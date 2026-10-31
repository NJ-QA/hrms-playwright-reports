# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: timeTracking/timeTrackingPolicyAllocation.spec.js >> PIN-153 Time Tracking Policy Allocation & Auto-Assign >> PIN_153_04 PIN_153_06 PIN_153_09 PIN_153_11 Verify employee allocation table, search, bulk select state transitions, and pagination
- Location: tests/timeTracking/timeTrackingPolicyAllocation.spec.js:97:5

# Error details

```
TimeoutError: locator.check: Timeout 10000ms exceeded.
Call log:
  - waiting for locator('table.table-view-table').or(locator('table[aria-label="Data table"]')).locator('tbody tr.table-view-data-row').first().locator('.table-view-row-checkbox input[type="checkbox"]')

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
        - button "Messages 133" [ref=e32] [cursor=pointer]:
          - img [ref=e34]
          - generic [ref=e36]:
            - generic [ref=e37]: Messages
            - generic [ref=e38]: "133"
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
          - tab "Shifts/Weekly Offs & Holidays" [ref=e192] [cursor=pointer]:
            - generic [ref=e193]: Shifts/Weekly Offs & Holidays
          - tab "Attendance Tracking" [selected] [ref=e194] [cursor=pointer]:
            - generic [ref=e195]: Attendance Tracking
          - tab "Leave Management" [ref=e196] [cursor=pointer]:
            - generic [ref=e197]: Leave Management
          - tab "Settings" [ref=e198] [cursor=pointer]:
            - generic [ref=e199]: Settings
        - separator [ref=e200]
      - generic [ref=e202]:
        - tablist [ref=e203]:
          - tab "Regularize & Cancel Penalties" [ref=e204] [cursor=pointer]:
            - generic [ref=e205]: Regularize & Cancel Penalties
          - tab "Penalization Policy" [ref=e206] [cursor=pointer]:
            - generic [ref=e207]: Penalization Policy
          - tab "Penalization Policy Allocation" [ref=e208] [cursor=pointer]:
            - generic [ref=e209]: Penalization Policy Allocation
          - tab "Time Tracking Policy" [ref=e210] [cursor=pointer]:
            - generic [ref=e211]: Time Tracking Policy
          - tab "Time Tracking Policy Allocation" [selected] [ref=e212] [cursor=pointer]:
            - generic [ref=e213]: Time Tracking Policy Allocation
        - tabpanel [ref=e214]:
          - generic [ref=e215]:
            - generic [ref=e216]:
              - generic [ref=e217]:
                - generic [ref=e220]:
                  - textbox "Search by employee name, email, code..." [active] [ref=e221]
                  - generic:
                    - img
                - generic [ref=e224] [cursor=pointer]:
                  - img [ref=e226]
                  - textbox "Select Department" [ref=e228]
                  - group
                - generic [ref=e231] [cursor=pointer]:
                  - img [ref=e233]
                  - textbox "Select Location" [ref=e235]
                  - group
                - generic [ref=e238] [cursor=pointer]:
                  - img [ref=e240]
                  - textbox "Select Time Tracking Policy" [ref=e242]
                  - group
              - generic [ref=e243]: "Total: 2389"
            - generic [ref=e244]:
              - generic [ref=e245]:
                - generic [ref=e246]:
                  - generic [ref=e247]:
                    - button "Update Time Tracking Policy" [disabled]:
                      - img
                      - text: Update Time Tracking Policy
                  - button "Column visibility" [ref=e249] [cursor=pointer]:
                    - img [ref=e250]
                - table "Data table" [ref=e253]:
                  - rowgroup [ref=e254]:
                    - row "EMPLOYEE NAME EMPLOYEE CODE DESIGNATION DEPARTMENT LOCATION REPORTING MANAGER TIME TRACKING POLICY ACTIONS" [ref=e255]:
                      - columnheader "EMPLOYEE NAME" [ref=e256]:
                        - generic [ref=e257]:
                          - generic [ref=e259] [cursor=pointer]:
                            - checkbox [ref=e260]
                            - img [ref=e261]
                          - generic [ref=e265]: EMPLOYEE NAME
                      - columnheader "EMPLOYEE CODE" [ref=e266]:
                        - generic [ref=e268]: EMPLOYEE CODE
                      - columnheader "DESIGNATION" [ref=e269]:
                        - generic [ref=e271]: DESIGNATION
                      - columnheader "DEPARTMENT" [ref=e272]:
                        - generic [ref=e274]: DEPARTMENT
                      - columnheader "LOCATION" [ref=e275]:
                        - generic [ref=e277]: LOCATION
                      - columnheader "REPORTING MANAGER" [ref=e278]:
                        - generic [ref=e280]: REPORTING MANAGER
                      - columnheader "TIME TRACKING POLICY" [ref=e281]:
                        - generic [ref=e283]: TIME TRACKING POLICY
                      - columnheader "ACTIONS" [ref=e284]:
                        - generic [ref=e286]: ACTIONS
                  - rowgroup [ref=e287]:
                    - row "NM Neeraj Maheshwari EMP-000377-TEST Quality Head QA + 1 Jaipur Jaipur N Neeraj QA Lead Default Time Tracking Policy" [ref=e288]:
                      - cell "NM Neeraj Maheshwari" [ref=e289]:
                        - generic [ref=e290]:
                          - generic [ref=e292] [cursor=pointer]:
                            - checkbox [ref=e293]
                            - img [ref=e294]
                          - generic [ref=e297]:
                            - generic [ref=e298]: NM
                            - paragraph [ref=e300] [cursor=pointer]: Neeraj Maheshwari
                      - cell "EMP-000377-TEST" [ref=e301]:
                        - paragraph [ref=e302]: EMP-000377-TEST
                      - cell "Quality Head" [ref=e303]:
                        - paragraph [ref=e304]: Quality Head
                      - cell "QA + 1" [ref=e305]:
                        - generic [ref=e306]:
                          - paragraph [ref=e309]: QA
                          - generic [ref=e311]: + 1
                      - cell "Jaipur Jaipur" [ref=e312]:
                        - paragraph [ref=e316]: Jaipur Jaipur
                      - cell "N Neeraj QA Lead" [ref=e317]:
                        - generic [ref=e319]:
                          - generic [ref=e320]: "N"
                          - generic [ref=e321]:
                            - paragraph [ref=e323] [cursor=pointer]: Neeraj
                            - paragraph [ref=e324]: QA Lead
                      - cell "Default Time Tracking Policy" [ref=e325]:
                        - paragraph [ref=e328]: Default Time Trackin...
                      - cell [ref=e329]
                    - row "Aarti EMP-000335-TEST QA Engineer II N/A N/A N/A Default Time Tracking Policy" [ref=e330]:
                      - cell "Aarti" [ref=e331]:
                        - generic [ref=e332]:
                          - generic [ref=e334] [cursor=pointer]:
                            - checkbox [ref=e335]
                            - img [ref=e336]
                          - generic [ref=e339]:
                            - img [ref=e341]
                            - paragraph [ref=e343] [cursor=pointer]: Aarti
                      - cell "EMP-000335-TEST" [ref=e344]:
                        - paragraph [ref=e345]: EMP-000335-TEST
                      - cell "QA Engineer II" [ref=e346]:
                        - paragraph [ref=e347]: QA Engineer II
                      - cell "N/A" [ref=e348]
                      - cell "N/A" [ref=e349]
                      - cell "N/A" [ref=e350]
                      - cell "Default Time Tracking Policy" [ref=e351]:
                        - paragraph [ref=e354]: Default Time Trackin...
                      - cell [ref=e355]
                    - row "BR Bhanwar Singh Rathorea MB002 N/A N/A N/A N/A Default Time Tracking Policy" [ref=e356]:
                      - cell "BR Bhanwar Singh Rathorea" [ref=e357]:
                        - generic [ref=e358]:
                          - generic [ref=e360] [cursor=pointer]:
                            - checkbox [ref=e361]
                            - img [ref=e362]
                          - generic [ref=e365]:
                            - generic [ref=e366]: BR
                            - paragraph [ref=e368] [cursor=pointer]: Bhanwar Singh Rathorea
                      - cell "MB002" [ref=e369]:
                        - paragraph [ref=e370]: MB002
                      - cell "N/A" [ref=e371]
                      - cell "N/A" [ref=e372]
                      - cell "N/A" [ref=e373]
                      - cell "N/A" [ref=e374]
                      - cell "Default Time Tracking Policy" [ref=e375]:
                        - paragraph [ref=e378]: Default Time Trackin...
                      - cell [ref=e379]
                    - row "DG Dushyant Puri Goswami MB003 N/A N/A N/A N/A Default Time Tracking Policy" [ref=e380]:
                      - cell "DG Dushyant Puri Goswami" [ref=e381]:
                        - generic [ref=e382]:
                          - generic [ref=e384] [cursor=pointer]:
                            - checkbox [ref=e385]
                            - img [ref=e386]
                          - generic [ref=e389]:
                            - generic [ref=e390]: DG
                            - paragraph [ref=e392] [cursor=pointer]: Dushyant Puri Goswami
                      - cell "MB003" [ref=e393]:
                        - paragraph [ref=e394]: MB003
                      - cell "N/A" [ref=e395]
                      - cell "N/A" [ref=e396]
                      - cell "N/A" [ref=e397]
                      - cell "N/A" [ref=e398]
                      - cell "Default Time Tracking Policy" [ref=e399]:
                        - paragraph [ref=e402]: Default Time Trackin...
                      - cell [ref=e403]
                    - row "AS Aastha Singh MB004 QA N/A N/A N/A QA Disabled Web 0ac78b15" [ref=e404]:
                      - cell "AS Aastha Singh" [ref=e405]:
                        - generic [ref=e406]:
                          - generic [ref=e408] [cursor=pointer]:
                            - checkbox [ref=e409]
                            - img [ref=e410]
                          - generic [ref=e413]:
                            - generic [ref=e414]: AS
                            - paragraph [ref=e416] [cursor=pointer]: Aastha Singh
                      - cell "MB004" [ref=e417]:
                        - paragraph [ref=e418]: MB004
                      - cell "QA" [ref=e419]:
                        - paragraph [ref=e420]: QA
                      - cell "N/A" [ref=e421]
                      - cell "N/A" [ref=e422]
                      - cell "N/A" [ref=e423]
                      - cell "QA Disabled Web 0ac78b15" [ref=e424]:
                        - paragraph [ref=e427]: QA Disabled Web 0ac7...
                      - cell [ref=e428]
                    - row "DJ Dewanshi Jain MB005 N/A N/A N/A N/A Default Time Tracking Policy" [ref=e429]:
                      - cell "DJ Dewanshi Jain" [ref=e430]:
                        - generic [ref=e431]:
                          - generic [ref=e433] [cursor=pointer]:
                            - checkbox [ref=e434]
                            - img [ref=e435]
                          - generic [ref=e438]:
                            - generic [ref=e439]: DJ
                            - paragraph [ref=e441] [cursor=pointer]: Dewanshi Jain
                      - cell "MB005" [ref=e442]:
                        - paragraph [ref=e443]: MB005
                      - cell "N/A" [ref=e444]
                      - cell "N/A" [ref=e445]
                      - cell "N/A" [ref=e446]
                      - cell "N/A" [ref=e447]
                      - cell "Default Time Tracking Policy" [ref=e448]:
                        - paragraph [ref=e451]: Default Time Trackin...
                      - cell [ref=e452]
                    - row "LK Lokesh MB006 N/A N/A N/A N/A Default Time Tracking Policy" [ref=e453]:
                      - cell "LK Lokesh" [ref=e454]:
                        - generic [ref=e455]:
                          - generic [ref=e457] [cursor=pointer]:
                            - checkbox [ref=e458]
                            - img [ref=e459]
                          - generic [ref=e462]:
                            - generic [ref=e463]: LK
                            - paragraph [ref=e465] [cursor=pointer]: Lokesh
                      - cell "MB006" [ref=e466]:
                        - paragraph [ref=e467]: MB006
                      - cell "N/A" [ref=e468]
                      - cell "N/A" [ref=e469]
                      - cell "N/A" [ref=e470]
                      - cell "N/A" [ref=e471]
                      - cell "Default Time Tracking Policy" [ref=e472]:
                        - paragraph [ref=e475]: Default Time Trackin...
                      - cell [ref=e476]
                    - row "NS Niranjan Sharma MB007 N/A N/A N/A N/A Default Time Tracking Policy" [ref=e477]:
                      - cell "NS Niranjan Sharma" [ref=e478]:
                        - generic [ref=e479]:
                          - generic [ref=e481] [cursor=pointer]:
                            - checkbox [ref=e482]
                            - img [ref=e483]
                          - generic [ref=e486]:
                            - generic [ref=e487]: NS
                            - paragraph [ref=e489] [cursor=pointer]: Niranjan Sharma
                      - cell "MB007" [ref=e490]:
                        - paragraph [ref=e491]: MB007
                      - cell "N/A" [ref=e492]
                      - cell "N/A" [ref=e493]
                      - cell "N/A" [ref=e494]
                      - cell "N/A" [ref=e495]
                      - cell "Default Time Tracking Policy" [ref=e496]:
                        - paragraph [ref=e499]: Default Time Trackin...
                      - cell [ref=e500]
                    - row "PB Prabudh Bharwdwaj MB008 N/A N/A N/A N/A Default Time Tracking Policy" [ref=e501]:
                      - cell "PB Prabudh Bharwdwaj" [ref=e502]:
                        - generic [ref=e503]:
                          - generic [ref=e505] [cursor=pointer]:
                            - checkbox [ref=e506]
                            - img [ref=e507]
                          - generic [ref=e510]:
                            - generic [ref=e511]: PB
                            - paragraph [ref=e513] [cursor=pointer]: Prabudh Bharwdwaj
                      - cell "MB008" [ref=e514]:
                        - paragraph [ref=e515]: MB008
                      - cell "N/A" [ref=e516]
                      - cell "N/A" [ref=e517]
                      - cell "N/A" [ref=e518]
                      - cell "N/A" [ref=e519]
                      - cell "Default Time Tracking Policy" [ref=e520]:
                        - paragraph [ref=e523]: Default Time Trackin...
                      - cell [ref=e524]
                    - row "NM Neeraj Maheshwari MB009 N/A N/A N/A N/A Default Time Tracking Policy" [ref=e525]:
                      - cell "NM Neeraj Maheshwari" [ref=e526]:
                        - generic [ref=e527]:
                          - generic [ref=e529] [cursor=pointer]:
                            - checkbox [ref=e530]
                            - img [ref=e531]
                          - generic [ref=e534]:
                            - generic [ref=e535]: NM
                            - paragraph [ref=e537] [cursor=pointer]: Neeraj Maheshwari
                      - cell "MB009" [ref=e538]:
                        - paragraph [ref=e539]: MB009
                      - cell "N/A" [ref=e540]
                      - cell "N/A" [ref=e541]
                      - cell "N/A" [ref=e542]
                      - cell "N/A" [ref=e543]
                      - cell "Default Time Tracking Policy" [ref=e544]:
                        - paragraph [ref=e547]: Default Time Trackin...
                      - cell [ref=e548]
              - generic [ref=e550]:
                - paragraph [ref=e551]: "Rows per page:"
                - generic [ref=e552]:
                  - 'combobox "Rows per page: 10" [ref=e553] [cursor=pointer]': "10"
                  - textbox: "10"
                  - img
                - paragraph [ref=e554]: 1–10 of 2389
                - generic [ref=e555]:
                  - button "Go to previous page" [disabled]:
                    - img
                  - button "Go to next page" [ref=e556] [cursor=pointer]:
                    - img [ref=e557]
  - generic [ref=e559]:
    - generic [ref=e560]:
      - heading "Theme & Style" [level=6] [ref=e561]
      - img [ref=e562] [cursor=pointer]
    - generic [ref=e564]:
      - generic [ref=e565]:
        - heading "Theme Mode" [level=6] [ref=e566]:
          - img [ref=e567]
          - text: Theme Mode
        - generic [ref=e569]:
          - button "Light" [ref=e570] [cursor=pointer]:
            - img [ref=e571]
            - text: Light
          - button "Dark" [ref=e573] [cursor=pointer]:
            - img [ref=e574]
            - text: Dark
          - button "Auto" [ref=e576] [cursor=pointer]:
            - img [ref=e577]
            - text: Auto
      - generic [ref=e579]:
        - heading "Theme Color" [level=6] [ref=e580]:
          - img [ref=e581]
          - text: Theme Color
        - generic [ref=e583]:
          - generic "Default" [ref=e584] [cursor=pointer]
          - generic "Orange" [ref=e586] [cursor=pointer]
          - generic "Marun" [ref=e588] [cursor=pointer]
          - generic "Blue" [ref=e590] [cursor=pointer]
          - generic "Green" [ref=e592] [cursor=pointer]
          - generic "Gray" [ref=e594] [cursor=pointer]
      - generic [ref=e596]:
        - heading "Dashboard Layout" [level=6] [ref=e597]
        - generic [ref=e598]:
          - button "Default" [ref=e599] [cursor=pointer]:
            - img [ref=e600]
            - text: Default
          - button "New Layout" [ref=e602] [cursor=pointer]:
            - img [ref=e603]
            - text: New Layout
  - generic [ref=e605]:
    - generic [ref=e606]:
      - heading "Change Password" [level=6] [ref=e607]
      - img [ref=e608] [cursor=pointer]
    - generic [ref=e610]:
      - generic [ref=e611]:
        - text: "You are currently logged in as:"
        - strong [ref=e612]: xperts_imaging@yopmail.com
        - generic [ref=e613]: Please enter your current password to verify your identity, then create a strong new password to keep your account secure.
      - alert [ref=e614]:
        - img [ref=e616]
        - generic [ref=e619]:
          - strong [ref=e620]: Security Notice
          - generic [ref=e621]: For your safety, you will be automatically logged out after a successful password change.
      - generic [ref=e622]:
        - generic [ref=e624]:
          - generic [ref=e625]:
            - generic [ref=e627]:
              - text: Old Password
              - generic [ref=e628]: "*"
            - textbox "Enter your current password" [ref=e630]
          - img [ref=e632] [cursor=pointer]
        - generic [ref=e635]:
          - generic [ref=e636]:
            - generic [ref=e638]:
              - text: New Password
              - generic [ref=e639]: "*"
            - textbox "Create a strong new password" [ref=e641]
          - img [ref=e643] [cursor=pointer]
        - generic [ref=e646]:
          - generic [ref=e647]:
            - generic [ref=e649]:
              - text: Confirm Password
              - generic [ref=e650]: "*"
            - textbox "Re-enter your new password" [disabled] [ref=e652]
          - img [ref=e654]
        - button "Update Password" [ref=e656] [cursor=pointer]
```

