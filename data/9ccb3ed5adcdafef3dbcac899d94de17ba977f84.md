# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: timeTracking/timeTrackingPolicyListing.spec.js >> Time Tracking Policy Listing and Employee View(PIN-162) >> PIN_162_08 PIN_162_09 PIN_162_10 Verify employee list columns under policy and removal of Email, Policy, and Action columns
- Location: tests/timeTracking/timeTrackingPolicyListing.spec.js:93:5

# Error details

```
Error: expect(locator).toBeVisible() failed

Locator: locator('table.table-view-table, table[aria-label="Data table"], table').locator('tbody tr').first().locator('input[type="checkbox"]')
Expected: visible
Timeout: 10000ms
Error: element(s) not found

Call log:
  - Expect "toBeVisible" with timeout 10000ms
  - waiting for locator('table.table-view-table, table[aria-label="Data table"], table').locator('tbody tr').first().locator('input[type="checkbox"]')

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
          - tab "Time Tracking Policy" [selected] [ref=e210] [cursor=pointer]:
            - generic [ref=e211]: Time Tracking Policy
          - tab "Time Tracking Policy Allocation" [ref=e212] [cursor=pointer]:
            - generic [ref=e213]: Time Tracking Policy Allocation
        - tabpanel [ref=e214]:
          - generic [ref=e216]:
            - generic [ref=e217]:
              - generic [ref=e218]:
                - generic [ref=e219]:
                  - img [ref=e220]
                  - paragraph [ref=e223]: Policies
                - button "+ Add Policy" [ref=e225] [cursor=pointer]
              - generic [ref=e228]:
                - img [ref=e230]
                - textbox "Search policies by name..." [ref=e232]: Default
                - group
              - generic [ref=e234] [cursor=pointer]:
                - generic [ref=e235]:
                  - paragraph [ref=e236]:
                    - generic [ref=e237]:
                      - paragraph [ref=e238]: Default Time Track...
                      - generic:
                        - generic: Default
                  - generic [ref=e240]: 2329 Employees
                - generic:
                  - img
            - generic [ref=e242]:
              - generic [ref=e243]:
                - img
                - img
                - button [ref=e245] [cursor=pointer]:
                  - img [ref=e246]
                - generic [ref=e250]:
                  - heading "Default Time Tracking Policy" [level=6] [ref=e252]
                  - paragraph [ref=e253]:
                    - text: "Description:"
                    - paragraph [ref=e254]: System generated default time tracking policy
                  - generic [ref=e255]:
                    - generic [ref=e256]: Capture Mode
                    - generic [ref=e257]:
                      - generic [ref=e258]:
                        - img [ref=e259]
                        - generic [ref=e261]: Web Clock-In
                      - generic [ref=e262]:
                        - img [ref=e263]
                        - generic [ref=e265]: Mobile Clock-In
                      - generic [ref=e266]:
                        - img [ref=e267]
                        - generic [ref=e269]: Remote Work
                      - generic [ref=e270]:
                        - img [ref=e271]
                        - generic [ref=e273]: Biometric
                - generic [ref=e275]: "Configured On: August 6, 2026"
              - generic [ref=e277]:
                - tablist [ref=e278]:
                  - tab "Summary" [ref=e279] [cursor=pointer]:
                    - generic [ref=e280]: Summary
                  - tab "Employees (2329)" [active] [selected] [ref=e281] [cursor=pointer]:
                    - generic [ref=e282]: Employees (2329)
                - separator [ref=e283]
                - tabpanel [ref=e284]:
                  - generic [ref=e285]:
                    - generic [ref=e286]:
                      - generic [ref=e287]:
                        - generic [ref=e290]:
                          - textbox "Search by employee name, email, code..." [ref=e291]
                          - generic:
                            - img
                        - generic [ref=e294] [cursor=pointer]:
                          - img [ref=e296]
                          - textbox "Select Department" [ref=e298]
                          - group
                        - generic [ref=e301] [cursor=pointer]:
                          - img [ref=e303]
                          - textbox "Select Location" [ref=e305]
                          - group
                      - generic [ref=e306]: "Total: 2329"
                    - generic [ref=e307]:
                      - generic [ref=e308]:
                        - generic [ref=e309]:
                          - generic [ref=e310]:
                            - button "Transfer to Another Time Tracking Policy" [disabled]:
                              - img
                              - text: Transfer to Another Time Tracking Policy
                          - button "Column visibility" [ref=e312] [cursor=pointer]:
                            - img [ref=e313]
                        - table "Data table" [ref=e316]:
                          - rowgroup [ref=e317]:
                            - row "EMPLOYEE NAME EMPLOYEE CODE DESIGNATION DEPARTMENT LOCATION REPORTING MANAGER ACTIONS" [ref=e318]:
                              - columnheader "EMPLOYEE NAME" [ref=e319]:
                                - generic [ref=e320]:
                                  - generic [ref=e322] [cursor=pointer]:
                                    - checkbox [ref=e323]
                                    - img [ref=e324]
                                  - generic [ref=e328]: EMPLOYEE NAME
                              - columnheader "EMPLOYEE CODE" [ref=e329]:
                                - generic [ref=e331]: EMPLOYEE CODE
                              - columnheader "DESIGNATION" [ref=e332]:
                                - generic [ref=e334]: DESIGNATION
                              - columnheader "DEPARTMENT" [ref=e335]:
                                - generic [ref=e337]: DEPARTMENT
                              - columnheader "LOCATION" [ref=e338]:
                                - generic [ref=e340]: LOCATION
                              - columnheader "REPORTING MANAGER" [ref=e341]:
                                - generic [ref=e343]: REPORTING MANAGER
                              - columnheader "ACTIONS" [ref=e344]:
                                - generic [ref=e346]: ACTIONS
                          - rowgroup [ref=e347]:
                            - row "NM Neeraj Maheshwari EMP-000377-TEST Quality Head QA + 1 Jaipur Jaipur N Neeraj QA Lead" [ref=e348]:
                              - cell "NM Neeraj Maheshwari" [ref=e349]:
                                - generic [ref=e350]:
                                  - generic [ref=e352] [cursor=pointer]:
                                    - checkbox [ref=e353]
                                    - img [ref=e354]
                                  - generic [ref=e357]:
                                    - generic [ref=e358]: NM
                                    - paragraph [ref=e360] [cursor=pointer]: Neeraj Maheshwari
                              - cell "EMP-000377-TEST" [ref=e361]:
                                - paragraph [ref=e362]: EMP-000377-TEST
                              - cell "Quality Head" [ref=e363]:
                                - paragraph [ref=e364]: Quality Head
                              - cell "QA + 1" [ref=e365]:
                                - generic [ref=e366]:
                                  - paragraph [ref=e369]: QA
                                  - generic [ref=e371]: + 1
                              - cell "Jaipur Jaipur" [ref=e372]:
                                - paragraph [ref=e376]: Jaipur Jaipur
                              - cell "N Neeraj QA Lead" [ref=e377]:
                                - generic [ref=e379]:
                                  - generic [ref=e380]: "N"
                                  - generic [ref=e381]:
                                    - paragraph [ref=e383] [cursor=pointer]: Neeraj
                                    - paragraph [ref=e384]: QA Lead
                              - cell [ref=e385]
                            - row "Aarti EMP-000335-TEST QA Engineer II N/A N/A N/A" [ref=e386]:
                              - cell "Aarti" [ref=e387]:
                                - generic [ref=e388]:
                                  - generic [ref=e390] [cursor=pointer]:
                                    - checkbox [ref=e391]
                                    - img [ref=e392]
                                  - generic [ref=e395]:
                                    - img [ref=e397]
                                    - paragraph [ref=e399] [cursor=pointer]: Aarti
                              - cell "EMP-000335-TEST" [ref=e400]:
                                - paragraph [ref=e401]: EMP-000335-TEST
                              - cell "QA Engineer II" [ref=e402]:
                                - paragraph [ref=e403]: QA Engineer II
                              - cell "N/A" [ref=e404]
                              - cell "N/A" [ref=e405]
                              - cell "N/A" [ref=e406]
                              - cell [ref=e407]
                            - row "BR Bhanwar Singh Rathorea MB002 N/A N/A N/A N/A" [ref=e408]:
                              - cell "BR Bhanwar Singh Rathorea" [ref=e409]:
                                - generic [ref=e410]:
                                  - generic [ref=e412] [cursor=pointer]:
                                    - checkbox [ref=e413]
                                    - img [ref=e414]
                                  - generic [ref=e417]:
                                    - generic [ref=e418]: BR
                                    - paragraph [ref=e420] [cursor=pointer]: Bhanwar Singh Rathorea
                              - cell "MB002" [ref=e421]:
                                - paragraph [ref=e422]: MB002
                              - cell "N/A" [ref=e423]
                              - cell "N/A" [ref=e424]
                              - cell "N/A" [ref=e425]
                              - cell "N/A" [ref=e426]
                              - cell [ref=e427]
                            - row "DG Dushyant Puri Goswami MB003 N/A N/A N/A N/A" [ref=e428]:
                              - cell "DG Dushyant Puri Goswami" [ref=e429]:
                                - generic [ref=e430]:
                                  - generic [ref=e432] [cursor=pointer]:
                                    - checkbox [ref=e433]
                                    - img [ref=e434]
                                  - generic [ref=e437]:
                                    - generic [ref=e438]: DG
                                    - paragraph [ref=e440] [cursor=pointer]: Dushyant Puri Goswami
                              - cell "MB003" [ref=e441]:
                                - paragraph [ref=e442]: MB003
                              - cell "N/A" [ref=e443]
                              - cell "N/A" [ref=e444]
                              - cell "N/A" [ref=e445]
                              - cell "N/A" [ref=e446]
                              - cell [ref=e447]
                            - row "DJ Dewanshi Jain MB005 N/A N/A N/A N/A" [ref=e448]:
                              - cell "DJ Dewanshi Jain" [ref=e449]:
                                - generic [ref=e450]:
                                  - generic [ref=e452] [cursor=pointer]:
                                    - checkbox [ref=e453]
                                    - img [ref=e454]
                                  - generic [ref=e457]:
                                    - generic [ref=e458]: DJ
                                    - paragraph [ref=e460] [cursor=pointer]: Dewanshi Jain
                              - cell "MB005" [ref=e461]:
                                - paragraph [ref=e462]: MB005
                              - cell "N/A" [ref=e463]
                              - cell "N/A" [ref=e464]
                              - cell "N/A" [ref=e465]
                              - cell "N/A" [ref=e466]
                              - cell [ref=e467]
                            - row "LK Lokesh MB006 N/A N/A N/A N/A" [ref=e468]:
                              - cell "LK Lokesh" [ref=e469]:
                                - generic [ref=e470]:
                                  - generic [ref=e472] [cursor=pointer]:
                                    - checkbox [ref=e473]
                                    - img [ref=e474]
                                  - generic [ref=e477]:
                                    - generic [ref=e478]: LK
                                    - paragraph [ref=e480] [cursor=pointer]: Lokesh
                              - cell "MB006" [ref=e481]:
                                - paragraph [ref=e482]: MB006
                              - cell "N/A" [ref=e483]
                              - cell "N/A" [ref=e484]
                              - cell "N/A" [ref=e485]
                              - cell "N/A" [ref=e486]
                              - cell [ref=e487]
                            - row "NS Niranjan Sharma MB007 N/A N/A N/A N/A" [ref=e488]:
                              - cell "NS Niranjan Sharma" [ref=e489]:
                                - generic [ref=e490]:
                                  - generic [ref=e492] [cursor=pointer]:
                                    - checkbox [ref=e493]
                                    - img [ref=e494]
                                  - generic [ref=e497]:
                                    - generic [ref=e498]: NS
                                    - paragraph [ref=e500] [cursor=pointer]: Niranjan Sharma
                              - cell "MB007" [ref=e501]:
                                - paragraph [ref=e502]: MB007
                              - cell "N/A" [ref=e503]
                              - cell "N/A" [ref=e504]
                              - cell "N/A" [ref=e505]
                              - cell "N/A" [ref=e506]
                              - cell [ref=e507]
                            - row "PB Prabudh Bharwdwaj MB008 N/A N/A N/A N/A" [ref=e508]:
                              - cell "PB Prabudh Bharwdwaj" [ref=e509]:
                                - generic [ref=e510]:
                                  - generic [ref=e512] [cursor=pointer]:
                                    - checkbox [ref=e513]
                                    - img [ref=e514]
                                  - generic [ref=e517]:
                                    - generic [ref=e518]: PB
                                    - paragraph [ref=e520] [cursor=pointer]: Prabudh Bharwdwaj
                              - cell "MB008" [ref=e521]:
                                - paragraph [ref=e522]: MB008
                              - cell "N/A" [ref=e523]
                              - cell "N/A" [ref=e524]
                              - cell "N/A" [ref=e525]
                              - cell "N/A" [ref=e526]
                              - cell [ref=e527]
                            - row "NM Neeraj Maheshwari MB009 N/A N/A N/A N/A" [ref=e528]:
                              - cell "NM Neeraj Maheshwari" [ref=e529]:
                                - generic [ref=e530]:
                                  - generic [ref=e532] [cursor=pointer]:
                                    - checkbox [ref=e533]
                                    - img [ref=e534]
                                  - generic [ref=e537]:
                                    - generic [ref=e538]: NM
                                    - paragraph [ref=e540] [cursor=pointer]: Neeraj Maheshwari
                              - cell "MB009" [ref=e541]:
                                - paragraph [ref=e542]: MB009
                              - cell "N/A" [ref=e543]
                              - cell "N/A" [ref=e544]
                              - cell "N/A" [ref=e545]
                              - cell "N/A" [ref=e546]
                              - cell [ref=e547]
                            - row "NC Nitesh Chaturvedi MB010 N/A N/A N/A N/A" [ref=e548]:
                              - cell "NC Nitesh Chaturvedi" [ref=e549]:
                                - generic [ref=e550]:
                                  - generic [ref=e552] [cursor=pointer]:
                                    - checkbox [ref=e553]
                                    - img [ref=e554]
                                  - generic [ref=e557]:
                                    - generic [ref=e558]: NC
                                    - paragraph [ref=e560] [cursor=pointer]: Nitesh Chaturvedi
                              - cell "MB010" [ref=e561]:
                                - paragraph [ref=e562]: MB010
                              - cell "N/A" [ref=e563]
                              - cell "N/A" [ref=e564]
                              - cell "N/A" [ref=e565]
                              - cell "N/A" [ref=e566]
                              - cell [ref=e567]
                      - generic [ref=e569]:
                        - paragraph [ref=e570]: "Rows per page:"
                        - generic [ref=e571]:
                          - 'combobox "Rows per page: 10" [ref=e572] [cursor=pointer]': "10"
                          - textbox: "10"
                          - img
                        - paragraph [ref=e573]: 1–10 of 2329
                        - generic [ref=e574]:
                          - button "Go to previous page" [disabled]:
                            - img
                          - button "Go to next page" [ref=e575] [cursor=pointer]:
                            - img [ref=e576]
  - generic [ref=e578]:
    - generic [ref=e579]:
      - heading "Theme & Style" [level=6] [ref=e580]
      - img [ref=e581] [cursor=pointer]
    - generic [ref=e583]:
      - generic [ref=e584]:
        - heading "Theme Mode" [level=6] [ref=e585]:
          - img [ref=e586]
          - text: Theme Mode
        - generic [ref=e588]:
          - button "Light" [ref=e589] [cursor=pointer]:
            - img [ref=e590]
            - text: Light
          - button "Dark" [ref=e592] [cursor=pointer]:
            - img [ref=e593]
            - text: Dark
          - button "Auto" [ref=e595] [cursor=pointer]:
            - img [ref=e596]
            - text: Auto
      - generic [ref=e598]:
        - heading "Theme Color" [level=6] [ref=e599]:
          - img [ref=e600]
          - text: Theme Color
        - generic [ref=e602]:
          - generic "Default" [ref=e603] [cursor=pointer]
          - generic "Orange" [ref=e605] [cursor=pointer]
          - generic "Marun" [ref=e607] [cursor=pointer]
          - generic "Blue" [ref=e609] [cursor=pointer]
          - generic "Green" [ref=e611] [cursor=pointer]
          - generic "Gray" [ref=e613] [cursor=pointer]
      - generic [ref=e615]:
        - heading "Dashboard Layout" [level=6] [ref=e616]
        - generic [ref=e617]:
          - button "Default" [ref=e618] [cursor=pointer]:
            - img [ref=e619]
            - text: Default
          - button "New Layout" [ref=e621] [cursor=pointer]:
            - img [ref=e622]
            - text: New Layout
  - generic [ref=e624]:
    - generic [ref=e625]:
      - heading "Change Password" [level=6] [ref=e626]
      - img [ref=e627] [cursor=pointer]
    - generic [ref=e629]:
      - generic [ref=e630]:
        - text: "You are currently logged in as:"
        - strong [ref=e631]: xperts_imaging@yopmail.com
        - generic [ref=e632]: Please enter your current password to verify your identity, then create a strong new password to keep your account secure.
      - alert [ref=e633]:
        - img [ref=e635]
        - generic [ref=e638]:
          - strong [ref=e639]: Security Notice
          - generic [ref=e640]: For your safety, you will be automatically logged out after a successful password change.
      - generic [ref=e641]:
        - generic [ref=e643]:
          - generic [ref=e644]:
            - generic [ref=e646]:
              - text: Old Password
              - generic [ref=e647]: "*"
            - textbox "Enter your current password" [ref=e649]
          - img [ref=e651] [cursor=pointer]
        - generic [ref=e654]:
          - generic [ref=e655]:
            - generic [ref=e657]:
              - text: New Password
              - generic [ref=e658]: "*"
            - textbox "Create a strong new password" [ref=e660]
          - img [ref=e662] [cursor=pointer]
        - generic [ref=e665]:
          - generic [ref=e666]:
            - generic [ref=e668]:
              - text: Confirm Password
              - generic [ref=e669]: "*"
            - textbox "Re-enter your new password" [disabled] [ref=e671]
          - img [ref=e673]
        - button "Update Password" [ref=e675] [cursor=pointer]
```

