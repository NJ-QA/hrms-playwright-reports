# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: exit/reviewExitWorkflow.spec.js >> PIN-200: Termination and Resignation Request Review — Approval, Rejection, and Exit Handoff >> PIN_200_20, PIN_200_21, PIN_200_22: Reviewer comment validation (Blank blocked, Whitespace-only blocked, 1000 characters maximum)
- Location: tests/exit/reviewExitWorkflow.spec.js:164:5

# Error details

```
Error: Reject decision option should be visible

expect(locator).toBeVisible() failed

Locator: locator('[role="dialog"], .MuiDialog-paper').filter({ hasText: /review form|Resignation approval|Exit details/i }).first().locator('label').filter({ hasText: /REJECT TERMINATION|REJECT RESIGNATION|^Reject$/i }).locator('input[type="radio"]').or(locator('[role="dialog"], .MuiDialog-paper').filter({ hasText: /review form|Resignation approval|Exit details/i }).first().locator('input[type="radio"][value*="REJECT" i]')).first().or(locator('[role="dialog"], .MuiDialog-paper').filter({ hasText: /review form|Resignation approval|Exit details/i }).first().getByText(/Reject/i).first())
Expected: visible
Timeout: 10000ms
Error: element(s) not found

Call log:
  - Reject decision option should be visible with timeout 10000ms
  - waiting for locator('[role="dialog"], .MuiDialog-paper').filter({ hasText: /review form|Resignation approval|Exit details/i }).first().locator('label').filter({ hasText: /REJECT TERMINATION|REJECT RESIGNATION|^Reject$/i }).locator('input[type="radio"]').or(locator('[role="dialog"], .MuiDialog-paper').filter({ hasText: /review form|Resignation approval|Exit details/i }).first().locator('input[type="radio"][value*="REJECT" i]')).first().or(locator('[role="dialog"], .MuiDialog-paper').filter({ hasText: /review form|Resignation approval|Exit details/i }).first().getByText(/Reject/i).first())

```

# Test source

