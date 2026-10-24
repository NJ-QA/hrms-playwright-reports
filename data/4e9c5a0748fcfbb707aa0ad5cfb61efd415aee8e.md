# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: timeTracking/fixedFlexibleShift.spec.js >> Fixed and Flexible Shift Configuration & Versioning (PIN-126) >> Flow 1: Fixed Shift Timings, Day Configurations, Overnight & Breaks (PIN_126_01, 02, 03, 04, 09, 11, 12)
- Location: tests/timeTracking/fixedFlexibleShift.spec.js:64:5

# Error details

```
Error: expect(locator).toBeHidden() failed

Locator:  locator('.logout-modal-container, [role="dialog"]').filter({ hasText: /Delete Shift|Delete/i }).first()
Expected: hidden
Received: visible
Timeout:  9000ms

Call log:
  - Expect "toBeHidden" with timeout 9000ms
  - waiting for locator('.logout-modal-container, [role="dialog"]').filter({ hasText: /Delete Shift|Delete/i }).first()
    13 × locator resolved to <div role="dialog" tabindex="-1" aria-modal="true" aria-labelledby="«r17»" class="logout-modal-overlay">…</div>
       - unexpected value "visible"

```

# Page snapshot

```yaml
- generic [active]:
  - generic:
    - generic [ref=e1]:
      - generic [ref=e3]:
        - generic [ref=e4]:
          - link "Logo xperts" [ref=e5] [cursor=pointer]:
            - /url: /global/setting/general
            - img "Logo" [ref=e6]
            - heading "xperts" [level=2] [ref=e7]
          - button [ref=e8] [cursor=pointer]:
            - img [ref=e9]
        - separator [ref=e11]
        - list [ref=e13]:
          - listitem [ref=e14]:
            - button "Home" [ref=e15] [cursor=pointer]:
              - img [ref=e17]
              - generic [ref=e20]: Home
          - listitem [ref=e21]:
            - button "Me" [ref=e22] [cursor=pointer]:
              - img [ref=e24]
              - generic [ref=e28]: Me
              - img [ref=e29]
          - listitem [ref=e31]:
            - button "Messages 87" [ref=e32] [cursor=pointer]:
              - img [ref=e34]
              - generic [ref=e36]:
                - generic [ref=e37]: Messages
                - generic [ref=e38]: "87"
          - listitem [ref=e39]:
            - button "Organization" [ref=e40] [cursor=pointer]:
              - img [ref=e42]
              - generic [ref=e45]: Organization
              - img [ref=e46]
          - listitem [ref=e48]:
            - button "Schedule" [ref=e49] [cursor=pointer]:
              - img [ref=e51]
              - generic [ref=e54]: Schedule
          - listitem [ref=e55]:
            - button "Projects" [ref=e56] [cursor=pointer]:
              - img [ref=e58]
              - generic [ref=e61]: Projects
          - separator [ref=e62]
          - listitem [ref=e63]:
            - button "Attendance" [ref=e64] [cursor=pointer]:
              - img [ref=e66]
              - generic [ref=e69]: Attendance
              - img [ref=e70]
          - listitem [ref=e72]:
            - button "Time Tracking" [ref=e73] [cursor=pointer]:
              - img [ref=e75]
              - generic [ref=e78]: Time Tracking
              - img [ref=e79]
          - listitem [ref=e81]:
            - button "Hiring" [ref=e82] [cursor=pointer]:
              - img [ref=e84]
              - generic [ref=e87]: Hiring
              - img [ref=e88]
          - listitem [ref=e90]:
            - button "Reports" [ref=e91] [cursor=pointer]:
              - img [ref=e93]
              - generic [ref=e96]: Reports
          - listitem [ref=e97]:
            - button "Communication" [ref=e98] [cursor=pointer]:
              - img [ref=e100]
              - generic [ref=e103]: Communication
          - listitem [ref=e104]:
            - button "Benefits" [ref=e105] [cursor=pointer]:
              - img [ref=e107]
              - generic [ref=e110]: Benefits
          - listitem [ref=e111]:
            - button "Recruit" [ref=e112] [cursor=pointer]:
              - img [ref=e114]
              - generic [ref=e117]: Recruit
          - listitem [ref=e118]:
            - button "Candidate" [ref=e119] [cursor=pointer]:
              - img [ref=e121]
              - generic [ref=e125]: Candidate
          - listitem [ref=e126]:
            - button "Payment" [ref=e127] [cursor=pointer]:
              - img [ref=e129]
              - generic [ref=e132]: Payment
          - listitem [ref=e133]:
            - button "Chats" [ref=e134] [cursor=pointer]:
              - img [ref=e136]
              - generic [ref=e139]: Chats
      - generic [ref=e140]:
        - generic [ref=e142]:
          - generic [ref=e144]: Good Evening Neeraj !
          - generic [ref=e145]:
            - img [ref=e146]
            - textbox "Search employee and action (Ex., leave, exit)" [ref=e148]
          - generic [ref=e149]:
            - generic "Help" [ref=e150]:
              - button [ref=e151] [cursor=pointer]:
                - img [ref=e152]
            - generic "Messages" [ref=e154]:
              - button [ref=e155] [cursor=pointer]:
                - img [ref=e156]
            - generic "Notifications" [ref=e158]:
              - button "1" [ref=e159] [cursor=pointer]:
                - generic [ref=e160]:
                  - img [ref=e161]
                  - generic [ref=e163]: "1"
            - generic "Global Settings" [ref=e164]:
              - button [ref=e165] [cursor=pointer]:
                - img [ref=e166]
            - button "EN" [ref=e169] [cursor=pointer]:
              - img [ref=e171]
              - generic [ref=e178]: EN
              - img [ref=e179]
            - generic [ref=e182] [cursor=pointer]:
              - img "profile" [ref=e184]
              - generic [ref=e185]:
                - generic [ref=e186]: Neeraj
                - generic [ref=e187]: xperts_imaging@yopmail.com
        - generic [ref=e189]:
          - generic [ref=e190]:
            - tablist [ref=e191]:
              - tab "Shifts/Weekly Offs & Holidays" [selected] [ref=e192] [cursor=pointer]:
                - generic [ref=e193]: Shifts/Weekly Offs & Holidays
              - tab "Attendance Tracking" [ref=e194] [cursor=pointer]:
                - generic [ref=e195]: Attendance Tracking
              - tab "Leave Management" [ref=e196] [cursor=pointer]:
                - generic [ref=e197]: Leave Management
              - tab "Settings" [ref=e198] [cursor=pointer]:
                - generic [ref=e199]: Settings
            - separator [ref=e200]
          - generic [ref=e202]:
            - tablist [ref=e203]:
              - tab "Shift & Weekly Offs" [selected] [ref=e204] [cursor=pointer]:
                - generic [ref=e205]: Shift & Weekly Offs
              - tab "Shift Allowance" [ref=e206] [cursor=pointer]:
                - generic [ref=e207]: Shift Allowance
              - tab "Assignments" [ref=e208] [cursor=pointer]:
                - generic [ref=e209]: Assignments
              - tab "Holidays" [ref=e210] [cursor=pointer]:
                - generic [ref=e211]: Holidays
            - tabpanel [ref=e212]:
              - generic [ref=e213]:
                - tablist [ref=e214]:
                  - tab "Shifts" [selected] [ref=e215] [cursor=pointer]:
                    - generic [ref=e216]: Shifts
                  - tab "Weekly Offs" [ref=e217] [cursor=pointer]:
                    - generic [ref=e218]: Weekly Offs
                  - tab "Shift & Weekly Off Rules" [ref=e219] [cursor=pointer]:
                    - generic [ref=e220]: Shift & Weekly Off Rules
                - tabpanel [ref=e221]:
                  - generic [ref=e223]:
                    - generic [ref=e224]:
                      - generic [ref=e225]:
                        - generic [ref=e226]:
                          - img [ref=e227]
                          - paragraph [ref=e230]: Shifts
                        - button "+ Add Shift" [ref=e232] [cursor=pointer]
                      - generic [ref=e235]:
                        - img [ref=e237]
                        - textbox "Search by shift name or code..." [ref=e239]: QA Shift Night mvltf9hdzcly
                        - group
                      - generic [ref=e243]:
                        - img [ref=e245]
                        - paragraph [ref=e248]: Shifts Not Found
                        - paragraph [ref=e249]: No shifts found.
                        - button "Add Shift" [ref=e250] [cursor=pointer]
                    - generic [ref=e252]:
                      - img [ref=e254]
                      - heading "No Shift Selected" [level=6] [ref=e257]
                      - paragraph [ref=e258]: Please select a shift from the list on the left to review its timing rules, active versions, and overall configuration.
      - generic [ref=e259]:
        - generic [ref=e260]:
          - heading "Theme & Style" [level=6] [ref=e261]
          - img [ref=e262] [cursor=pointer]
        - generic [ref=e264]:
          - generic [ref=e265]:
            - heading "Theme Mode" [level=6] [ref=e266]:
              - img [ref=e267]
              - text: Theme Mode
            - generic [ref=e269]:
              - button "Light" [ref=e270] [cursor=pointer]:
                - img [ref=e271]
                - text: Light
              - button "Dark" [ref=e273] [cursor=pointer]:
                - img [ref=e274]
                - text: Dark
              - button "Auto" [ref=e276] [cursor=pointer]:
                - img [ref=e277]
                - text: Auto
          - generic [ref=e279]:
            - heading "Theme Color" [level=6] [ref=e280]:
              - img [ref=e281]
              - text: Theme Color
            - generic [ref=e283]:
              - generic "Default" [ref=e284] [cursor=pointer]
              - generic "Orange" [ref=e286] [cursor=pointer]
              - generic "Marun" [ref=e288] [cursor=pointer]
              - generic "Blue" [ref=e290] [cursor=pointer]
              - generic "Green" [ref=e292] [cursor=pointer]
              - generic "Gray" [ref=e294] [cursor=pointer]
          - generic [ref=e296]:
            - heading "Dashboard Layout" [level=6] [ref=e297]
            - generic [ref=e298]:
              - button "Default" [ref=e299] [cursor=pointer]:
                - img [ref=e300]
                - text: Default
              - button "New Layout" [ref=e302] [cursor=pointer]:
                - img [ref=e303]
                - text: New Layout
      - generic [ref=e305]:
        - generic [ref=e306]:
          - heading "Change Password" [level=6] [ref=e307]
          - img [ref=e308] [cursor=pointer]
        - generic [ref=e310]:
          - generic [ref=e311]:
            - text: "You are currently logged in as:"
            - strong [ref=e312]: xperts_imaging@yopmail.com
            - generic [ref=e313]: Please enter your current password to verify your identity, then create a strong new password to keep your account secure.
          - alert [ref=e314]:
            - img [ref=e316]
            - generic [ref=e319]:
              - strong [ref=e320]: Security Notice
              - generic [ref=e321]: For your safety, you will be automatically logged out after a successful password change.
          - generic [ref=e322]:
            - generic [ref=e324]:
              - generic [ref=e325]:
                - generic [ref=e327]:
                  - text: Old Password
                  - generic [ref=e328]: "*"
                - textbox "Enter your current password" [ref=e330]
              - img [ref=e332] [cursor=pointer]
            - generic [ref=e335]:
              - generic [ref=e336]:
                - generic [ref=e338]:
                  - text: New Password
                  - generic [ref=e339]: "*"
                - textbox "Create a strong new password" [ref=e341]
              - img [ref=e343] [cursor=pointer]
            - generic [ref=e346]:
              - generic [ref=e347]:
                - generic [ref=e349]:
                  - text: Confirm Password
                  - generic [ref=e350]: "*"
                - textbox "Re-enter your new password" [disabled] [ref=e352]
              - img [ref=e354]
            - button "Update Password" [ref=e356] [cursor=pointer]
    - alert [ref=e357]:
      - img [ref=e359]
      - generic [ref=e361]:
        - generic [ref=e362]: SUCCESS
        - text: Shift "QA Shift Night mvltf9hdzcly" has been deleted successfully
      - button "Close" [ref=e364] [cursor=pointer]:
        - img [ref=e365]
```

