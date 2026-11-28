# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: timeTracking/shiftAllowanceVersions.spec.js >> Shift Allowance Policy - Versions (PIN-228) >> Flow 2: Version Creation, Effective Dates & Validations (PIN-228-4, PIN-228-6, PIN-228-7, PIN-228-9, PIN-228-10, PIN-228-11, PIN-228-12)
- Location: tests/timeTracking/shiftAllowanceVersions.spec.js:102:5

# Error details

```
Error: expect(locator).toBeVisible() failed

Locator: locator('.MuiPickersLayout-root button[role="gridcell"]:not([disabled]), .MuiDateCalendar-root button[role="gridcell"]:not([disabled])').filter({ hasText: /^\s*28\s*$/ }).first()
Expected: visible
Timeout: 5000ms
Error: element(s) not found

Call log:
  - Expect "toBeVisible" with timeout 5000ms
  - waiting for locator('.MuiPickersLayout-root button[role="gridcell"]:not([disabled]), .MuiDateCalendar-root button[role="gridcell"]:not([disabled])').filter({ hasText: /^\s*28\s*$/ }).first()

```

# Page snapshot

```yaml
- generic:
  - generic [ref=e1]:
    - generic [ref=e3]:
      - generic [ref=e4]:
        - link [ref=e5] [cursor=pointer]:
          - /url: /global/setting/general
          - img [ref=e6]
          - heading [level=2] [ref=e7]: xperts
        - button [ref=e8] [cursor=pointer]:
          - img [ref=e9]
      - separator [ref=e11]
      - list [ref=e13]:
        - listitem [ref=e14]:
          - button [ref=e15] [cursor=pointer]:
            - img [ref=e17]
            - generic [ref=e20]: Home
        - listitem [ref=e21]:
          - button [ref=e22] [cursor=pointer]:
            - img [ref=e24]
            - generic [ref=e28]: Me
            - img [ref=e29]
        - listitem [ref=e31]:
          - button [ref=e32] [cursor=pointer]:
            - img [ref=e34]
            - generic [ref=e36]:
              - generic [ref=e37]: Messages
              - generic [ref=e38]: "1"
        - listitem [ref=e39]:
          - button [ref=e40] [cursor=pointer]:
            - img [ref=e42]
            - generic [ref=e45]: Organization
            - img [ref=e46]
        - listitem [ref=e48]:
          - button [ref=e49] [cursor=pointer]:
            - img [ref=e51]
            - generic [ref=e54]: Schedule
        - listitem [ref=e55]:
          - button [ref=e56] [cursor=pointer]:
            - img [ref=e58]
            - generic [ref=e61]: Projects
        - separator [ref=e62]
        - listitem [ref=e63]:
          - button [ref=e64] [cursor=pointer]:
            - img [ref=e66]
            - generic [ref=e69]: Attendance
            - img [ref=e70]
        - listitem [ref=e72]:
          - button [ref=e73] [cursor=pointer]:
            - img [ref=e75]
            - generic [ref=e78]: Time Tracking
            - img [ref=e79]
        - listitem [ref=e81]:
          - button [ref=e82] [cursor=pointer]:
            - img [ref=e84]
            - generic [ref=e87]: Hiring
            - img [ref=e88]
        - listitem [ref=e90]:
          - button [ref=e91] [cursor=pointer]:
            - img [ref=e93]
            - generic [ref=e96]: Reports
        - listitem [ref=e97]:
          - button [ref=e98] [cursor=pointer]:
            - img [ref=e100]
            - generic [ref=e103]: Communication
        - listitem [ref=e104]:
          - button [ref=e105] [cursor=pointer]:
            - img [ref=e107]
            - generic [ref=e110]: Benefits
        - listitem [ref=e111]:
          - button [ref=e112] [cursor=pointer]:
            - img [ref=e114]
            - generic [ref=e117]: Recruit
        - listitem [ref=e118]:
          - button [ref=e119] [cursor=pointer]:
            - img [ref=e121]
            - generic [ref=e125]: Candidate
        - listitem [ref=e126]:
          - button [ref=e127] [cursor=pointer]:
            - img [ref=e129]
            - generic [ref=e132]: Payment
        - listitem [ref=e133]:
          - button [ref=e134] [cursor=pointer]:
            - img [ref=e136]
            - generic [ref=e139]: Chats
    - generic [ref=e140]:
      - generic [ref=e142]:
        - generic [ref=e144]: Good Evening Auto !
        - generic [ref=e145]:
          - img [ref=e146]
          - textbox [ref=e148]:
            - /placeholder: Search employee and action (Ex., leave, exit)
        - generic [ref=e149]:
          - button [ref=e151] [cursor=pointer]:
            - img [ref=e152]
          - button [ref=e155] [cursor=pointer]:
            - img [ref=e156]
          - button [ref=e159] [cursor=pointer]:
            - generic [ref=e160]:
              - img [ref=e161]
              - generic [ref=e163]: "20"
          - button [ref=e165] [cursor=pointer]:
            - img [ref=e166]
          - button [ref=e169] [cursor=pointer]:
            - img [ref=e171]
            - generic [ref=e178]: EN
            - img [ref=e179]
          - generic [ref=e182] [cursor=pointer]:
            - img [ref=e184]
            - generic [ref=e185]:
              - generic [ref=e186]: Auto
              - generic [ref=e187]: qa.emp_b072852bd0614cf7@yopmail.com
      - generic [ref=e189]:
        - generic [ref=e190]:
          - tablist [ref=e191]:
            - tab [selected] [ref=e192] [cursor=pointer]:
              - generic [ref=e193]: Shifts/Weekly Offs & Holidays
            - tab [ref=e194] [cursor=pointer]:
              - generic [ref=e195]: Attendance Tracking
            - tab [ref=e196] [cursor=pointer]:
              - generic [ref=e197]: Leave Management
            - tab [ref=e198] [cursor=pointer]:
              - generic [ref=e199]: Settings
          - separator [ref=e200]
        - generic [ref=e202]:
          - tablist [ref=e203]:
            - tab [ref=e204] [cursor=pointer]:
              - generic [ref=e205]: Shift & Weekly Offs
            - tab [selected] [ref=e206] [cursor=pointer]:
              - generic [ref=e207]: Shift Allowance
            - tab [ref=e208] [cursor=pointer]:
              - generic [ref=e209]: Holidays
            - tab [ref=e210] [cursor=pointer]:
              - generic [ref=e211]: Assignments
          - tabpanel [ref=e212]:
            - generic [ref=e213]:
              - tablist [ref=e214]:
                - tab [selected] [ref=e215] [cursor=pointer]:
                  - generic [ref=e216]: Shift Allowance Policy
                - tab [ref=e217] [cursor=pointer]:
                  - generic [ref=e218]: Shift Allowance Code
              - separator [ref=e219]
              - tabpanel [ref=e220]:
                - generic [ref=e222]:
                  - generic [ref=e223]:
                    - generic [ref=e224]:
                      - generic [ref=e225]:
                        - img [ref=e226]
                        - paragraph [ref=e229]: Policies
                      - button [ref=e231] [cursor=pointer]:
                        - text: +Add Shift Allowance Policy
                        - img [ref=e232]
                    - generic [ref=e236]:
                      - img [ref=e238]
                      - textbox [ref=e240]:
                        - /placeholder: Search by policy name...
                        - text: VerPolicy 1795832245597
                      - group
                    - generic [ref=e242] [cursor=pointer]:
                      - generic [ref=e243]:
                        - paragraph [ref=e245]: VerPolicy 1795832245597
                        - generic [ref=e247]: 0 Employees
                      - generic:
                        - img
                  - generic [ref=e249]:
                    - generic [ref=e250]:
                      - img
                      - img:
                        - generic: 12 H
                        - generic: 06 H
                        - generic: 18 H
                        - generic: 00 H
                      - generic [ref=e251]:
                        - button [ref=e253] [cursor=pointer]:
                          - img [ref=e254]
                        - button [ref=e256] [cursor=pointer]:
                          - img [ref=e257]
                      - generic [ref=e261]:
                        - heading [level=6] [ref=e263]: VerPolicy 1795832245597
                        - generic [ref=e264]:
                          - generic [ref=e265]: "Description:"
                          - generic [ref=e266]: Updated notes
                      - generic [ref=e268]: Configured on November 28, 2026
                    - generic [ref=e270]:
                      - tablist [ref=e271]:
                        - tab [ref=e272] [cursor=pointer]:
                          - generic [ref=e273]: Summary
                        - tab [ref=e274] [cursor=pointer]:
                          - generic [ref=e275]: Employees (0)
                        - tab [selected] [ref=e276] [cursor=pointer]:
                          - generic [ref=e277]: Track Shift Allowance Versions
                      - separator [ref=e278]
                      - tabpanel [ref=e279]:
                        - generic [ref=e280]:
                          - heading [level=6] [ref=e282]: History of changes
                          - separator [ref=e283]
                          - generic [ref=e286]:
                            - paragraph [ref=e289]: 28/11/2026 - Current
                            - generic [ref=e290]:
                              - paragraph [ref=e291]: Updated by
                              - generic [ref=e292]: AL
                              - paragraph [ref=e293]: Auto lahcifclnagbemph on 28/11/2026
                            - generic [ref=e294]:
                              - button [ref=e295] [cursor=pointer]:
                                - img [ref=e296]
                              - button [ref=e298] [cursor=pointer]:
                                - img [ref=e299]
                              - generic [ref=e301]:
                                - button [disabled]:
                                  - img
    - generic [ref=e302]:
      - generic [ref=e303]:
        - heading [level=6] [ref=e304]: Theme & Style
        - img [ref=e305] [cursor=pointer]
      - generic [ref=e307]:
        - generic [ref=e308]:
          - heading [level=6] [ref=e309]:
            - img [ref=e310]
            - text: Theme Mode
          - generic [ref=e312]:
            - button [ref=e313] [cursor=pointer]:
              - img [ref=e314]
              - text: Light
            - button [ref=e316] [cursor=pointer]:
              - img [ref=e317]
              - text: Dark
            - button [ref=e319] [cursor=pointer]:
              - img [ref=e320]
              - text: Auto
        - heading [level=6] [ref=e323]:
          - img [ref=e324]
          - text: Theme Color
        - generic [ref=e339]:
          - heading [level=6] [ref=e340]: Dashboard Layout
          - generic [ref=e341]:
            - button [ref=e342] [cursor=pointer]:
              - img [ref=e343]
              - text: Default
            - button [ref=e345] [cursor=pointer]:
              - img [ref=e346]
              - text: New Layout
    - generic [ref=e348]:
      - generic [ref=e349]:
        - heading [level=6] [ref=e350]: Change Password
        - img [ref=e351] [cursor=pointer]
      - generic [ref=e353]:
        - generic [ref=e354]:
          - text: "You are currently logged in as:"
          - strong [ref=e355]: qa.emp_b072852bd0614cf7@yopmail.com
          - generic [ref=e356]: Please enter your current password to verify your identity, then create a strong new password to keep your account secure.
        - alert [ref=e357]:
          - img [ref=e359]
          - generic [ref=e362]:
            - strong [ref=e363]: Security Notice
            - generic [ref=e364]: For your safety, you will be automatically logged out after a successful password change.
        - generic [ref=e365]:
          - generic [ref=e367]:
            - generic [ref=e368]:
              - generic [ref=e370]:
                - text: Old Password
                - generic [ref=e371]: "*"
              - textbox [ref=e373]:
                - /placeholder: Enter your current password
            - img [ref=e375] [cursor=pointer]
          - generic [ref=e378]:
            - generic [ref=e379]:
              - generic [ref=e381]:
                - text: New Password
                - generic [ref=e382]: "*"
              - textbox [ref=e384]:
                - /placeholder: Create a strong new password
            - img [ref=e386] [cursor=pointer]
          - generic [ref=e389]:
            - generic [ref=e390]:
              - generic [ref=e392]:
                - text: Confirm Password
                - generic [ref=e393]: "*"
              - textbox [disabled] [ref=e395]:
                - /placeholder: Re-enter your new password
            - img [ref=e397]
          - button [ref=e399] [cursor=pointer]: Update Password
  - dialog [ref=e402]:
    - banner [ref=e403]:
      - generic [ref=e404]:
        - generic [ref=e406]: Edit Shift Allowance Policy
        - button "close" [ref=e407] [cursor=pointer]:
          - img [ref=e408]
    - generic [ref=e411]:
      - generic [ref=e413]:
        - generic [ref=e414]:
          - generic [ref=e416]:
            - img [ref=e418]
            - generic [ref=e420]:
              - paragraph [ref=e421]: Basic Information
              - text: Enter the name and description for this shift allowance policy
          - generic [ref=e422]:
            - generic [ref=e424]:
              - generic [ref=e426]:
                - text: Policy Name
                - generic [ref=e427]: "*"
              - 'textbox "Ex: Night Shift Allowance Policy" [ref=e429]': VerPolicy 1795832245597
            - generic [ref=e431]:
              - generic [ref=e433]: Description
              - 'textbox "Ex: Allowance details and applicability..." [ref=e434]': Updated notes
        - generic [ref=e435]:
          - generic [ref=e437]:
            - img [ref=e439]
            - generic [ref=e441]:
              - paragraph [ref=e442]: Effective Date
              - text: Define the date from which this policy configuration becomes active
          - generic [ref=e445]:
            - generic [ref=e448]:
              - generic [ref=e449]: Effective From
              - img [ref=e450] [cursor=pointer]
            - group [ref=e453]:
              - generic [ref=e454]:
                - generic [ref=e455]:
                  - spinbutton "Day" [ref=e456]: "28"
                  - text: /
                - generic [ref=e457]:
                  - spinbutton "Month" [ref=e458]: "11"
                  - text: /
                - spinbutton "Year" [ref=e460]: "2026"
              - button "Choose date, selected date is Nov 28, 2026" [ref=e462] [cursor=pointer]:
                - img [ref=e463]
              - group
              - textbox [ref=e465]: 28/11/2026
        - generic [ref=e466]:
          - generic [ref=e468]:
            - img [ref=e470]
            - generic [ref=e473]:
              - paragraph [ref=e474]: Shift Allowance Calculation
              - text: Configure how shift allowances are calculated based on time range or predefined shifts
          - generic [ref=e475]:
            - generic [ref=e476]:
              - generic [ref=e478] [cursor=pointer]:
                - generic [ref=e479]:
                  - radio "Calculate Shift Allowance based on Shift start time falling in a time range" [checked] [ref=e480]
                  - generic [ref=e481]:
                    - img [ref=e482]
                    - img [ref=e484]
                - generic [ref=e486]: Calculate Shift Allowance based on Shift start time falling in a time range
              - generic [ref=e487]:
                - heading "Define Shift start time range and assign Shift Allowance Code" [level=6] [ref=e488]
                - generic [ref=e490]:
                  - paragraph [ref=e491]: If shift start time is between
                  - generic [ref=e492]:
                    - combobox "1 AM" [ref=e493] [cursor=pointer]:
                      - paragraph [ref=e495]: 1 AM
                    - textbox: "01"
                    - img
                    - group
                  - paragraph [ref=e496]: to
                  - generic [ref=e497]:
                    - combobox "6 AM" [ref=e498] [cursor=pointer]:
                      - paragraph [ref=e500]: 6 AM
                    - textbox: "06"
                    - img
                    - group
                  - paragraph [ref=e501]: shift allowance is paid as
                  - generic [ref=e502]:
                    - combobox "AA" [ref=e503] [cursor=pointer]:
                      - paragraph [ref=e505]: AA
                    - textbox: AA
                    - img
                    - group
                  - generic "Add rule" [ref=e507] [cursor=pointer]:
                    - button [ref=e508]:
                      - img [ref=e509]
                - generic [ref=e511]:
                  - generic [ref=e512] [cursor=pointer]:
                    - checkbox [ref=e513]
                    - img [ref=e514]
                  - paragraph [ref=e516]: Ignore employees who are assigned flexible shift for the purpose of shift allowance consideration.
                  - img [ref=e517] [cursor=pointer]
            - generic [ref=e521] [cursor=pointer]:
              - generic [ref=e522]:
                - radio "Calculate Shift Allowance based on Pre-defined Shifts" [ref=e523]
                - img [ref=e525]
              - generic [ref=e527]: Calculate Shift Allowance based on Pre-defined Shifts
        - generic [ref=e528]:
          - generic [ref=e530]:
            - img [ref=e532]
            - generic [ref=e534]:
              - paragraph [ref=e535]: Work Hours Threshold
              - text: Set minimum percentage of work hours required to qualify for shift allowance
          - generic [ref=e538]:
            - generic [ref=e539] [cursor=pointer]:
              - checkbox [ref=e540]
              - img [ref=e541]
            - paragraph [ref=e543]: Ignore Shift Allowance calculation if work hours of employee is less than
            - textbox "1" [disabled] [ref=e545]
            - paragraph [ref=e546]: "%"
            - generic [ref=e547]:
              - combobox "Select" [disabled] [ref=e548]:
                - paragraph [ref=e549]: Select
              - textbox [disabled]
              - img
              - group
        - generic [ref=e550]:
          - generic [ref=e552]:
            - img [ref=e554]
            - generic [ref=e556]:
              - paragraph [ref=e557]: Applicability
              - text: Specify whether shift allowance is applicable on weekly offs and public holidays
          - generic [ref=e559]:
            - generic [ref=e560]:
              - generic [ref=e561] [cursor=pointer]:
                - checkbox [ref=e562]
                - img [ref=e563]
              - paragraph [ref=e565]: Weekly Offs
            - generic [ref=e566]:
              - generic [ref=e567] [cursor=pointer]:
                - checkbox [ref=e568]
                - img [ref=e569]
              - paragraph [ref=e571]: Holidays
      - generic [ref=e572]:
        - generic [ref=e573]:
          - img [ref=e574]
          - paragraph [ref=e576]: Help Center
        - generic [ref=e577]:
          - generic [ref=e578]:
            - paragraph [ref=e579]: What is Shift Allowance Policy?
            - generic [ref=e580]: A shift allowance policy defines additional financial compensation paid to employees working specific or non-standard shifts (e.g. night shifts, rotational shifts, or weekend shifts).
          - generic [ref=e581]:
            - paragraph [ref=e582]: Time Range vs Pre-defined Shifts?
            - generic [ref=e583]: Configure based on 'Time Range' to pay allowances whenever an employee's shift start time falls within a designated window. Configure based on 'Pre-defined Shifts' to map specific allowance pay codes to individual existing shifts.
          - generic [ref=e584]:
            - paragraph [ref=e585]: How does Work Hours Threshold work?
            - generic [ref=e586]: Enable the work hours threshold to specify a minimum percentage of gross or payable shift hours an employee must complete to become eligible for the shift allowance. You can also specify if the allowance applies on weekly offs and public holidays.
  - dialog [ref=e587]:
    - generic [ref=e591]:
      - generic [ref=e592]:
        - generic [ref=e593] [cursor=pointer]:
          - generic [ref=e595]: November 2026
          - button "calendar view is open, switch to year view" [ref=e596]:
            - img [ref=e597]
        - generic [ref=e599]:
          - button "Previous month" [disabled]:
            - img
          - button "Next month" [ref=e601] [cursor=pointer]:
            - img [ref=e602]
      - grid "November 2026" [ref=e606]:
        - row "Sunday Monday Tuesday Wednesday Thursday Friday Saturday" [ref=e607]:
          - columnheader "Sunday" [ref=e608]: S
          - columnheader "Monday" [ref=e609]: M
          - columnheader "Tuesday" [ref=e610]: T
          - columnheader "Wednesday" [ref=e611]: W
          - columnheader "Thursday" [ref=e612]: T
          - columnheader "Friday" [ref=e613]: F
          - columnheader "Saturday" [ref=e614]: S
        - rowgroup [ref=e615]:
          - row "1 2 3 4 5 6 7" [ref=e616]:
            - gridcell "1" [disabled]
            - gridcell "2" [disabled]
            - gridcell "3" [disabled]
            - gridcell "4" [disabled]
            - gridcell "5" [disabled]
            - gridcell "6" [disabled]
            - gridcell "7" [disabled]
          - row "8 9 10 11 12 13 14" [ref=e617]:
            - gridcell "8" [disabled]
            - gridcell "9" [disabled]
            - gridcell "10" [disabled]
            - gridcell "11" [disabled]
            - gridcell "12" [disabled]
            - gridcell "13" [disabled]
            - gridcell "14" [disabled]
          - row "15 16 17 18 19 20 21" [ref=e618]:
            - gridcell "15" [disabled]
            - gridcell "16" [disabled]
            - gridcell "17" [disabled]
            - gridcell "18" [disabled]
            - gridcell "19" [disabled]
            - gridcell "20" [disabled]
            - gridcell "21" [disabled]
          - row "22 23 24 25 26 27 28" [ref=e619]:
            - gridcell "22" [disabled]
            - gridcell "23" [disabled]
            - gridcell "24" [disabled]
            - gridcell "25" [disabled]
            - gridcell "26" [disabled]
            - gridcell "27" [disabled]
            - gridcell "28" [disabled] [selected]
          - row "29 30" [ref=e620]:
            - gridcell "29" [active] [ref=e621] [cursor=pointer]
            - gridcell "30" [ref=e622] [cursor=pointer]
            - gridcell
            - gridcell
            - gridcell
            - gridcell
            - gridcell
```