```ts
  1   | const { expect } = require('@playwright/test');
  2   | const BaseComponent = require('@pages/components/BaseComponent');
  3   | const logger = require('@utils/logger/logger');
  4   | 
  5   | /**
  6   |  * Review Exit Modal Component (PIN-200)
  7   |  * Corresponds to "Termination review form" and "Resignation review form"
  8   |  * as seen in live UI (Image 91.png & Image 95.png).
  9   |  */
  10  | class ReviewExitModal extends BaseComponent {
  11  |     /**
  12  |      * @param {import('@playwright/test').Page} page
  13  |      */
  14  |     constructor(page) {
  15  |         super(page);
  16  | 
  17  |         // Dialog container & Header
  18  |         this.dialog = page.locator('[role="dialog"], .MuiDialog-paper').filter({
  19  |             hasText: /review form|Resignation approval|Exit details/i
  20  |         }).first();
  21  | 
  22  |         this.dialogTitle = this.dialog.locator('h2, h3, [class*="title"], [class*="header"]').filter({
  23  |             hasText: /Termination review form|Resignation review form|Resignation approval/i
  24  |         }).first();
  25  | 
  26  |         this.closeButton = this.dialog.locator('button[aria-label="close" i], button:has(svg[data-testid="CloseIcon"])').first();
  27  | 
  28  |         // 1. Decision Radio Options: ACCEPT TERMINATION / REJECT TERMINATION (or ACCEPT RESIGNATION / REJECT RESIGNATION)
  29  |         this.acceptDecisionRadio = this.dialog.locator('label').filter({
  30  |             hasText: /ACCEPT TERMINATION|ACCEPT RESIGNATION|^Approve$/i
  31  |         }).locator('input[type="radio"]').or(
  32  |             this.dialog.locator('input[type="radio"][value*="ACCEPT" i], input[type="radio"][value*="APPROVE" i]')
  33  |         ).first();
  34  | 
  35  |         this.rejectDecisionRadio = this.dialog.locator('label').filter({
  36  |             hasText: /REJECT TERMINATION|REJECT RESIGNATION|^Reject$/i
  37  |         }).locator('input[type="radio"]').or(
  38  |             this.dialog.locator('input[type="radio"][value*="REJECT" i]')
  39  |         ).first();
  40  | 
  41  |         // 2. Recommended Last Working Day (LWD)
  42  |         this.systemCalculatedLwdRadio = this.dialog.locator('label').filter({
  43  |             hasText: /SYSTEM-CALCULATED NOTICE PERIOD|System[\s-]Calculated/i
  44  |         }).locator('input[type="radio"]').first();
  45  | 
  46  |         this.chooseAnotherDateRadio = this.dialog.locator('label').filter({
  47  |             hasText: /CHOOSE ANOTHER DATE|Custom/i
  48  |         }).locator('input[type="radio"]').first();
  49  | 
  50  |         this.chooseAnotherDateInput = this.dialog.locator('input[type="text"], input[placeholder*="DD/MM/YYYY" i]').filter({
  51  |             hasNot: this.dialog.locator('textarea')
  52  |         }).first();
  53  | 
  54  |         // Holiday / Weekoff validation error on LWD (PIN_200_14, PIN_200_36)
  55  |         this.lwdHolidayError = this.dialog.locator('text=/which is a weekly off|cannot fall on a weekly off or holiday|before DOJ/i').first();
  56  | 
  57  |         // 3. Mark Employee as Eligible for Rehire
  58  |         this.eligibleForRehireCheckbox = this.dialog.locator('label').filter({
  59  |             hasText: /Mark employee as eligible for rehire/i
  60  |         }).locator('input[type="checkbox"]').first();
  61  | 
  62  |         // 4. Comment (Mandatory, max 1000 characters)
  63  |         this.commentInput = this.dialog.locator('textarea').first();
  64  |         this.commentError = this.dialog.locator('.Mui-error, [class*="error"]').filter({
  65  |             hasText: /required|cannot be blank|cannot be empty/i
  66  |         }).first();
  67  | 
  68  |         // 5. Add Attachment
  69  |         this.fileInput = this.dialog.locator('input[type="file"]').first();
  70  |         this.addAttachmentButton = this.dialog.locator('button, label, div').filter({
  71  |             hasText: /Add attachment/i
  72  |         }).first();
  73  | 
  74  |         // 6. Advisory Banner
  75  |         this.advisoryBanner = this.dialog.locator('div').filter({
  76  |             hasText: /On submission, this request will be approved/i
  77  |         }).first();
  78  | 
  79  |         // 7. Footer Action Buttons
  80  |         this.cancelButton = this.dialog.getByRole('button', { name: /^Cancel$/i }).first();
  81  |         this.submitButton = this.dialog.getByRole('button', { name: /^Submit$/i }).first();
  82  |     }
  83  | 
  84  |     /**
  85  |      * Verifies that the Review Exit modal is loaded.
  86  |      */
  87  |     async verifyLoaded() {
  88  |         logger.info('Verifying Review Exit form dialog is loaded');
  89  |         await expect(this.dialog, 'Review Exit dialog should be visible').toBeVisible({ timeout: 15_000 });
  90  |         const titleVisible = await this.dialogTitle.isVisible({ timeout: 3000 }).catch(() => false);
  91  |         if (titleVisible) {
  92  |             await expect(this.dialogTitle).toBeVisible();
  93  |         }
  94  |         await expect(this.acceptDecisionRadio.or(this.dialog.getByText(/Accept|Approve/i).first()), 'Accept decision option should be visible').toBeVisible({ timeout: 10_000 });
> 95  |         await expect(this.rejectDecisionRadio.or(this.dialog.getByText(/Reject/i).first()), 'Reject decision option should be visible').toBeVisible({ timeout: 10_000 });
      |                                                                                                                                         ^ Error: Reject decision option should be visible
  96  |         await expect(this.commentInput, 'Comment textarea should be visible').toBeVisible({ timeout: 10_000 });
  97  |     }
  98  | 
  99  |     /**
  100 |      * Selects Accept / Approve.
  101 |      */
  102 |     async selectAccept() {
  103 |         logger.info('Selecting ACCEPT decision');
  104 |         await this.acceptDecisionRadio.click();
  105 |     }
  106 | 
  107 |     /**
  108 |      * Selects Reject.
  109 |      */
  110 |     async selectReject() {
  111 |         logger.info('Selecting REJECT decision');
  112 |         await this.rejectDecisionRadio.click();
  113 |     }
  114 | 
  115 |     /**
  116 |      * Fills the review comment.
  117 |      * @param {string} comment
  118 |      */
  119 |     async fillComment(comment) {
  120 |         logger.info(`Filling review comment: "${comment}"`);
  121 |         await this.commentInput.fill(comment);
  122 |     }
  123 | 
  124 |     /**
  125 |      * Selects LWD: System Calculated or Choose Another Date.
  126 |      * @param {'SYSTEM' | 'ANOTHER_DATE'} choice
  127 |      * @param {string} [customDate]
  128 |      */
  129 |     async selectLwdChoice(choice, customDate = null) {
  130 |         if (choice === 'SYSTEM') {
  131 |             await this.systemCalculatedLwdRadio.click();
  132 |         } else {
  133 |             await this.chooseAnotherDateRadio.click();
  134 |             if (customDate) {
  135 |                 await this.chooseAnotherDateInput.fill(customDate);
  136 |             }
  137 |         }
  138 |     }
  139 | 
  140 |     /**
  141 |      * Toggles Ok to rehire checkbox.
  142 |      * @param {boolean} checked
  143 |      */
  144 |     async setOkToRehire(checked) {
  145 |         logger.info(`Setting Ok to Rehire to: ${checked}`);
  146 |         const isChecked = await this.eligibleForRehireCheckbox.isChecked();
  147 |         if (isChecked !== checked) {
  148 |             await this.eligibleForRehireCheckbox.click();
  149 |         }
  150 |     }
  151 | 
  152 |     /**
  153 |      * Cancels the modal.
  154 |      */
  155 |     async cancel() {
  156 |         logger.info('Canceling review modal');
  157 |         await this.cancelButton.click();
  158 |         await expect(this.dialog).toBeHidden({ timeout: 5000 });
  159 |     }
  160 | }
  161 | 
  162 | module.exports = ReviewExitModal;
  163 | 
```