# Test source

```ts
  121 |         await expect(this.splitListContainer).toBeVisible({ timeout: 30_000 });
  122 |         await expect(this.detailsCard).toBeVisible({ timeout: 30_000 });
  123 |     }
  124 | 
  125 |     async openAddShiftModal() {
  126 |         logger.info('Opening Add Shift modal');
  127 |         await expect(this.addShiftButton).toBeVisible();
  128 |         await this.addShiftButton.click();
  129 |         await this.addShiftModal.waitForOpen();
  130 |         return this.addShiftModal;
  131 |     }
  132 | 
  133 |     async searchShift(query) {
  134 |         logger.info(`Searching for shift: ${query}`);
  135 |         await this.searchInput.clear();
  136 |         await this.searchInput.fill(query);
  137 |         await this.page.waitForTimeout(500);
  138 |     }
  139 | 
  140 |     async selectShiftByName(name) {
  141 |         logger.info(`Selecting shift by name: ${name}`);
  142 |         await this.searchShift(name);
  143 |         // List labels are visually truncated; searching by the full name narrows the list.
  144 |         await expect(this.shiftItems).toHaveCount(1);
  145 |         await this.shiftItems.first().click();
  146 |         await expect(this.shiftHeading).toHaveText(name);
  147 |     }
  148 | 
  149 |     async openShiftMenu() {
  150 |         logger.info('Opening shift details menu');
  151 |         await expect(this.menuButton).toBeVisible();
  152 |         await this.menuButton.click();
  153 |         await this.page.waitForTimeout(300);
  154 |         const menu = this.page.locator('[role="menu"], .MuiMenu-paper, ul.MuiMenu-list').first();
  155 |         await expect(menu).toBeVisible();
  156 |         return menu;
  157 |     }
  158 | 
  159 |     async renameSelectedShift() {
  160 |         logger.info('Clicking Rename in shift menu');
  161 |         await this.openShiftMenu();
  162 |         const renameOption = this.page.locator('[role="menuitem"], .MuiMenuItem-root, li')
  163 |             .filter({ hasText: /rename/i })
  164 |             .first();
  165 |         await expect(renameOption).toBeVisible();
  166 |         await renameOption.click();
  167 |         await this.renameShiftModal.waitForOpen();
  168 |         return this.renameShiftModal;
  169 |     }
  170 | 
  171 |     async setAsDefaultSelectedShift() {
  172 |         logger.info('Setting selected shift as default');
  173 |         await this.openShiftMenu();
  174 |         const defaultOption = this.page.locator('[role="menuitem"], .MuiMenuItem-root, li')
  175 |             .filter({ hasText: /default/i })
  176 |             .first();
  177 |         await expect(defaultOption).toBeVisible();
  178 |         await defaultOption.click();
  179 | 
  180 |         const confirmDialog = this.page.getByRole('dialog', { name: 'Set Default Shift', exact: true });
  181 |         await expect(confirmDialog).toBeVisible();
  182 |         await confirmDialog.getByRole('button', { name: 'Set Default', exact: true }).click();
  183 |         await expect(confirmDialog).toBeHidden();
  184 |     }
  185 | 
  186 |     async deleteSelectedShift() {
  187 |         logger.info('Deleting selected shift');
  188 |         await this.openShiftMenu();
  189 |         const deleteOption = this.page.locator('[role="menuitem"], .MuiMenuItem-root, li')
  190 |             .filter({ hasText: /delete/i })
  191 |             .first();
  192 | 
  193 |         if (await deleteOption.count() === 0) {
  194 |             await this.page.keyboard.press('Escape');
  195 |             return false;
  196 |         }
  197 | 
  198 |         const isDisabled = await deleteOption.evaluate(el =>
  199 |             el.getAttribute('aria-disabled') === 'true' ||
  200 |             el.classList.contains('Mui-disabled') ||
  201 |             el.hasAttribute('disabled')
  202 |         );
  203 | 
  204 |         if (isDisabled) {
  205 |             await this.page.keyboard.press('Escape');
  206 |             return false;
  207 |         }
  208 | 
  209 |         await deleteOption.click();
  210 | 
  211 |         const confirmDialog = this.page.locator('.logout-modal-container, [role="dialog"]')
  212 |             .filter({ hasText: /Delete Shift|Delete/i })
  213 |             .first();
  214 |         await expect(confirmDialog).toBeVisible();
  215 | 
  216 |         const confirmButton = confirmDialog.getByRole('button', { name: /^Delete$/i })
  217 |             .or(confirmDialog.locator('button').filter({ hasText: /^Delete$/i }))
  218 |             .first();
  219 |         await expect(confirmButton).toBeVisible();
  220 |         await confirmButton.click();
> 221 |         await expect(confirmDialog).toBeHidden();
      |                                     ^ Error: expect(locator).toBeHidden() failed
  222 |         return true;
  223 |     }
  224 | 
  225 |     versionRows(status) {
  226 |         const rows = this.detailsContainer.locator('.shift-detail-version-row');
  227 |         return status ? rows.filter({ has: this.page.locator('p').filter({ hasText: new RegExp(`${status}$`) }) }) : rows;
  228 |     }
  229 | 
  230 |     async editSelectedShift() {
  231 |         await this.openTrackVersionsTab();
  232 |         const current = this.versionRows('Current');
  233 |         await expect(current).toHaveCount(1);
  234 |         await current.getByRole('button', { name: 'Edit Version', exact: true }).click();
  235 |         await this.addShiftModal.waitForOpen();
  236 |         return this.addShiftModal;
  237 |     }
  238 | 
  239 |     async openSummaryTab() {
  240 |         logger.info('Opening Summary tab');
  241 |         await expect(this.summaryTab).toBeVisible();
  242 |         await this.summaryTab.click();
  243 |         await this.page.waitForTimeout(500);
  244 |     }
  245 | 
  246 |     async openEmployeesTab() {
  247 |         logger.info('Opening Employees tab');
  248 |         await expect(this.employeesTab).toBeVisible();
  249 |         await this.employeesTab.click();
  250 |         await this.page.waitForTimeout(500);
  251 |     }
  252 | 
  253 |     async openTrackVersionsTab() {
  254 |         logger.info('Opening Track Shift Versions tab');
  255 |         await expect(this.trackVersionsTab).toBeVisible();
  256 |         await this.trackVersionsTab.click();
  257 |         await this.page.waitForTimeout(500);
  258 |     }
  259 | 
  260 |     async deleteUpcomingVersion() {
  261 |         logger.info('Deleting upcoming shift version');
  262 |         await this.openTrackVersionsTab();
  263 |         const deleteBtn = this.detailsContainer.locator('.version-delete-btn, button[aria-label*="delete" i], button:has-text("Delete")')
  264 |             .or(this.detailsContainer.locator('.shift-version-card, tr, .version-item').filter({ hasText: /Upcoming/i }).locator('button:has(svg), button:has-text("Delete")'))
  265 |             .first();
  266 |         if (await deleteBtn.isVisible()) {
  267 |             await deleteBtn.click();
  268 |             const confirmDialog = this.page.locator('.logout-modal-container, [role="dialog"]')
  269 |                 .filter({ hasText: /Delete|Confirm/i })
  270 |                 .first();
  271 |             if (await confirmDialog.isVisible()) {
  272 |                 const confirmBtn = confirmDialog.getByRole('button', { name: /^Delete$/i })
  273 |                     .or(confirmDialog.locator('button').filter({ hasText: /^Delete$/i }))
  274 |                     .first();
  275 |                 await confirmBtn.click();
  276 |                 await expect(confirmDialog).toBeHidden();
  277 |             }
  278 |             return true;
  279 |         }
  280 |         return false;
  281 |     }
  282 | 
  283 |     async deleteShiftByName(name) {
  284 |         logger.info(`Deleting shift with name: ${name}`);
  285 |         await this.searchShift(name);
  286 |         const shiftItem = this.shiftItems.filter({ hasText: name }).first();
  287 |         if (await shiftItem.count() > 0 && await shiftItem.isVisible()) {
  288 |             await shiftItem.click();
  289 |             await this.page.waitForTimeout(400);
  290 |             return await this.deleteSelectedShift();
  291 |         }
  292 |         return false;
  293 |     }
  294 | 
  295 |     async cleanupTestShifts(prefix = 'QA Shift') {
  296 |         logger.info(`Cleaning up test shifts starting with: ${prefix}`);
  297 |         await this.searchShift(prefix);
  298 |         let count = await this.shiftItems.count();
  299 |         let maxAttempts = 15;
  300 |         while (count > 0 && maxAttempts > 0) {
  301 |             const firstItem = this.shiftItems.first();
  302 |             if (!(await firstItem.isVisible())) break;
  303 |             await firstItem.click();
  304 |             await this.page.waitForTimeout(400);
  305 |             const deleted = await this.deleteSelectedShift();
  306 |             if (!deleted) break;
  307 |             await this.searchShift(prefix);
  308 |             count = await this.shiftItems.count();
  309 |             maxAttempts--;
  310 |         }
  311 |     }
  312 | }
  313 | 
  314 | module.exports = ShiftManagementPage;
  315 | 
```