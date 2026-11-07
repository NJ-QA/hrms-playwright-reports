# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: admin/organization/tenantDepartments.spec.js >> PIN-167: Internal App tenant Department setup >> PIN_167_05: prevent deleting a department after assigning an employee to it
- Location: tests/admin/organization/tenantDepartments.spec.js:119:3

# Error details

```
Error: No configured option is available for legalEntity
```

# Page snapshot

```yaml
- generic [ref=e1]:
  - generic [ref=e3]:
    - generic [ref=e4]:
      - generic [ref=e5]:
        - heading "HRMS Internal" [level=2] [ref=e7]
        - button [ref=e8] [cursor=pointer]:
          - img [ref=e9]
      - navigation [ref=e10]:
        - link "Dashboard" [ref=e11] [cursor=pointer]:
          - /url: /
          - generic [ref=e12]:
            - img [ref=e13]
            - generic [ref=e16]: Dashboard
        - button "Lead Management" [ref=e18] [cursor=pointer]:
          - generic [ref=e19]:
            - img [ref=e20]
            - generic [ref=e23]: Lead Management
          - img [ref=e25]
        - button "Organization" [ref=e28] [cursor=pointer]:
          - generic [ref=e29]:
            - img [ref=e30]
            - generic [ref=e33]: Organization
          - img [ref=e35]
        - button "Analytics & Reports" [ref=e38] [cursor=pointer]:
          - generic [ref=e39]:
            - img [ref=e40]
            - generic [ref=e41]: Analytics & Reports
          - img [ref=e43]
        - button "Team Management" [ref=e46] [cursor=pointer]:
          - generic [ref=e47]:
            - img [ref=e48]
            - generic [ref=e53]: Team Management
          - img [ref=e55]
        - button "Time Tracking" [ref=e58] [cursor=pointer]:
          - generic [ref=e59]:
            - img [ref=e60]
            - generic [ref=e63]: Time Tracking
          - img [ref=e65]
        - button "Settings" [ref=e68] [cursor=pointer]:
          - generic [ref=e69]:
            - img [ref=e70]
            - generic [ref=e73]: Settings
          - img [ref=e75]
    - generic [ref=e77]:
      - navigation "Main Navigation" [ref=e78]:
        - heading "Organization" [level=1] [ref=e81]
        - generic [ref=e83]:
          - img [ref=e84]
          - textbox "Search resources..." [ref=e87]
        - generic [ref=e88]:
          - generic [ref=e89]:
            - button "Actions" [ref=e91] [cursor=pointer]:
              - img [ref=e92]
              - generic [ref=e93]: Actions
            - button "Recent Activity" [ref=e94] [cursor=pointer]:
              - img [ref=e95]
            - button "3 Notifications" [ref=e98] [cursor=pointer]:
              - img [ref=e99]
              - generic [ref=e102]: "3"
          - button "B" [ref=e105] [cursor=pointer]:
            - generic "Bhanwar Rathore" [ref=e106]:
              - generic [ref=e107]: B
            - img [ref=e108]
      - generic [ref=e113]:
        - generic [ref=e114]:
          - generic [ref=e115]:
            - heading "AutoOrg1794019590860 Active" [level=1] [ref=e116]:
              - text: AutoOrg1794019590860
              - generic [ref=e117]:
                - img [ref=e118]
                - text: Active
            - generic [ref=e121]:
              - img [ref=e122]
              - text: auto1794019590860.hrms.modulobytes.com
          - button "Back to Clients" [ref=e126] [cursor=pointer]:
            - img [ref=e127]
            - text: Back to Clients
        - generic [ref=e129]:
          - generic [ref=e130]:
            - img [ref=e132]
            - generic [ref=e135]:
              - generic [ref=e136]: Email
              - generic [ref=e137]: org.1794019590860@yopmail.com
          - generic [ref=e138]:
            - img [ref=e140]
            - generic [ref=e142]:
              - generic [ref=e143]: Joined Date
              - generic [ref=e144]: 11/7/2026
          - generic [ref=e145]:
            - img [ref=e147]
            - generic [ref=e150]:
              - generic [ref=e151]: Created By
              - generic [ref=e152]: Bhanwar Rathore
          - generic [ref=e153]:
            - img [ref=e155]
            - generic [ref=e160]:
              - generic [ref=e161]: Total Employees
              - generic [ref=e162]: "1"
        - generic [ref=e163]:
          - navigation [ref=e164]:
            - generic [ref=e165]:
              - tab "Overview" [ref=e166] [cursor=pointer]:
                - img [ref=e167]
                - generic [ref=e169]: Overview
              - tab "Set Up" [ref=e170] [cursor=pointer]:
                - img [ref=e171]
                - generic [ref=e174]: Set Up
              - tab "Subscription" [ref=e175] [cursor=pointer]:
                - img [ref=e176]
                - generic [ref=e179]: Subscription
              - tab "Tasks" [ref=e180] [cursor=pointer]:
                - img [ref=e181]
                - generic [ref=e184]: Tasks
              - tab "Workforce" [selected] [ref=e185] [cursor=pointer]:
                - img [ref=e186]
                - generic [ref=e191]: Workforce
              - tab "Marketing" [ref=e192] [cursor=pointer]:
                - img [ref=e193]
                - generic [ref=e196]: Marketing
              - tab "Support" [ref=e197] [cursor=pointer]:
                - img [ref=e198]
                - generic [ref=e201]: Support
              - tab "Activity" [ref=e202] [cursor=pointer]:
                - img [ref=e203]
                - generic [ref=e206]: Activity
              - tab "Lead History" [ref=e207] [cursor=pointer]:
                - img [ref=e208]
                - generic [ref=e211]: Lead History
              - tab "Onboarding Details" [ref=e212] [cursor=pointer]:
                - img [ref=e213]
                - generic [ref=e216]: Onboarding Details
              - tab "Email Communication" [ref=e217] [cursor=pointer]:
                - img [ref=e218]
                - generic [ref=e221]: Email Communication
              - tab "Settings" [ref=e222] [cursor=pointer]:
                - img [ref=e223]
                - generic [ref=e226]: Settings
          - tabpanel [ref=e227]:
            - generic [ref=e229]:
              - navigation [ref=e230]:
                - generic [ref=e231]:
                  - tab "Employees" [selected] [ref=e232] [cursor=pointer]:
                    - generic [ref=e233]: Employees
                  - tab "Designations" [ref=e234] [cursor=pointer]:
                    - generic [ref=e235]: Designations
              - tabpanel [ref=e236]:
                - generic [ref=e237]:
                  - generic [ref=e239]:
                    - heading "Employees" [level=3] [ref=e240]
                    - paragraph [ref=e241]: 1 Active Employees
                  - generic [ref=e243]:
                    - generic [ref=e244]:
                      - generic [ref=e245]: Search by Name
                      - textbox "Search employees..." [ref=e246]
                    - generic [ref=e247]:
                      - generic [ref=e248]: Status
                      - combobox [ref=e249]:
                        - option "All" [selected]
                        - option "Active"
                        - option "Inactive"
                    - generic [ref=e250]:
                      - generic [ref=e251]: Email Status
                      - combobox [ref=e252]:
                        - option "All" [selected]
                        - option "Registered"
                        - option "Invited"
                        - option "Not Invited"
                        - option "Verification Pending"
                    - button "Sort Options" [ref=e254] [cursor=pointer]:
                      - img [ref=e255]
                      - text: Sort Options
                    - generic [ref=e259]:
                      - button "Bulk Employee" [ref=e260] [cursor=pointer]:
                        - img [ref=e261]
                        - text: Bulk Employee
                      - button "Add Employee" [ref=e264] [cursor=pointer]:
                        - img [ref=e265]
                        - text: Add Employee
                  - generic [ref=e269]:
                    - table [ref=e271]:
                      - rowgroup [ref=e272]:
                        - row "Name Contact Designation Roles Departments Status Joined Date Action" [ref=e273]:
                          - columnheader "Name" [ref=e274]
                          - columnheader "Contact" [ref=e275]
                          - columnheader "Designation" [ref=e276]
                          - columnheader "Roles" [ref=e277]
                          - columnheader "Departments" [ref=e278]
                          - columnheader "Status" [ref=e279]
                          - columnheader "Joined Date" [ref=e280]
                          - columnheader "Action" [ref=e281]
                      - rowgroup [ref=e282]:
                        - row "A Admin User EMP-0001 admin.1794019590860@yopmail.com +91 9819590860 N/A EMPLOYEE ADMIN N/A ACTIVE Registered 11/7/2026" [ref=e283]:
                          - cell "A Admin User EMP-0001" [ref=e284]:
                            - generic [ref=e285]:
                              - generic "Admin" [ref=e287]:
                                - generic [ref=e288]: A
                              - generic [ref=e289]:
                                - generic [ref=e292]: Admin User
                                - generic [ref=e293]: EMP-0001
                          - cell "admin.1794019590860@yopmail.com +91 9819590860" [ref=e294]:
                            - generic [ref=e295]:
                              - generic [ref=e296]:
                                - img [ref=e297]
                                - text: admin.1794019590860@yopmail.com
                              - generic [ref=e300]:
                                - img [ref=e301]
                                - text: +91 9819590860
                          - cell "N/A" [ref=e303]:
                            - generic [ref=e305]: N/A
                          - cell "EMPLOYEE ADMIN" [ref=e306]:
                            - generic [ref=e307]:
                              - generic [ref=e308]: EMPLOYEE
                              - generic [ref=e310]: ADMIN
                          - cell "N/A" [ref=e311]
                          - cell "ACTIVE Registered" [ref=e312]:
                            - generic [ref=e313]:
                              - generic [ref=e314]: ACTIVE
                              - generic [ref=e315]: Registered
                          - cell "11/7/2026" [ref=e316]
                          - cell [ref=e317]:
                            - img [ref=e320] [cursor=pointer]
                    - generic [ref=e324]:
                      - generic [ref=e325]:
                        - generic [ref=e326]: Showing 1 to 1 of 1 entries
                        - generic [ref=e327]:
                          - generic [ref=e328]: "Rows per page:"
                          - combobox [ref=e329] [cursor=pointer]:
                            - option "10" [selected]
                            - option "20"
                            - option "50"
                            - option "100"
                      - list [ref=e330]:
                        - listitem [ref=e331]:
                          - generic:
                            - text: «
                            - generic: First
                        - listitem [ref=e332]:
                          - generic:
                            - text: ‹
                            - generic: Previous
                        - listitem [ref=e333]:
                          - generic [ref=e334]:
                            - text: "1"
                            - generic [ref=e335]: (current)
                        - listitem [ref=e336]:
                          - generic:
                            - text: ›
                            - generic: Next
                        - listitem [ref=e337]:
                          - generic:
                            - text: »
                            - generic: Last
  - dialog [ref=e339]:
    - generic [ref=e340]:
      - generic [ref=e341]:
        - generic [ref=e343]:
          - img [ref=e344]
          - text: Add Employee to AutoOrg1794019590860
        - generic [ref=e347]:
          - button "Back" [ref=e348] [cursor=pointer]:
            - img [ref=e349]
            - text: Back
          - button "Continue" [ref=e351] [cursor=pointer]:
            - text: Continue
            - img [ref=e352]
          - button "Close" [ref=e354] [cursor=pointer]
      - generic [ref=e355]:
        - generic [ref=e356]:
          - generic [ref=e357]:
            - img [ref=e359]
            - generic [ref=e362]: Personal Details
          - generic [ref=e364]:
            - img [ref=e366]
            - generic [ref=e369]: Job Details
          - generic [ref=e371]:
            - img [ref=e373]
            - generic [ref=e377]: Profile Details
          - generic [ref=e379]:
            - img [ref=e381]
            - generic [ref=e383]: Compensation Details
        - generic [ref=e385]:
          - generic [ref=e387]:
            - generic [ref=e388]:
              - text: Date of Joining
              - generic [ref=e389]: "*"
            - textbox [active] [ref=e390]: 2026-11-07
          - generic [ref=e392]:
            - generic [ref=e393]:
              - text: Designation
              - generic [ref=e394]: "*"
            - combobox [ref=e395] [cursor=pointer]
          - generic [ref=e397]:
            - generic [ref=e398]: Secondary Designation
            - textbox "Enter secondary designation" [ref=e399]
          - generic [ref=e401]:
            - generic [ref=e402]:
              - text: Employment Type
              - generic [ref=e403]: "*"
            - combobox [ref=e404] [cursor=pointer]:
              - option "Full Time"
              - option "Part Time"
          - generic [ref=e406]:
            - generic [ref=e407]:
              - text: Legal Entity
              - generic [ref=e408]: "*"
            - combobox [ref=e409] [cursor=pointer]
          - generic [ref=e411]:
            - generic [ref=e412]:
              - text: Department
              - generic [ref=e413]: "*"
            - combobox [ref=e414] [cursor=pointer]:
              - option "Dobcy Department 1794019693948 Updated"
              - option "Dobcy Department 1794019746594 Updated"
          - generic [ref=e416]:
            - generic [ref=e417]:
              - text: Location
              - generic [ref=e418]: "*"
            - combobox [ref=e419] [cursor=pointer]
          - generic [ref=e421]:
            - generic [ref=e422]:
              - text: Probation Policy
              - generic [ref=e423]: "*"
            - combobox [ref=e424] [cursor=pointer]:
              - option "Standard Probation" [selected]
          - generic [ref=e426]:
            - generic [ref=e427]:
              - text: Employee Notice Period
              - generic [ref=e428]: "*"
            - combobox [ref=e429] [cursor=pointer]:
              - option "90 Days" [selected]
              - option "45 Days"
              - option "15 Days"
              - option "60 Days"
              - option "30 Days"
          - generic [ref=e431]:
            - generic [ref=e432]: Worker Type
            - combobox [ref=e433] [cursor=pointer]:
              - option "PERMANENT" [selected]
              - option "FREELANCER"
              - option "CONSULTANT"
              - option "CONTRACTOR"
```