# Test source

```ts
  1   | const { expect } = require('@playwright/test');
  2   | const BaseComponent = require('@pages/components/BaseComponent');
  3   | 
  4   | class TimeTrackingPolicyAllocationPage extends BaseComponent {
  5   |     constructor(page) {
  6   |         super(page);
  7   |         this.tab = page.getByRole('tab', { name: 'Time Tracking Policy Allocation' })
  8   |             .or(page.locator('.hrms-tab-button').filter({ hasText: 'Time Tracking Policy Allocation' }));
  9   |         this.toolbar = page.locator('.policy-allocation-toolbar');
  10  |         this.searchInput = page.locator('input[name="comanSearchInput"]')
  11  |             .or(page.getByPlaceholder('Search by employee name, email, code...'));
  12  |         this.departmentFilter = page.locator('input[placeholder="Select Department"]');
  13  |         this.locationFilter = page.locator('input[placeholder="Select Location"]');
  14  |         this.policyFilter = page.locator('input[placeholder="Select Time Tracking Policy"]');
  15  |         this.totalCount = page.locator('.policy-allocation-total-count');
  16  |         
  17  |         this.updatePolicyButton = page.locator('button.table-view-toolbar-button')
  18  |             .filter({ hasText: 'Update Time Tracking Policy' })
  19  |             .or(page.getByRole('button', { name: /Update Time Tracking Policy/i }));
  20  |         this.columnVisibilityButton = page.locator('.table-view-visibility-button')
  21  |             .or(page.getByRole('button', { name: 'Column visibility' }));
  22  | 
  23  |         this.table = page.locator('table.table-view-table')
  24  |             .or(page.locator('table[aria-label="Data table"]'));
  25  |         this.header = this.table.locator('thead');
  26  |         this.selectAllCheckbox = this.header.locator('.table-view-select-all input[type="checkbox"]');
  27  |         this.rows = this.table.locator('tbody tr.table-view-data-row');
  28  | 
  29  |         this.pagination = page.locator('.policy-allocation-pagination')
  30  |             .or(page.locator('.MuiTablePagination-root'));
  31  |         this.rowsPerPageSelect = this.pagination.getByRole('combobox', { name: /Rows per page/i })
  32  |             .or(this.pagination.locator('.MuiSelect-select'));
  33  |         this.displayedRowsText = this.pagination.locator('.MuiTablePagination-displayedRows');
  34  |         this.prevPageButton = this.pagination.getByRole('button', { name: /previous page/i });
  35  |         this.nextPageButton = this.pagination.getByRole('button', { name: /next page/i });
  36  | 
  37  |         this.successToast = page.getByRole('alert')
  38  |             .filter({ hasText: /Time Tracking Policy updated successfully/i });
  39  |     }
  40  | 
  41  |     async openTab() {
  42  |         await this.tab.click();
  43  |         await expect(this.tab).toHaveAttribute('aria-selected', 'true');
  44  |         await this.verifyLoaded();
  45  |     }
  46  | 
  47  |     async verifyLoaded() {
  48  |         await expect(this.toolbar).toBeVisible({ timeout: 25_000 });
  49  |         await expect(this.searchInput).toBeVisible({ timeout: 25_000 });
  50  |         await expect(this.table).toBeVisible({ timeout: 25_000 });
  51  |         await expect(this.rows.first()).toBeVisible({ timeout: 25_000 });
  52  |     }
  53  | 
  54  |     async searchEmployee(text) {
  55  |         await this.searchInput.clear();
  56  |         await this.searchInput.fill(text);
  57  |         await this.page.waitForTimeout(1000);
  58  |         await expect(this.rows.first()).toBeVisible({ timeout: 10_000 });
  59  |     }
  60  | 
  61  |     async clearSearch() {
  62  |         await this.searchInput.clear();
  63  |         await this.page.waitForTimeout(1000);
  64  |         await expect(this.rows.first()).toBeVisible({ timeout: 10_000 });
  65  |     }
  66  | 
  67  |     async getTotalCountNumber() {
  68  |         const text = await this.totalCount.innerText();
  69  |         const match = text.match(/\d+/);
  70  |         return match ? parseInt(match[0], 10) : 0;
  71  |     }
  72  | 
  73  |     getRow(identifier) {
  74  |         return this.rows.filter({ hasText: identifier });
  75  |     }
  76  | 
  77  |     getRowCheckbox(identifier) {
  78  |         const row = typeof identifier === 'number' ? this.rows.nth(identifier) : this.getRow(identifier);
  79  |         return row.locator('.table-view-row-checkbox input[type="checkbox"]');
  80  |     }
  81  | 
  82  |     async selectEmployee(identifier) {
  83  |         const checkbox = this.getRowCheckbox(identifier);
> 84  |         await checkbox.check();
      |                        ^ TimeoutError: locator.check: Timeout 10000ms exceeded.
  85  |         await expect(checkbox).toBeChecked();
  86  |     }
  87  | 
  88  |     async unselectEmployee(identifier) {
  89  |         const checkbox = this.getRowCheckbox(identifier);
  90  |         await checkbox.uncheck();
  91  |         await expect(checkbox).not.toBeChecked();
  92  |     }
  93  | 
  94  |     async selectAllOnPage() {
  95  |         await this.selectAllCheckbox.check();
  96  |         await expect(this.selectAllCheckbox).toBeChecked();
  97  |     }
  98  | 
  99  |     async unselectAllOnPage() {
  100 |         await this.selectAllCheckbox.uncheck();
  101 |         await expect(this.selectAllCheckbox).not.toBeChecked();
  102 |     }
  103 | 
  104 |     async getAssignedPolicyName(identifier) {
  105 |         const row = typeof identifier === 'number' ? this.rows.nth(identifier) : this.getRow(identifier);
  106 |         await expect(row).toBeVisible({ timeout: 20_000 });
  107 |         const policyCell = row.locator('td').nth(6);
  108 |         await expect(policyCell).toBeVisible({ timeout: 20_000 });
  109 |         const pEl = policyCell.locator('p').first();
  110 |         await expect(pEl).toBeVisible({ timeout: 20_000 });
  111 |         const ariaLabel = await pEl.getAttribute('aria-label');
  112 |         if (ariaLabel && ariaLabel.trim().length > 0) {
  113 |             return ariaLabel.trim();
  114 |         }
  115 |         const text = await pEl.innerText();
  116 |         if (text && text.trim().length > 0) {
  117 |             return text.trim();
  118 |         }
  119 |         return (await policyCell.innerText()).trim();
  120 |     }
  121 | 
  122 |     async editEmployeePolicy(identifier) {
  123 |         const row = typeof identifier === 'number' ? this.rows.nth(identifier) : this.getRow(identifier);
  124 |         const editButton = row.locator('.table-view-action-edit, button[aria-label="Edit"]');
  125 |         await editButton.click();
  126 |     }
  127 | 
  128 |     async openUpdatePolicyDialog() {
  129 |         await expect(this.updatePolicyButton).toBeEnabled();
  130 |         await this.updatePolicyButton.click();
  131 |     }
  132 | 
  133 |     async selectDestinationPolicy(policyName) {
  134 |         const dialog = this.page.getByRole('dialog')
  135 |             .or(this.page.locator('.MuiDialog-container, .MuiMenu-paper, [role="menu"], .MuiPopover-paper'))
  136 |             .first();
  137 |         await expect(dialog).toBeVisible();
  138 | 
  139 |         const policySelect = dialog.getByRole('combobox')
  140 |             .or(dialog.locator('.MuiSelect-select, input[type="text"]'))
  141 |             .first();
  142 |         if (await policySelect.isVisible()) {
  143 |             await policySelect.click();
  144 |         }
  145 | 
  146 |         const option = this.page.getByRole('option', { name: policyName, exact: true })
  147 |             .or(this.page.getByRole('menuitem', { name: policyName, exact: true }))
  148 |             .or(dialog.getByText(policyName, { exact: true }));
  149 |         await option.click();
  150 | 
  151 |         const applyButton = dialog.getByRole('button', { name: /Update|Save|Apply|Confirm/i }).first();
  152 |         if (await applyButton.isVisible()) {
  153 |             await applyButton.click();
  154 |         }
  155 |     }
  156 | 
  157 |     async updatePolicyForSelected(policyName) {
  158 |         await this.openUpdatePolicyDialog();
  159 |         await this.selectDestinationPolicy(policyName);
  160 |     }
  161 | }
  162 | 
  163 | module.exports = TimeTrackingPolicyAllocationPage;
  164 | 
```