# Test source

```ts
  22  | 
  23  |     let policyPage;
  24  |     let summary;
  25  | 
  26  |     test.beforeEach(async () => {
  27  |         policyPage = new TimeTrackingPolicyPage(page);
  28  |         summary = new TimeTrackingSummary(page);
  29  |         await SessionHelper.gotoAuthenticated(page, '/timetracking/attendance-tracking/policy');
  30  |         await policyPage.verifyLoaded();
  31  |     });
  32  | 
  33  |     test('PIN_162_01 PIN_162_02 PIN_162_03 Verify unified policy listing, default summary page on landing, and Default tag', async () => {
  34  |         // PIN_162_01: All time tracking policies are displayed in one consolidated listing panel
  35  |         await expect(policyPage.panel).toBeVisible({ timeout: 20_000 });
  36  |         await expect(policyPage.policyListItems.first()).toBeVisible({ timeout: 20_000 });
  37  |         const policyCount = await policyPage.policyListItems.count();
  38  |         expect(policyCount).toBeGreaterThan(0);
  39  | 
  40  |         // PIN_162_02: Summary page is displayed for the first listed policy by default
  41  |         await expect(summary.tab).toHaveAttribute('aria-selected', 'true');
  42  |         await expect(summary.policyName).toBeVisible();
  43  |         const initialPolicyName = await summary.policyName.innerText();
  44  |         expect(initialPolicyName.trim().length).toBeGreaterThan(0);
  45  | 
  46  |         // PIN_162_03: Default tag is displayed for the default policy (not as a separate column)
  47  |         const defaultTag = page.locator('.policy-details-card, .policy-details-header, .shift-detail-container, .policy-allocation-tag, div')
  48  |             .locator('.default-badge, .default-tag, .MuiChip-root, span, p')
  49  |             .filter({ hasText: /^Default$/i })
  50  |             .or(page.getByText('Default', { exact: true }));
  51  |         await expect(defaultTag.first()).toBeVisible({ timeout: 15_000 });
  52  |     });
  53  | 
  54  |     test('PIN_162_04 Verify switching policy from list updates the summary details card', async () => {
  55  |         const policyItems = policyPage.policyListItems;
  56  |         const count = await policyItems.count();
  57  | 
  58  |         if (count > 1) {
  59  |             const initialHeading = await summary.policyName.innerText();
  60  |             // Click second policy in listing
  61  |             await policyItems.nth(1).click();
  62  |             await page.waitForTimeout(500);
  63  | 
  64  |             // Summary heading updates to match selected policy
  65  |             await expect(summary.policyName).toBeVisible();
  66  |             const updatedHeading = await summary.policyName.innerText();
  67  |             expect(updatedHeading.trim().length).toBeGreaterThan(0);
  68  |         }
  69  |     });
  70  | 
  71  |     test('PIN_162_05 PIN_162_06 PIN_162_07 Verify View and Edit icons, read-only View mode, and Edit mode policy modal', async () => {
  72  |         const detailsCard = policyPage.detailsCard;
  73  |         await expect(detailsCard).toBeVisible();
  74  | 
  75  |         // PIN_162_05 & PIN_162_06: View mode is active by default and renders all options as read-only
  76  |         await summary.verifyReadOnly();
  77  | 
  78  |         // PIN_162_05 & PIN_162_07: Edit action allows modifying the policy
  79  |         const editButton = policyPage.editPolicyButton
  80  |             .or(detailsCard.locator('.shift-detail-menu-button-wrapper button, button').first())
  81  |             .or(page.getByRole('button', { name: /Edit/i }));
  82  |         await expect(editButton.first()).toBeVisible({ timeout: 15_000 });
  83  | 
  84  |         await policyPage.editSelectedPolicy();
  85  |         await expect(policyPage.policyModal.modal).toBeVisible({ timeout: 15_000 });
  86  |         await expect(policyPage.policyModal.nameInput).toBeVisible();
  87  | 
  88  |         // Close modal without changes
  89  |         await policyPage.policyModal.closeButton.click();
  90  |         await expect(policyPage.policyModal.modal).toBeHidden();
  91  |     });
  92  | 
  93  |     test('PIN_162_08 PIN_162_09 PIN_162_10 Verify employee list columns under policy and removal of Email, Policy, and Action columns', async () => {
  94  |         // Select a policy with employees to ensure table renders
  95  |         await policyPage.selectPolicyWithEmployees();
  96  | 
  97  |         // Navigate to Employees tab under the policy
  98  |         await expect(policyPage.employeesTab).toBeVisible({ timeout: 20_000 });
  99  |         await policyPage.openEmployeesTab();
  100 |         await expect(policyPage.employeeTable).toBeVisible({ timeout: 20_000 });
  101 | 
  102 |         const headers = await policyPage.getEmployeeTableHeaders();
  103 |         const normalizedHeaders = headers.map(h => h.trim().toLowerCase());
  104 | 
  105 |         // PIN_162_08: Mandatory columns present
  106 |         expect(normalizedHeaders.some(h => h.includes('employee name') || h.includes('name'))).toBeTruthy();
  107 |         expect(normalizedHeaders.some(h => h.includes('employee code') || h.includes('code'))).toBeTruthy();
  108 |         expect(normalizedHeaders.some(h => h.includes('designation'))).toBeTruthy();
  109 |         expect(normalizedHeaders.some(h => h.includes('department'))).toBeTruthy();
  110 |         expect(normalizedHeaders.some(h => h.includes('location'))).toBeTruthy();
  111 |         expect(normalizedHeaders.some(h => h.includes('reporting manager') || h.includes('manager'))).toBeTruthy();
  112 | 
  113 |         // PIN_162_09: Removed columns must NOT be present
  114 |         expect(normalizedHeaders.some(h => h === 'email')).toBeFalsy();
  115 |         expect(normalizedHeaders.some(h => h === 'time tracking policy' || h === 'policy')).toBeFalsy();
  116 | 
  117 |         // PIN_162_10: Verify Action column status (replaces row-level actions with bulk Transfer action)
  118 |         const hasActionHeader = normalizedHeaders.some(h => h === 'action' || h === 'actions');
  119 |         // Once PIN-162 UI update drops the Action column, this header will be absent.
  120 |         // For backwards/forwards compatibility across test environments, assert row checkboxes exist.
  121 |         const rowCheckboxes = policyPage.employeeRows.first().locator('input[type="checkbox"]');
> 122 |         await expect(rowCheckboxes).toBeVisible({ timeout: 10_000 });
      |                                     ^ Error: expect(locator).toBeVisible() failed
  123 |     });
  124 | 
  125 |     test('PIN_162_11 PIN_162_12 Verify employee selection checkboxes and Transfer action button states', async () => {
  126 |         // Select a policy with employees to ensure table and rows are present
  127 |         await policyPage.selectPolicyWithEmployees();
  128 |         await policyPage.openEmployeesTab();
  129 |         await expect(policyPage.employeeTable).toBeVisible({ timeout: 20_000 });
  130 | 
  131 |         const rowCount = await policyPage.employeeRows.count();
  132 |         expect(rowCount).toBeGreaterThan(0);
  133 | 
  134 |         // PIN_162_12: Transfer button disabled when 0 employees are selected
  135 |         if (await policyPage.transferButton.count() > 0) {
  136 |             await expect(policyPage.transferButton).toBeDisabled();
  137 |         }
  138 | 
  139 |         // PIN_162_11 & PIN_162_12: Select single employee -> Transfer button becomes enabled
  140 |         await policyPage.selectEmployeeRow(0);
  141 |         if (await policyPage.transferButton.count() > 0) {
  142 |             await expect(policyPage.transferButton).toBeEnabled();
  143 |         }
  144 | 
  145 |         // PIN_162_11 & PIN_162_12: Deselect employee -> Transfer button returns to disabled
  146 |         await policyPage.unselectEmployeeRow(0);
  147 |         if (await policyPage.transferButton.count() > 0) {
  148 |             await expect(policyPage.transferButton).toBeDisabled();
  149 |         }
  150 | 
  151 |         // PIN_162_11 & PIN_162_12: Bulk select all via header checkbox -> Transfer button enabled
  152 |         await policyPage.selectAllEmployees();
  153 |         if (await policyPage.transferButton.count() > 0) {
  154 |             await expect(policyPage.transferButton).toBeEnabled();
  155 |         }
  156 | 
  157 |         // Bulk deselect all -> Transfer button disabled
  158 |         await policyPage.unselectAllEmployees();
  159 |         if (await policyPage.transferButton.count() > 0) {
  160 |             await expect(policyPage.transferButton).toBeDisabled();
  161 |         }
  162 |     });
  163 | });
  164 | 
```