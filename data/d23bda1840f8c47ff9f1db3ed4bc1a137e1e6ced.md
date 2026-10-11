# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: organization/documents/documentGenerationTemplateFinalize.spec.js >> PIN-307: Document Generation Template – Part 3 (Finalize) >> PIN_307_05-10: View and Download dependencies and bulk selectors stay consistent
- Location: tests/organization/documents/documentGenerationTemplateFinalize.spec.js:132:5

# Error details

```
Error: expect(locator).toBeAttached() failed

Locator: locator('.MuiDrawer-paper, body').locator('input[role="switch"], input[type="checkbox"]').last()
Expected: attached
Timeout: 10000ms
Error: element(s) not found

Call log:
  - Expect "toBeAttached" with timeout 10000ms
  - waiting for locator('.MuiDrawer-paper, body').locator('input[role="switch"], input[type="checkbox"]').last()

```

# Page snapshot

```yaml
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
        - button "Messages 10" [ref=e32] [cursor=pointer]:
          - img [ref=e34]
          - generic [ref=e36]:
            - generic [ref=e37]: Messages
            - generic [ref=e38]: "10"
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
          - button [ref=e159] [cursor=pointer]:
            - img [ref=e160]
        - generic "Global Settings" [ref=e162]:
          - button [ref=e163] [cursor=pointer]:
            - img [ref=e164]
        - button "EN" [ref=e167] [cursor=pointer]:
          - img [ref=e169]
          - generic [ref=e176]: EN
          - img [ref=e177]
        - generic [ref=e180] [cursor=pointer]:
          - img "profile" [ref=e182]
          - generic [ref=e183]:
            - generic [ref=e184]: Neeraj
            - generic [ref=e185]: xperts_imaging@yopmail.com
    - generic [ref=e187]:
      - generic [ref=e188]:
        - tablist [ref=e189]:
          - tab "Dashboard" [ref=e190] [cursor=pointer]:
            - generic [ref=e191]: Dashboard
          - tab "Employee Management" [ref=e192] [cursor=pointer]:
            - generic [ref=e193]: Employee Management
          - tab "Organization Structure" [ref=e194] [cursor=pointer]:
            - generic [ref=e195]: Organization Structure
          - tab "Onboarding" [ref=e196] [cursor=pointer]:
            - generic [ref=e197]: Onboarding
          - tab "Exit" [ref=e198] [cursor=pointer]:
            - generic [ref=e199]: Exit
          - tab "Hiring" [ref=e200] [cursor=pointer]:
            - generic [ref=e201]: Hiring
          - tab "Documents" [selected] [ref=e202] [cursor=pointer]:
            - generic [ref=e203]: Documents
          - tab "Expenses & Travel" [ref=e204] [cursor=pointer]:
            - generic [ref=e205]: Expenses & Travel
          - tab "Settings" [ref=e206] [cursor=pointer]:
            - generic [ref=e207]: Settings
        - separator [ref=e208]
      - generic [ref=e210]:
        - tablist [ref=e211]:
          - tab "Employee Documents" [ref=e212] [cursor=pointer]:
            - generic [ref=e213]: Employee Documents
          - tab "Document Templates" [selected] [ref=e214] [cursor=pointer]:
            - generic [ref=e215]: Document Templates
          - tab "Organization Documents" [ref=e216] [cursor=pointer]:
            - generic [ref=e217]: Organization Documents
        - tabpanel [ref=e218]:
          - generic [ref=e220]:
            - generic [ref=e221]:
              - generic [ref=e222]:
                - heading "Document templates" [level=6] [ref=e223]
                - paragraph [ref=e224]: Generate agreements, employee letters or compliance forms and send for signature/upload/acknowledgement.
              - button "Create template" [ref=e226] [cursor=pointer]:
                - img [ref=e227]
                - text: Create template
                - img [ref=e228]
            - generic [ref=e230]:
              - generic [ref=e232]:
                - combobox [ref=e233] [cursor=pointer]: All
                - textbox: ALL
                - img
                - group
              - generic [ref=e235]:
                - combobox [ref=e236] [cursor=pointer]: All
                - textbox: ALL
                - img
                - group
              - generic [ref=e239]:
                - img [ref=e241]
                - textbox "Search" [ref=e244]
                - group
            - table "Data table" [ref=e248]:
              - rowgroup [ref=e249]:
                - row "DOCUMENT NAME WORKFLOW ENABLED Action Type LAST USED ACTIONS Filter ACTIONS" [ref=e250]:
                  - columnheader "DOCUMENT NAME" [ref=e251]:
                    - generic [ref=e253]: DOCUMENT NAME
                  - columnheader "WORKFLOW ENABLED" [ref=e254]:
                    - generic [ref=e256]: WORKFLOW ENABLED
                  - columnheader "Action Type" [ref=e257]:
                    - generic [ref=e259]: Action Type
                  - columnheader "LAST USED" [ref=e260]:
                    - generic [ref=e262]: LAST USED
                  - columnheader "ACTIONS Filter ACTIONS" [ref=e263]:
                    - generic [ref=e265]:
                      - text: ACTIONS
                      - button "Filter ACTIONS" [ref=e266] [cursor=pointer]:
                        - img [ref=e267]
              - rowgroup [ref=e269]:
                - row "QA_Finalize_Template_1791365145856 PIN-307 Finalize step verification. No Document Generation Not Generated Generate" [ref=e270]:
                  - cell "QA_Finalize_Template_1791365145856 PIN-307 Finalize step verification." [ref=e271]:
                    - generic [ref=e272] [cursor=pointer]:
                      - img [ref=e274]
                      - generic [ref=e277]:
                        - heading "QA_Finalize_Template_1791365145856" [level=6] [ref=e279]
                        - generic [ref=e280]: PIN-307 Finalize step verification.
                  - cell "No" [ref=e281]
                  - cell "Document Generation" [ref=e282]:
                    - generic [ref=e283]:
                      - img [ref=e284]
                      - generic [ref=e287]: Document Generation
                  - cell "Not Generated" [ref=e288]
                  - cell "Generate" [ref=e289]:
                    - generic [ref=e290]:
                      - button "Generate" [ref=e291] [cursor=pointer]:
                        - img [ref=e292]
                        - text: Generate
                      - button [ref=e295] [cursor=pointer]:
                        - img [ref=e296]
                - row "QA_Finalize_Template_1791363923345 PIN-307 Finalize step verification. No Document Generation Not Generated Generate" [ref=e298]:
                  - cell "QA_Finalize_Template_1791363923345 PIN-307 Finalize step verification." [ref=e299]:
                    - generic [ref=e300] [cursor=pointer]:
                      - img [ref=e302]
                      - generic [ref=e305]:
                        - heading "QA_Finalize_Template_1791363923345" [level=6] [ref=e307]
                        - generic [ref=e308]: PIN-307 Finalize step verification.
                  - cell "No" [ref=e309]
                  - cell "Document Generation" [ref=e310]:
                    - generic [ref=e311]:
                      - img [ref=e312]
                      - generic [ref=e315]: Document Generation
                  - cell "Not Generated" [ref=e316]
                  - cell "Generate" [ref=e317]:
                    - generic [ref=e318]:
                      - button "Generate" [ref=e319] [cursor=pointer]:
                        - img [ref=e320]
                        - text: Generate
                      - button [ref=e323] [cursor=pointer]:
                        - img [ref=e324]
                - row "testmanual No Document Generation Not Generated Generate" [ref=e326]:
                  - cell "testmanual" [ref=e327]:
                    - generic [ref=e328] [cursor=pointer]:
                      - img [ref=e330]
                      - heading "testmanual" [level=6] [ref=e335]
                  - cell "No" [ref=e336]
                  - cell "Document Generation" [ref=e337]:
                    - generic [ref=e338]:
                      - img [ref=e339]
                      - generic [ref=e342]: Document Generation
                  - cell "Not Generated" [ref=e343]
                  - cell "Generate" [ref=e344]:
                    - generic [ref=e345]:
                      - button "Generate" [ref=e346] [cursor=pointer]:
                        - img [ref=e347]
                        - text: Generate
                      - button [ref=e350] [cursor=pointer]:
                        - img [ref=e351]
                - row "QA_Finalize_Template_1791355255347 PIN-307 Finalize step verification. No Document Generation Not Generated Generate" [ref=e353]:
                  - cell "QA_Finalize_Template_1791355255347 PIN-307 Finalize step verification." [ref=e354]:
                    - generic [ref=e355] [cursor=pointer]:
                      - img [ref=e357]
                      - generic [ref=e360]:
                        - heading "QA_Finalize_Template_1791355255347" [level=6] [ref=e362]
                        - generic [ref=e363]: PIN-307 Finalize step verification.
                  - cell "No" [ref=e364]
                  - cell "Document Generation" [ref=e365]:
                    - generic [ref=e366]:
                      - img [ref=e367]
                      - generic [ref=e370]: Document Generation
                  - cell "Not Generated" [ref=e371]
                  - cell "Generate" [ref=e372]:
                    - generic [ref=e373]:
                      - button "Generate" [ref=e374] [cursor=pointer]:
                        - img [ref=e375]
                        - text: Generate
                      - button [ref=e378] [cursor=pointer]:
                        - img [ref=e379]
  - generic [ref=e381]:
    - generic [ref=e382]:
      - heading "Theme & Style" [level=6] [ref=e383]
      - img [ref=e384] [cursor=pointer]
    - generic [ref=e386]:
      - generic [ref=e387]:
        - heading "Theme Mode" [level=6] [ref=e388]:
          - img [ref=e389]
          - text: Theme Mode
        - generic [ref=e391]:
          - button "Light" [ref=e392] [cursor=pointer]:
            - img [ref=e393]
            - text: Light
          - button "Dark" [ref=e395] [cursor=pointer]:
            - img [ref=e396]
            - text: Dark
          - button "Auto" [ref=e398] [cursor=pointer]:
            - img [ref=e399]
            - text: Auto
      - generic [ref=e401]:
        - heading "Theme Color" [level=6] [ref=e402]:
          - img [ref=e403]
          - text: Theme Color
        - generic [ref=e405]:
          - generic "Default" [ref=e406] [cursor=pointer]
          - generic "Orange" [ref=e408] [cursor=pointer]
          - generic "Marun" [ref=e410] [cursor=pointer]
          - generic "Blue" [ref=e412] [cursor=pointer]
          - generic "Green" [ref=e414] [cursor=pointer]
          - generic "Gray" [ref=e416] [cursor=pointer]
      - generic [ref=e418]:
        - heading "Dashboard Layout" [level=6] [ref=e419]
        - generic [ref=e420]:
          - button "Default" [ref=e421] [cursor=pointer]:
            - img [ref=e422]
            - text: Default
          - button "New Layout" [ref=e424] [cursor=pointer]:
            - img [ref=e425]
            - text: New Layout
  - generic [ref=e427]:
    - generic [ref=e428]:
      - heading "Change Password" [level=6] [ref=e429]
      - img [ref=e430] [cursor=pointer]
    - generic [ref=e432]:
      - generic [ref=e433]:
        - text: "You are currently logged in as:"
        - strong [ref=e434]: xperts_imaging@yopmail.com
        - generic [ref=e435]: Please enter your current password to verify your identity, then create a strong new password to keep your account secure.
      - alert [ref=e436]:
        - img [ref=e438]
        - generic [ref=e441]:
          - strong [ref=e442]: Security Notice
          - generic [ref=e443]: For your safety, you will be automatically logged out after a successful password change.
      - generic [ref=e444]:
        - generic [ref=e446]:
          - generic [ref=e447]:
            - generic [ref=e449]:
              - text: Old Password
              - generic [ref=e450]: "*"
            - textbox "Enter your current password" [ref=e452]
          - img [ref=e454] [cursor=pointer]
        - generic [ref=e457]:
          - generic [ref=e458]:
            - generic [ref=e460]:
              - text: New Password
              - generic [ref=e461]: "*"
            - textbox "Create a strong new password" [ref=e463]
          - img [ref=e465] [cursor=pointer]
        - generic [ref=e468]:
          - generic [ref=e469]:
            - generic [ref=e471]:
              - text: Confirm Password
              - generic [ref=e472]: "*"
            - textbox "Re-enter your new password" [disabled] [ref=e474]
          - img [ref=e476]
        - button "Update Password" [ref=e478] [cursor=pointer]
```

