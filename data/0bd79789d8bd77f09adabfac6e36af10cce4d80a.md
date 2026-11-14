# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: employee/shiftAllowancePolicyAssignment.spec.js >> PIN-229: Employee Profile > Employee Time | Add or update Shift allowance policy >> Flow 1 (PIN-229-1 to PIN-229-3, PIN-229-10 to PIN-229-19, PIN-229-26): Field Display, Drawer Controls, Date Rules, Validations & Dismiss Rules
- Location: tests/employee/shiftAllowancePolicyAssignment.spec.js:74:5

# Error details

```
Error: locator.setChecked: Element is outside of the viewport
Call log:
  - waiting for locator('.right-sideBar.shift-sideBar.openRightSideBar').filter({ has: locator('h6').filter({ hasText: /Update Shift Allowance Policy/i }) }).first().locator('label').filter({ hasText: /doesn't have an end date/i }).first().locator('input[type="checkbox"]').or(locator('.right-sideBar.shift-sideBar.openRightSideBar').filter({ has: locator('h6').filter({ hasText: /Update Shift Allowance Policy/i }) }).first().locator('input[name="noEndDate"]')).first().or(locator('.right-sideBar.shift-sideBar.openRightSideBar').filter({ has: locator('h6').filter({ hasText: /Update Shift Allowance Policy/i }) }).first().locator('label').filter({ hasText: /doesn't have an end date/i }).first().locator('input')).or(locator('input[name="noEndDate"]')).first()
    - locator resolved to <input type="checkbox" name="noEndDate" data-indeterminate="false" class="PrivateSwitchBase-input css-j8yymo"/>
  - attempting click action
    - scrolling into view if needed
    - done scrolling

```

# Test source

