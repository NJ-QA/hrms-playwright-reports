# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: exit/taskFilteringWorkflow.spec.js >> PIN-213: Exit Process > Task Templates & Tracking Filtering >> Flow 4: Results pagination and displayed records range (PIN_213_07)
- Location: tests/exit/taskFilteringWorkflow.spec.js:155:5

# Error details

```
Error: expect(received).toMatch(expected)

Expected pattern: /\d+[\s–-]+\d+\s+of\s+\d+|\d+\s+of\s+\d+/i
Received string:  "Rows per page:"
```

# Test source

```ts
  65  |         await expect(taskTrackingPage.searchInput, 'Search input must be visible').toBeVisible();
  66  |         await expect(taskTrackingPage.table, 'Task Tracking table must be visible').toBeVisible();
  67  | 
  68  |         const thead = taskTrackingPage.tableHeader;
  69  |         await expect(thead.getByText(/EMPLOYEE/i).first()).toBeVisible();
  70  |         await expect(thead.getByText(/DEPARTMENT/i).first()).toBeVisible();
  71  |         await expect(thead.getByText(/LOCATION/i).first()).toBeVisible();
  72  |         await expect(thead.getByText(/ACTIONS/i).first()).toBeVisible();
  73  | 
  74  |         logger.info('Flow 1: Verified all 4 primary filters, search input, and table layout');
  75  |     });
  76  | 
  77  |     // =========================================================================
  78  |     // FLOW 2: Multi-select Filter Behavior & Popover Options
  79  |     // Coverage: PIN_213_05
  80  |     // =========================================================================
  81  |     test('Flow 2: Multi-select filter selection support and option toggling (PIN_213_05)', async () => {
  82  |         logger.info('Running Flow 2: Multi-select filter behavior');
  83  | 
  84  |         // Open Department filter popover
  85  |         await taskTrackingPage.openDepartmentFilter();
  86  | 
  87  |         // Verify popover presentation
  88  |         if (await taskTrackingPage.filterPopover.isVisible({ timeout: 4000 }).catch(() => false)) {
  89  |             // Verify Search box inside popover
  90  |             if (await taskTrackingPage.popoverSearchInput.isVisible({ timeout: 2000 }).catch(() => false)) {
  91  |                 await expect(taskTrackingPage.popoverSearchInput).toBeEnabled();
  92  |             }
  93  | 
  94  |             // Verify Select All or multi-checkbox options presence
  95  |             const checkboxCount = await taskTrackingPage.filterPopover.locator('input[type="checkbox"]').count();
  96  |             logger.info(`Filter popover contains ${checkboxCount} selectable checkboxes`);
  97  |             expect(checkboxCount).toBeGreaterThanOrEqual(1);
  98  | 
  99  |             // Toggle first option to test multi-select capability
  100 |             const firstOption = taskTrackingPage.filterPopover.locator('input[type="checkbox"]').first();
  101 |             await firstOption.click();
  102 |             await page.waitForTimeout(500);
  103 | 
  104 |             // Close popover
  105 |             await taskTrackingPage.closeFilterPopover();
  106 |         } else {
  107 |             // Fallback: If filter operates as native select/input
  108 |             await taskTrackingPage.closeFilterPopover();
  109 |         }
  110 | 
  111 |         logger.info('Flow 2: Successfully verified multi-select filter capability');
  112 |     });
  113 | 
  114 |     // =========================================================================
  115 |     // FLOW 3: Dynamic Matching Exit Count & Employee Search
  116 |     // Coverage: PIN_213_06
  117 |     // =========================================================================
  118 |     test('Flow 3: Results and matching count display correctly with search filtering (PIN_213_06)', async () => {
  119 |         logger.info('Running Flow 3: Dynamic matching exit count and search filtering');
  120 | 
  121 |         // Verify Initial matching exits count (e.g. "3 matching exits" or "9 matching exits")
  122 |         const initialCount = await taskTrackingPage.getMatchingExitCount();
  123 |         logger.info(`Initial matching exit count: ${initialCount}`);
  124 |         expect(initialCount).toBeGreaterThanOrEqual(0);
  125 | 
  126 |         const initialRows = await taskTrackingPage.tableRows.count();
  127 |         logger.info(`Initial visible table rows: ${initialRows}`);
  128 | 
  129 |         if (initialRows > 0) {
  130 |             // Read first employee name to execute targeted search
  131 |             const firstRowText = (await taskTrackingPage.tableRows.first().textContent()) || '';
  132 |             const matchName = firstRowText.split(/\s+/).filter(w => w.length > 2)[0] || 'Auto';
  133 | 
  134 |             logger.info(`Filtering with search term: "${matchName}"`);
  135 |             await taskTrackingPage.search(matchName);
  136 | 
  137 |             const filteredCount = await taskTrackingPage.getMatchingExitCount();
  138 |             logger.info(`Filtered matching exit count: ${filteredCount}`);
  139 |             expect(filteredCount).toBeLessThanOrEqual(initialCount);
  140 | 
  141 |             // Clear search
  142 |             await taskTrackingPage.clearSearch();
  143 |             const restoredCount = await taskTrackingPage.getMatchingExitCount();
  144 |             expect(restoredCount).toBe(initialCount);
  145 |             logger.info(`Flow 3: Successfully verified dynamic count reflection and search restoration (${restoredCount})`);
  146 |         } else {
  147 |             logger.info('Flow 3: Table currently has 0 rows; verified empty-state count alignment');
  148 |         }
  149 |     });
  150 | 
  151 |     // =========================================================================
  152 |     // FLOW 4: Server-Side Pagination & Rows Per Page Controls
  153 |     // Coverage: PIN_213_07
  154 |     // =========================================================================
  155 |     test('Flow 4: Results pagination and displayed records range (PIN_213_07)', async () => {
  156 |         logger.info('Running Flow 4: Server-side pagination controls');
  157 | 
  158 |         // Verify pagination container
  159 |         await expect(taskTrackingPage.paginationContainer).toBeVisible();
  160 | 
  161 |         // Verify displayed range format (e.g. "1–3 of 3" or "1-1 of 1")
  162 |         if (await taskTrackingPage.displayedRowsText.isVisible({ timeout: 3000 }).catch(() => false)) {
  163 |             const rangeText = (await taskTrackingPage.displayedRowsText.textContent()) || '';
  164 |             logger.info(`Pagination displayed rows: "${rangeText}"`);
> 165 |             expect(rangeText).toMatch(/\d+[\s–-]+\d+\s+of\s+\d+|\d+\s+of\s+\d+/i);
      |                               ^ Error: expect(received).toMatch(expected)
  166 |         }
  167 | 
  168 |         // Verify Rows per page control
  169 |         await expect(taskTrackingPage.rowsPerPageSelect).toBeVisible();
  170 | 
  171 |         // Verify Next and Previous button elements exist
  172 |         await expect(taskTrackingPage.prevPageButton).toBeVisible();
  173 |         await expect(taskTrackingPage.nextPageButton).toBeVisible();
  174 | 
  175 |         // Previous button must be disabled on page 1
  176 |         await expect(taskTrackingPage.prevPageButton).toBeDisabled();
  177 |         logger.info('Flow 4: Verified pagination layout and button initial states');
  178 |     });
  179 | 
  180 |     // =========================================================================
  181 |     // FLOW 5: Remove / Change Filters & Clear Filters Restoration
  182 |     // Coverage: PIN_213_08
  183 |     // =========================================================================
  184 |     test('Flow 5: Remove/change filter and clear filters action (PIN_213_08)', async () => {
  185 |         logger.info('Running Flow 5: Filter removal and clear filters button action');
  186 | 
  187 |         const initialCount = await taskTrackingPage.getMatchingExitCount();
  188 | 
  189 |         // Type a dummy search to trigger filters active state
  190 |         await taskTrackingPage.search('NonExistentEmployee_XYZ_999');
  191 | 
  192 |         const filteredCount = await taskTrackingPage.getMatchingExitCount();
  193 |         expect(filteredCount).toBe(0);
  194 | 
  195 |         // Click Clear filters or clear search
  196 |         if (await taskTrackingPage.clearFiltersButton.isVisible({ timeout: 3000 }).catch(() => false)) {
  197 |             await taskTrackingPage.resetFilters();
  198 |         } else {
  199 |             await taskTrackingPage.clearSearch();
  200 |         }
  201 | 
  202 |         // Verify count restoration
  203 |         await expect.poll(async () => await taskTrackingPage.getMatchingExitCount(), {
  204 |             message: 'Count should restore after clearing active filters',
  205 |             timeout: 10_000,
  206 |             intervals: [1000, 2000]
  207 |         }).toBe(initialCount);
  208 | 
  209 |         logger.info('Flow 5: Successfully verified filter removal and clear filters restoration');
  210 |     });
  211 | 
  212 |     // =========================================================================
  213 |     // FLOW 6: Task Templates Filtering Specification Alignment (PIN-213 Acceptance Criteria)
  214 |     // =========================================================================
  215 |     test('Flow 6: Exit Task Templates page structure and filter specification readiness (PIN-213 AC)', async () => {
  216 |         logger.info('Running Flow 6: Task Templates page structure and filter specification readiness');
  217 | 
  218 |         await taskTemplatesComponent.goto();
  219 | 
  220 |         // Verify Task Templates tab & Add Task List button
  221 |         await expect(taskTemplatesComponent.taskTemplatesTab).toBeVisible();
  222 |         await expect(taskTemplatesComponent.addTaskListButton).toBeVisible();
  223 | 
  224 |         // Verify Search task lists control in the left pane
  225 |         const searchListInput = page.locator('input[placeholder*="Search task lists" i]').first();
  226 |         if (await searchListInput.isVisible({ timeout: 3000 }).catch(() => false)) {
  227 |             await expect(searchListInput).toBeEnabled();
  228 |         }
  229 | 
  230 |         logger.info('Flow 6: Task Templates component verified and aligned with filtering specification');
  231 |     });
  232 | });
  233 | 
```