# Test source

```ts
  41  |         // Approver needed toggle (Switch index 1 when allowEmployeeGeneration is true)
  42  |         this.approverNeededGroup = page.locator('text=/Approver needed/i').first();
  43  |         this.approverNeededSwitch = page.locator('.MuiDrawer-paper, body').locator('input[role="switch"], input[type="checkbox"]').nth(1);
  44  | 
  45  |         // Require document workflow toggle (Last switch)
  46  |         this.requireWorkflowGroup = page.locator('text=/Require document workflow/i').first();
  47  |         this.requireWorkflowSwitch = page.locator('.MuiDrawer-paper, body').locator('input[role="switch"], input[type="checkbox"]').last();
  48  | 
  49  |         // Validation error
  50  |         this.templateNameError = page.locator('.hrms-input-error, .Mui-error, [class*="error"], p, span').filter({
  51  |             hasText: /Template Name is required|Name is required/i
  52  |         }).first();
  53  | 
  54  |         // ── Workflow Step Builder Elements (When workflow enabled) ────
  55  |         this.workflowSection = page.locator('text=/SELECT APPROVER|Configure signatures, approvals/i').first();
  56  |         this.addStepButton = page.locator('.doc-template-add-step-btn, button:has-text("+ Add Step")').first();
  57  |         this.actionTypeChip = page.locator('.document-step-editor-action-type-chip, .MuiChip-root').filter({
  58  |             hasText: /APPROVAL|SIGN|ACKNOWLEDGEMENT/i
  59  |         }).first();
  60  |         this.approverSearchInput = page.locator('input[placeholder*="Search employees"]').first();
  61  |         this.instructionsInput = page.locator('input[placeholder*="instruction" i], textarea[placeholder*="instruction" i]').first();
  62  |     }
  63  | 
  64  |     /**
  65  |      * Wait for the Document Template Setup wizard to open.
  66  |      */
  67  |     async waitForOpen() {
  68  |         logger.debug('Waiting for Document Template Setup Wizard to open');
  69  |         await expect(this.modalTitle).toBeVisible({ timeout: 15_000 });
  70  |         await expect(this.templateNameInput).toBeVisible({ timeout: 10_000 });
  71  |         return this;
  72  |     }
  73  | 
  74  |     /**
  75  |      * Wait for wizard to close.
  76  |      */
  77  |     async waitForClose() {
  78  |         logger.debug('Waiting for Document Template Setup Wizard to close');
  79  |         await expect(this.modalTitle).toBeHidden({ timeout: 10_000 });
  80  |         return this;
  81  |     }
  82  | 
  83  |     /**
  84  |      * Enter template name.
  85  |      * @param {string} name
  86  |      */
  87  |     async enterTemplateName(name) {
  88  |         logger.debug(`Entering template name: ${name}`);
  89  |         await expect(this.templateNameInput).toBeVisible({ timeout: 10_000 });
  90  |         await this.templateNameInput.fill(name);
  91  |         return this;
  92  |     }
  93  | 
  94  |     /**
  95  |      * Enter template description.
  96  |      * @param {string} desc
  97  |      */
  98  |     async enterDescription(desc) {
  99  |         logger.debug(`Entering template description: ${desc}`);
  100 |         await expect(this.descriptionTextarea).toBeVisible({ timeout: 10_000 });
  101 |         await this.descriptionTextarea.fill(desc);
  102 |         return this;
  103 |     }
  104 | 
  105 |     /**
  106 |      * Set 'Allow employees to generate this document' toggle state.
  107 |      * @param {boolean} enable
  108 |      */
  109 |     async setAllowEmployeeGeneration(enable = true) {
  110 |         logger.debug(`Setting Allow Employee Generation toggle to: ${enable}`);
  111 |         await expect(this.allowEmployeeGenerationSwitch).toBeAttached({ timeout: 10_000 });
  112 |         const isChecked = await this.allowEmployeeGenerationSwitch.isChecked();
  113 |         if (isChecked !== enable) {
  114 |             await this.allowEmployeeGenerationSwitch.evaluate(node => node.click());
  115 |             await this.page.waitForTimeout(500);
  116 |         }
  117 |         return this;
  118 |     }
  119 | 
  120 |     /**
  121 |      * Set 'Approver needed' toggle state.
  122 |      * @param {boolean} enable
  123 |      */
  124 |     async setApproverNeeded(enable = true) {
  125 |         logger.debug(`Setting Approver Needed toggle to: ${enable}`);
  126 |         await expect(this.approverNeededSwitch).toBeAttached({ timeout: 10_000 });
  127 |         const isChecked = await this.approverNeededSwitch.isChecked();
  128 |         if (isChecked !== enable) {
  129 |             await this.approverNeededSwitch.evaluate(node => node.click());
  130 |             await this.page.waitForTimeout(500);
  131 |         }
  132 |         return this;
  133 |     }
  134 | 
  135 |     /**
  136 |      * Set 'Require document workflow' toggle state.
  137 |      * @param {boolean} enable
  138 |      */
  139 |     async setRequireWorkflow(enable = true) {
  140 |         logger.debug(`Setting Require Workflow toggle to: ${enable}`);
> 141 |         await expect(this.requireWorkflowSwitch).toBeAttached({ timeout: 10_000 });
      |                                                  ^ Error: expect(locator).toBeAttached() failed
  142 |         const isChecked = await this.requireWorkflowSwitch.isChecked();
  143 |         if (isChecked !== enable) {
  144 |             await this.requireWorkflowSwitch.evaluate(node => node.click());
  145 |             await this.page.waitForTimeout(500);
  146 |         }
  147 |         return this;
  148 |     }
  149 | 
  150 |     /**
  151 |      * Click Continue button.
  152 |      */
  153 |     async clickContinue() {
  154 |         logger.info('Clicking Continue in Document Template Setup');
  155 |         await expect(this.continueButton).toBeVisible({ timeout: 10_000 });
  156 |         await this.continueButton.click({ force: true });
  157 |         return this;
  158 |     }
  159 | 
  160 |     /**
  161 |      * Click Cancel button.
  162 |      */
  163 |     async clickCancel() {
  164 |         logger.info('Clicking Cancel in Document Template Setup');
  165 |         await expect(this.cancelButton).toBeVisible({ timeout: 10_000 });
  166 |         await this.cancelButton.click({ force: true });
  167 |         return this;
  168 |     }
  169 | 
  170 |     /**
  171 |      * Click Close icon button.
  172 |      */
  173 |     async clickClose() {
  174 |         logger.info('Clicking Close icon in Document Template Setup');
  175 |         await expect(this.closeButton).toBeVisible({ timeout: 10_000 });
  176 |         await this.closeButton.click({ force: true });
  177 |         return this;
  178 |     }
  179 | 
  180 |     /**
  181 |      * Fill all Step 1 details.
  182 |      * @param {{ name?: string, description?: string, allowEmployeeGeneration?: boolean, approverNeeded?: boolean, requireWorkflow?: boolean }} data
  183 |      */
  184 |     async fillStep1Details(data = {}) {
  185 |         if (data.name !== undefined) {
  186 |             await this.enterTemplateName(data.name);
  187 |         }
  188 |         if (data.description !== undefined) {
  189 |             await this.enterDescription(data.description);
  190 |         }
  191 |         if (data.allowEmployeeGeneration !== undefined) {
  192 |             await this.setAllowEmployeeGeneration(data.allowEmployeeGeneration);
  193 |         }
  194 |         if (data.approverNeeded !== undefined && data.allowEmployeeGeneration) {
  195 |             await this.setApproverNeeded(data.approverNeeded);
  196 |         }
  197 |         if (data.requireWorkflow !== undefined) {
  198 |             await this.setRequireWorkflow(data.requireWorkflow);
  199 |         }
  200 |         return this;
  201 |     }
  202 | }
  203 | 
  204 | module.exports = DocumentTemplateSetupModal;
  205 | 
```