```ts
  13  |             has: page.locator('h6', { hasText: /Update Shift Allowance Policy/i })
  14  |         }).first();
  15  | 
  16  |         this.headerTitle = this.drawer.locator('h6').filter({ hasText: /Update Shift Allowance Policy/i }).first();
  17  |         this.closeIcon = this.drawer.locator('.right-sidebar-close-icon, h6 + img, .right-sidebar-header img, button:has(svg), img[cursor="pointer"]').first();
  18  | 
  19  |         // Form Fields
  20  |         this.reasonGroup = this.drawer.locator('.hrms-form-group[data-field-name="reason"]');
  21  |         this.reasonSelect = this.reasonGroup.locator('#mui-component-select-reason, [role="combobox"]').first();
  22  |         this.reasonNativeInput = this.reasonGroup.locator('input[name="reason"]');
  23  | 
  24  |         this.policyGroup = this.drawer.locator('.hrms-form-group[data-field-name="policyId"]');
  25  |         this.policySelect = this.policyGroup.locator('#mui-component-select-policyId, [role="combobox"]').first();
  26  |         this.policyNativeInput = this.policyGroup.locator('input[name="policyId"]');
  27  | 
  28  |         this.noLongerPartOfPolicyLabel = this.drawer.locator('label').filter({
  29  |             hasText: /no longer part of any Shift Allowance Policy/i
  30  |         }).first();
  31  |         this.noLongerPartOfPolicyCheckbox = this.noLongerPartOfPolicyLabel.locator('input[type="checkbox"]').or(this.drawer.locator('input[name="noLongerPartOfPolicy"]')).first();
  32  | 
  33  |         this.effectiveFromGroup = this.drawer.locator('.hrms-form-group[data-field-name="effectiveFrom"]');
  34  |         this.effectiveFromInput = this.effectiveFromGroup.locator('input[name="effectiveFrom"]');
  35  |         this.effectiveFromCalendarBtn = this.effectiveFromGroup.locator('button[aria-label="Choose date"]');
  36  | 
  37  |         this.effectiveToGroup = this.drawer.locator('.hrms-form-group[data-field-name="effectiveTo"]');
  38  |         this.effectiveToInput = this.effectiveToGroup.locator('input[name="effectiveTo"]');
  39  |         this.effectiveToCalendarBtn = this.effectiveToGroup.locator('button[aria-label="Choose date"]');
  40  | 
  41  |         this.noEndDateLabel = this.drawer.locator('label').filter({
  42  |             hasText: /doesn't have an end date/i
  43  |         }).first();
  44  |         this.noEndDateCheckbox = this.noEndDateLabel.locator('input[type="checkbox"]').or(this.drawer.locator('input[name="noEndDate"]')).first();
  45  | 
  46  |         // Bottom History Accordion inside drawer
  47  |         this.historySection = this.drawer.locator('.update-shift-history-section, div:has-text("Shift allowance policy assignment history")').first();
  48  |         this.historyAccordionHeader = this.historySection.locator('.ant-collapse-header, .MuiAccordionSummary-root, h6, [role="button"]').first();
  49  | 
  50  |         // Footer buttons
  51  |         this.cancelButton = this.drawer.getByRole('button', { name: /^Cancel$/i }).first();
  52  |         this.updateButton = this.drawer.getByRole('button', { name: /^Update$/i }).first();
  53  | 
  54  |         // Overlay mask
  55  |         this.backdropMask = page.locator('.MuiBackdrop-root, .drawer-overlay, .ant-drawer-mask').first();
  56  |     }
  57  | 
  58  |     async verifyOpen() {
  59  |         logger.info('Verifying Update Shift Allowance Policy drawer is open');
  60  |         await expect(this.drawer).toBeVisible({ timeout: 15_000 });
  61  |         await expect(this.headerTitle).toHaveText('Update Shift Allowance Policy');
  62  |         return this;
  63  |     }
  64  | 
  65  |     async selectReason(reasonText) {
  66  |         logger.info(`Selecting reason: "${reasonText}"`);
  67  |         await this.reasonSelect.click();
  68  |         const option = this.page.getByRole('option').filter({ hasText: new RegExp(reasonText, 'i') }).first();
  69  |         await expect(option).toBeVisible({ timeout: 5_000 });
  70  |         await option.click();
  71  |         return this;
  72  |     }
  73  | 
  74  |     async openPolicyDropdown() {
  75  |         logger.info('Opening Shift Allowance Policy dropdown');
  76  |         await this.policySelect.click();
  77  |         return this;
  78  |     }
  79  | 
  80  |     async selectPolicy(policyName) {
  81  |         logger.info(`Selecting policy: "${policyName}"`);
  82  |         await this.openPolicyDropdown();
  83  |         const option = this.page.getByRole('option').filter({ hasText: new RegExp(`^${policyName}$`, 'i') }).first();
  84  |         await expect(option).toBeVisible({ timeout: 10_000 });
  85  |         await option.click();
  86  |         return this;
  87  |     }
  88  | 
  89  |     async toggleNoLongerPartOfPolicy(check = true) {
  90  |         logger.info(`Setting "Employee is no longer part of any Shift Allowance Policy" to ${check}`);
  91  |         const checkbox = this.noLongerPartOfPolicyCheckbox.or(this.noLongerPartOfPolicyLabel.locator('input')).or(this.page.locator('input[name="noLongerPartOfPolicy"]')).first();
  92  |         const isChecked = await checkbox.isChecked().catch(() => !check);
  93  |         if (isChecked !== check) {
  94  |             const clickTarget = this.noLongerPartOfPolicyLabel.or(checkbox).first();
  95  |             await clickTarget.click({ force: true }).catch(async () => {
  96  |                 await checkbox.setChecked(check, { force: true });
  97  |             });
  98  |             await this.page.waitForTimeout(300);
  99  |             if (await checkbox.isChecked().catch(() => false) !== check) {
  100 |                 await checkbox.setChecked(check, { force: true }).catch(() => {});
  101 |             }
  102 |         }
  103 |         return this;
  104 |     }
  105 | 
  106 |     async toggleNoEndDate(check = true) {
  107 |         logger.info(`Setting "Shift allowance policy doesn't have an end date" to ${check}`);
  108 |         const checkbox = this.noEndDateCheckbox.or(this.noEndDateLabel.locator('input')).or(this.page.locator('input[name="noEndDate"]')).first();
  109 |         const isChecked = await checkbox.isChecked().catch(() => !check);
  110 |         if (isChecked !== check) {
  111 |             const clickTarget = this.noEndDateLabel.or(checkbox).first();
  112 |             await clickTarget.click({ force: true }).catch(async () => {
> 113 |                 await checkbox.setChecked(check, { force: true });
      |                                ^ Error: locator.setChecked: Element is outside of the viewport
  114 |             });
  115 |             await this.page.waitForTimeout(300);
  116 |             if (await checkbox.isChecked().catch(() => false) !== check) {
  117 |                 await checkbox.setChecked(check, { force: true }).catch(() => {});
  118 |             }
  119 |         }
  120 |         return this;
  121 |     }
  122 | 
  123 |     async setEffectiveFromDate(dateStr) {
  124 |         logger.info(`Setting Effective From date: ${dateStr}`);
  125 |         // Click and fill directly, or fill via sections
  126 |         await this.effectiveFromInput.fill(dateStr);
  127 |         return this;
  128 |     }
  129 | 
  130 |     async setEffectiveToDate(dateStr) {
  131 |         logger.info(`Setting Effective To date: ${dateStr}`);
  132 |         await this.effectiveToInput.fill(dateStr);
  133 |         return this;
  134 |     }
  135 | 
  136 |     async clickUpdate() {
  137 |         logger.info('Clicking Update button in drawer');
  138 |         await expect(this.updateButton).toBeVisible({ timeout: 5_000 });
  139 |         await this.updateButton.click();
  140 |         return this;
  141 |     }
  142 | 
  143 |     async clickCancel() {
  144 |         logger.info('Clicking Cancel button in drawer');
  145 |         await this.cancelButton.click();
  146 |         return this;
  147 |     }
  148 | 
  149 |     async close() {
  150 |         logger.info('Closing Update Shift Allowance Policy drawer via close icon');
  151 |         await this.closeIcon.click();
  152 |         return this;
  153 |     }
  154 | }
  155 | 
  156 | module.exports = UpdateShiftAllowanceDrawer;
  157 | 
```