# Test source

```ts
  97  |             await expect(this.descriptionInput).toBeVisible({ timeout: 5000 });
  98  |         }
  99  |     }
  100 | 
  101 |     async selectCalculationType(type) {
  102 |         if (type === 'TIME_RANGE') {
  103 |             await this.timeRangeRadio.scrollIntoViewIfNeeded().catch(() => {});
  104 |             await this.timeRangeRadio.evaluate(el => el.click());
  105 |             await expect(this.timeRangeRadio).toBeChecked({ timeout: 5000 });
  106 |         } else if (type === 'PRE_DEFINED_SHIFTS') {
  107 |             await this.preDefinedShiftsRadio.scrollIntoViewIfNeeded().catch(() => {});
  108 |             await this.preDefinedShiftsRadio.evaluate(el => el.click());
  109 |             await expect(this.preDefinedShiftsRadio).toBeChecked({ timeout: 5000 });
  110 |         }
  111 |     }
  112 | 
  113 |     async fillDefaultTimeRangeRule() {
  114 |         logger.info('Filling default Time Range shift allowance rule');
  115 |         const fromTimeSelect = this.modal.locator('#mui-component-select-fromTime_0');
  116 |         if (await fromTimeSelect.isVisible().catch(() => false)) {
  117 |             await fromTimeSelect.click();
  118 |             await this.page.getByRole('option').nth(1).click();
  119 |         }
  120 | 
  121 |         const toTimeSelect = this.modal.locator('#mui-component-select-toTime_0');
  122 |         if (await toTimeSelect.isVisible().catch(() => false)) {
  123 |             await toTimeSelect.click();
  124 |             await this.page.getByRole('option').nth(6).click();
  125 |         }
  126 | 
  127 |         const codeSelect = this.modal.locator('#mui-component-select-shiftAllowanceCode_0');
  128 |         if (await codeSelect.isVisible().catch(() => false)) {
  129 |             await codeSelect.click();
  130 |             await this.page.getByRole('option').first().click();
  131 |         }
  132 |     }
  133 | 
  134 |     async getShiftRow(index = 0) {
  135 |         return this.modal.locator(`[data-policy-shift-row="${index}"]`);
  136 |     }
  137 | 
  138 |     async selectShiftForPredefinedRow(index, shiftNameOrCode) {
  139 |         const row = await this.getShiftRow(index);
  140 |         const shiftSelect = row.locator('.MuiSelect-select').first();
  141 |         await shiftSelect.click();
  142 |         const option = this.page.getByRole('option').filter({ hasText: shiftNameOrCode }).first();
  143 |         await expect(option).toBeVisible({ timeout: 5000 });
  144 |         await option.click();
  145 |     }
  146 | 
  147 |     async selectPayCodeForPredefinedRow(index, payCode) {
  148 |         const row = await this.getShiftRow(index);
  149 |         const payCodeSelect = row.locator('.MuiSelect-select').last();
  150 |         await payCodeSelect.click();
  151 |         const option = this.page.getByRole('option').filter({ hasText: payCode }).first();
  152 |         await expect(option).toBeVisible({ timeout: 5000 });
  153 |         await option.click();
  154 |     }
  155 | 
  156 |     async setThreshold(percentage, basis = 'Gross Hours') {
  157 |         await this.thresholdCheckbox.scrollIntoViewIfNeeded().catch(() => {});
  158 |         if (!(await this.thresholdCheckbox.isChecked())) {
  159 |             await this.thresholdCheckbox.evaluate(el => el.click());
  160 |         }
  161 |         await this.thresholdPercentageInput.clear();
  162 |         await this.thresholdPercentageInput.fill(String(percentage));
  163 | 
  164 |         if (basis) {
  165 |             await this.thresholdBasisSelect.click();
  166 |             const option = this.page.getByRole('option', { name: basis }).first();
  167 |             await expect(option).toBeVisible({ timeout: 5000 });
  168 |             await option.click();
  169 |         }
  170 |     }
  171 | 
  172 |     async setApplicability({ weeklyOffs = false, holidays = false } = {}) {
  173 |         await this.weeklyOffsCheckbox.scrollIntoViewIfNeeded().catch(() => {});
  174 |         const isWeeklyOffChecked = await this.weeklyOffsCheckbox.isChecked();
  175 |         if (isWeeklyOffChecked !== weeklyOffs) {
  176 |             await this.weeklyOffsCheckbox.evaluate(el => el.click());
  177 |         }
  178 | 
  179 |         await this.holidaysCheckbox.scrollIntoViewIfNeeded().catch(() => {});
  180 |         const isHolidayChecked = await this.holidaysCheckbox.isChecked();
  181 |         if (isHolidayChecked !== holidays) {
  182 |             await this.holidaysCheckbox.evaluate(el => el.click());
  183 |         }
  184 |     }
  185 | 
  186 |     async openEffectiveFromCalendar() {
  187 |         logger.info('Opening Effective From date picker calendar');
  188 |         await this.effectiveFromDateButton.click();
  189 |         const popper = this.page.locator('.MuiPickersLayout-root').first();
  190 |         await expect(popper).toBeVisible({ timeout: 5000 });
  191 |     }
  192 | 
  193 |     async selectDayInCalendar(day) {
  194 |         logger.info(`Selecting day ${day} in calendar`);
  195 |         const dayBtn = this.page.locator('.MuiPickersLayout-root button[role="gridcell"]:not([disabled]), .MuiDateCalendar-root button[role="gridcell"]:not([disabled])')
  196 |             .filter({ hasText: new RegExp(`^\\s*${Number(day)}\\s*$`) }).first();
> 197 |         await expect(dayBtn).toBeVisible({ timeout: 5000 });
      |                              ^ Error: expect(locator).toBeVisible() failed
  198 |         await dayBtn.click();
  199 |     }
  200 | 
  201 |     async clearEffectiveFrom() {
  202 |         logger.info('Clearing Effective From date field');
  203 |         const sections = this.effectiveFromField.locator('.MuiPickersSectionList-sectionContent');
  204 |         const count = await sections.count();
  205 |         if (count > 0) {
  206 |             for (let i = 0; i < count; i++) {
  207 |                 await sections.nth(i).click();
  208 |                 await this.page.keyboard.press('Backspace');
  209 |                 await this.page.keyboard.press('Delete');
  210 |             }
  211 |         } else {
  212 |             await this.effectiveFromSectionList.click();
  213 |             await this.page.keyboard.press('Control+A');
  214 |             await this.page.keyboard.press('Backspace');
  215 |         }
  216 |     }
  217 | 
  218 |     async save() {
  219 |         logger.info('Saving Shift Allowance Policy');
  220 |         await expect(this.saveButton).toBeVisible({ timeout: 10_000 });
  221 |         await expect(this.saveButton).toBeEnabled({ timeout: 10_000 });
  222 |         await this.saveButton.click();
  223 |     }
  224 | 
  225 |     async reset() {
  226 |         logger.info('Resetting Shift Allowance Policy form');
  227 |         await this.resetButton.click();
  228 |     }
  229 | 
  230 |     async close() {
  231 |         logger.info('Closing Shift Allowance Policy modal');
  232 |         try {
  233 |             const closeBtn = this.modal.locator('button:has(svg[data-testid*="Close" i]), button[aria-label*="close" i], .MuiDialogTitle-root button, header button').first();
  234 |             if (await closeBtn.isVisible({ timeout: 2000 }).catch(() => false)) {
  235 |                 await closeBtn.click({ force: true, timeout: 3000 }).catch(() => {});
  236 |             } else {
  237 |                 await this.page.keyboard.press('Escape');
  238 |             }
  239 |         } catch {
  240 |             await this.page.keyboard.press('Escape');
  241 |         }
  242 |         // Handle discard / unsaved changes modal if triggered
  243 |         const discardBtn = this.page.getByRole('button', { name: /Discard|Leave|Yes/i }).first();
  244 |         if (await discardBtn.isVisible({ timeout: 2000 }).catch(() => false)) {
  245 |             await discardBtn.click().catch(() => {});
  246 |         }
  247 |         await this.modal.waitFor({ state: 'hidden', timeout: 5000 }).catch(async () => {
  248 |             await this.page.keyboard.press('Escape');
  249 |         });
  250 |     }
  251 | }
  252 | 
  253 | module.exports = AddShiftAllowancePolicyModal;
  254 | 
```