# Test source

```ts
  98  |     async fillJobDetails(jobDetails = {}) {
  99  |         logger.info('AdminAddEmployeeModal → Filling Step 2: Job Details');
  100 |         const defaults = {
  101 |             dateOfJoining: '2026-04-01',
  102 |             designation: '52', // QA Engineer II
  103 |             employmentType: 'FULL_TIME',
  104 |             legalEntity: '6390ca1d-3c31-470e-b8a8-be425f502707',
  105 |             department: '4d3fb4ac-f986-4d01-badf-c578c1761836',
  106 |             location: 'f8ca4655-2563-4106-9714-e84607e3598f',
  107 |             probationPolicy: '170',
  108 |             noticePeriod: '489',
  109 |             workerType: '1242'
  110 |         };
  111 | 
  112 |         const config = { ...defaults, ...jobDetails };
  113 | 
  114 |         if (config.dateOfJoining) await this.dateOfJoiningInput.fill(config.dateOfJoining);
  115 |         for (const [select, val] of [
  116 |             [this.designationSelect, config.designation],
  117 |             [this.employmentTypeSelect, config.employmentType],
  118 |             [this.legalEntitySelect, config.legalEntity],
  119 |             [this.departmentSelect, config.department],
  120 |             [this.locationSelect, config.location],
  121 |             [this.probationPolicySelect, config.probationPolicy],
  122 |             [this.noticePeriodSelect, config.noticePeriod],
  123 |             [this.workerTypeSelect, config.workerType]
  124 |         ]) {
  125 |             if (!select) continue;
  126 |             try {
  127 |                 if (val) await select.selectOption(val, { timeout: 2000 });
  128 |                 else await this.selectFirstConfiguredOption(select, true).catch(() => {});
  129 |             } catch {
  130 |                 await this.selectFirstConfiguredOption(select, true).catch(() => {});
  131 |             }
  132 |         }
  133 | 
  134 |         await this.continueButton.click();
  135 |         await this.page.waitForTimeout(2_500);
  136 |         return this;
  137 |     }
  138 | 
  139 |     /** Fills required tenant-specific organization fields without using IDs from another tenant. */
  140 |     async fillJobDetailsForTenant({ legalEntity, department, location, designation }) {
  141 |         await expect(this.dateOfJoiningInput).toBeVisible();
  142 |         await this.dateOfJoiningInput.fill(new Date().toISOString().slice(0, 10));
  143 |         for (const [select, value] of [
  144 |             [this.legalEntitySelect, legalEntity],
  145 |             [this.departmentSelect, department],
  146 |             [this.locationSelect, location]
  147 |         ]) {
  148 |             if (value) await this.selectOptionByText(select, value);
  149 |             else await this.selectFirstConfiguredOption(select);
  150 |         }
  151 | 
  152 |         if (designation) {
  153 |             await this.selectOptionByText(this.designationSelect, designation);
  154 |         } else {
  155 |             await this.selectFirstConfiguredOption(this.designationSelect);
  156 |         }
  157 |         for (const select of [this.employmentTypeSelect, this.workerTypeSelect]) {
  158 |             await this.selectFirstConfiguredOption(select);
  159 |         }
  160 |         for (const select of [this.probationPolicySelect, this.noticePeriodSelect]) {
  161 |             await this.selectFirstConfiguredOption(select, { optional: true });
  162 |         }
  163 | 
  164 |         await this.continueButton.click();
  165 |         await expect(this.activeStepLabel.filter({ hasText: /Profile Details/i })).toBeVisible({ timeout: 15_000 });
  166 |         return this;
  167 |     }
  168 | 
  169 |     async selectOptionByText(select, text) {
  170 |         const matchingOptions = select.locator('option').filter({ hasText: text });
  171 |         await expect(matchingOptions, `A dropdown option containing "${text}" should exist`).toHaveCount(1);
  172 |         const value = await matchingOptions.getAttribute('value');
  173 |         await select.selectOption(value);
  174 |     }
  175 | 
  176 |     async selectFirstConfiguredOption(select, { optional = false } = {}) {
  177 |         if (optional && !(await select.isVisible().catch(() => false))) return;
  178 |         await expect(select).toBeVisible();
  179 | 
  180 |         let optionIndex = -1;
  181 |         try {
  182 |             await expect.poll(async () => {
  183 |                 const idx = await select.locator('option').evaluateAll(options => options.findIndex(option =>
  184 |                     Boolean(option.value) && !option.disabled && !/^(select|choose|please select)/i.test(option.textContent.trim())
  185 |                 )).catch(() => -1);
  186 |                 return idx;
  187 |             }, { timeout: 10_000, intervals: [250, 500, 1000] }).toBeGreaterThanOrEqual(0);
  188 | 
  189 |             optionIndex = await select.locator('option').evaluateAll(options => options.findIndex(option =>
  190 |                 Boolean(option.value) && !option.disabled && !/^(select|choose|please select)/i.test(option.textContent.trim())
  191 |             ));
  192 |         } catch {
  193 |             optionIndex = -1;
  194 |         }
  195 | 
  196 |         if (optionIndex < 0) {
  197 |             if (optional) return;
> 198 |             throw new Error(`No configured option is available for ${await select.getAttribute('id') || 'required job field'}`);
      |                   ^ Error: No configured option is available for legalEntity
  199 |         }
  200 |         await select.selectOption({ index: optionIndex });
  201 |     }
  202 | 
  203 |     // =========================================================================
  204 |     // Step 3: Profile Details
  205 |     // =========================================================================
  206 | 
  207 |     /**
  208 |      * Verifies that Step 3 (Profile Details) is active.
  209 |      */
  210 |     async verifyProfileDetailsStepActive() {
  211 |         const stepLabel = this.activeStepLabel.filter({ hasText: /Profile Details/i });
  212 |         await expect(stepLabel).toBeVisible({ timeout: 15_000 });
  213 |         logger.info('AdminAddEmployeeModal → Step 3 Profile Details step is active');
  214 |     }
  215 | 
  216 |     /**
  217 |      * Enables or disables the onboarding invitation checkbox on Step 3.
  218 |      * @param {boolean} enabled
  219 |      */
  220 |     async setInviteEmployee(enabled = true) {
  221 |         await expect(this.inviteEmployeeCheckbox).toBeVisible();
  222 |         await this.inviteEmployeeCheckbox.setChecked(enabled);
  223 |         await expect(this.inviteEmployeeCheckbox).toHaveJSProperty('checked', enabled);
  224 |         return this;
  225 |     }
  226 | 
  227 |     /**
  228 |      * Selects time tracking policy on Step 3.
  229 |      * @param {string} policyId
  230 |      */
  231 |     async selectTimeTrackingPolicy(policyId = 'cb5455ea-9175-11f1-a1da-3ae8d4b81bd1') {
  232 |         logger.info(`AdminAddEmployeeModal → Selecting Time Tracking Policy: ${policyId}`);
  233 |         await this.timeTrackingPolicySelect.selectOption(policyId);
  234 |         return this;
  235 |     }
  236 | 
  237 |     /**
  238 |      * Verifies that Expenses section heading & Expense Policy select dropdown are visible.
  239 |      */
  240 |     async verifyExpensesSectionVisible() {
  241 |         await expect(this.expensesHeading).toBeVisible({ timeout: 10_000 });
  242 |         await expect(this.expensePolicySelect).toBeVisible({ timeout: 10_000 });
  243 |         logger.info('AdminAddEmployeeModal → Expenses section heading & Expense Policy dropdown visible');
  244 |     }
  245 | 
  246 |     /**
  247 |      * Returns count of options available in Expense Policy select dropdown.
  248 |      * @returns {Promise<number>}
  249 |      */
  250 |     async getExpensePolicyOptionsCount() {
  251 |         return await this.expensePolicySelect.locator('option').count();
  252 |     }
  253 | 
  254 |     /**
  255 |      * Verifies if Expense Policy is optional (not marked with required attribute).
  256 |      * @returns {Promise<boolean>}
  257 |      */
  258 |     async isExpensePolicyOptional() {
  259 |         const requiredAttr = await this.expensePolicySelect.getAttribute('required');
  260 |         return requiredAttr === null;
  261 |     }
  262 | 
  263 |     /**
  264 |      * Selects an Expense Policy by label or value.
  265 |      * @param {string} policyName
  266 |      * @returns {Promise<string>} Selected value
  267 |      */
  268 |     async selectExpensePolicy(policyName) {
  269 |         logger.info(`AdminAddEmployeeModal → Selecting Expense Policy: "${policyName}"`);
  270 |         await this.expensePolicySelect.selectOption({ label: policyName });
  271 |         const selectedValue = await this.expensePolicySelect.inputValue();
  272 |         return selectedValue;
  273 |     }
  274 | 
  275 |     // =========================================================================
  276 |     // Submission & Dialog Dismissal
  277 |     // =========================================================================
  278 | 
  279 |     /**
  280 |      * Clicks Continue/Save on Step 3 to submit employee creation and captures the API response.
  281 |      * Returns the parsed response containing employeeId and employeeCode.
  282 |      * @returns {Promise<{ employeeId: string, employeeCode: string, [key: string]: any }>}
  283 |      */
  284 |     async submitAndCaptureEmployee() {
  285 |         logger.info('AdminAddEmployeeModal → Submitting employee creation (Step 3 Continue)');
  286 |         const submitBtn = this.modal.getByRole('button', { name: /Continue|Save|Submit|Create/i }).first();
  287 |         await expect(submitBtn).toBeVisible({ timeout: 10_000 });
  288 |         await expect(submitBtn).toBeEnabled({ timeout: 10_000 });
  289 | 
  290 |         const [empCreateRes] = await Promise.all([
  291 |             this.page.waitForResponse(
  292 |                 res => res.url().includes('/employee') && res.request().method() === 'POST',
  293 |                 { timeout: 30_000 }
  294 |             ),
  295 |             submitBtn.click()
  296 |         ]);
  297 | 
  298 |         if (!empCreateRes.ok()) {
```