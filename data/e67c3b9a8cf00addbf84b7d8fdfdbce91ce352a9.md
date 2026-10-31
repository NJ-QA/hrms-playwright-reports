# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: timeTracking/timeTrackingSummary.spec.js >> Time Tracking Policy Summary (PIN-118) >> PIN_118_12 PIN_118_13 PIN_118_19 PIN_118_22 Configured limits and approvals appear in Summary after reload
- Location: tests/timeTracking/timeTrackingSummary.spec.js:53:5

# Error details

```
Error: expect(locator).toBeHidden() failed

Locator:  locator('[role="dialog"], .MuiDialog-paper, .modal-container').filter({ has: locator('.channels-list, input[name="name"], .policy-config-panel') }).first()
Expected: hidden
Received: visible
Timeout:  10000ms

Call log:
  - Expect "toBeHidden" with timeout 10000ms
  - waiting for locator('[role="dialog"], .MuiDialog-paper, .modal-container').filter({ has: locator('.channels-list, input[name="name"], .policy-config-panel') }).first()
    13 × locator resolved to <div role="dialog" aria-modal="true" aria-labelledby="«r1c»" class="MuiPaper-root MuiPaper-elevation MuiPaper-rounded MuiPaper-elevation24 MuiDialog-paper MuiDialog-paperScrollPaper MuiDialog-paperWidthSm MuiDialog-paperFullScreen css-1n3cxzf">…</div>
       - unexpected value "visible"

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
        - button "Messages 137" [ref=e32] [cursor=pointer]:
          - img [ref=e34]
          - generic [ref=e36]:
            - generic [ref=e37]: Messages
            - generic [ref=e38]: "137"
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
                - textbox "Search policies by name..." [active] [ref=e232]: QA Summary 0dde2f88
                - group
              - generic [ref=e234] [cursor=pointer]:
                - generic [ref=e235]:
                  - paragraph [ref=e236]:
                    - paragraph [ref=e237]: QA Summary 0dde2f88
                  - generic [ref=e239]: 0 Employees
                - generic:
                  - img
            - generic [ref=e241]:
              - generic [ref=e242]:
                - img
                - img
                - button [ref=e244] [cursor=pointer]:
                  - img [ref=e245]
                - generic [ref=e249]:
                  - heading "QA Summary 0dde2f88" [level=6] [ref=e251]
                  - paragraph [ref=e252]:
                    - text: "Description:"
                    - paragraph [ref=e253] [cursor=pointer]: Retained for Summary HTML capture - Web Remote WFH On Duty P...
                  - generic [ref=e254]:
                    - generic [ref=e255]: Capture Mode
                    - generic [ref=e256]:
                      - generic [ref=e257]:
                        - img [ref=e258]
                        - generic [ref=e260]: Web Clock-In
                      - generic [ref=e261]:
                        - img [ref=e262]
                        - generic [ref=e264]: Mobile Clock-In
                      - generic [ref=e265]:
                        - img [ref=e266]
                        - generic [ref=e268]: Remote Work
                      - generic [ref=e269]:
                        - img [ref=e270]
                        - generic [ref=e272]: Biometric
                - generic [ref=e274]: "Configured On: October 31, 2026"
              - generic [ref=e276]:
                - tablist [ref=e277]:
                  - tab "Summary" [selected] [ref=e278] [cursor=pointer]:
                    - generic [ref=e279]: Summary
                  - tab "Employees (0)" [ref=e280] [cursor=pointer]:
                    - generic [ref=e281]: Employees (0)
                - separator [ref=e282]
                - tabpanel [ref=e283]:
                  - generic [ref=e284]:
                    - generic [ref=e285]:
                      - generic [ref=e286]:
                        - img [ref=e288]
                        - heading "Work from home" [level=6] [ref=e291]
                      - generic [ref=e293]:
                        - generic [ref=e295]:
                          - generic [ref=e296]: WORK FROM HOME
                          - generic [ref=e297]:
                            - img [ref=e298]
                            - paragraph [ref=e300]: Allowed
                        - generic [ref=e302]:
                          - generic [ref=e303]: REQUESTS ALLOWED
                          - paragraph [ref=e304]: 5 days monthly
                        - generic [ref=e306]:
                          - generic [ref=e307]: APPROVAL REQUIRED
                          - generic [ref=e308]:
                            - img [ref=e309]
                            - paragraph [ref=e311]: "Yes"
                        - generic [ref=e313]:
                          - generic [ref=e314]: ALLOWED DAYS
                          - paragraph [ref=e315]: All Days
                    - generic [ref=e316]:
                      - generic [ref=e317]:
                        - img [ref=e319]
                        - heading "On Duty" [level=6] [ref=e321]
                      - generic [ref=e323]:
                        - generic [ref=e325]:
                          - generic [ref=e326]: ON DUTY
                          - generic [ref=e327]:
                            - img [ref=e328]
                            - paragraph [ref=e330]: Allowed
                        - generic [ref=e332]:
                          - generic [ref=e333]: REQUESTS ALLOWED
                          - paragraph [ref=e334]: 6 days monthly
                        - generic [ref=e336]:
                          - generic [ref=e337]: APPROVAL REQUIRED
                          - generic [ref=e338]:
                            - img [ref=e339]
                            - paragraph [ref=e341]: "Yes"
                    - generic [ref=e342]:
                      - generic [ref=e343]:
                        - img [ref=e345]
                        - heading "Partial Work Day" [level=6] [ref=e348]
                      - generic [ref=e350]:
                        - generic [ref=e352]:
                          - generic [ref=e353]: LATE ARRIVAL
                          - generic [ref=e354]:
                            - img [ref=e355]
                            - paragraph [ref=e357]: 120 mins per request
                        - generic [ref=e359]:
                          - generic [ref=e360]: EARLY LEAVING
                          - generic [ref=e361]:
                            - img [ref=e362]
                            - paragraph [ref=e364]: 60 mins per request
                        - generic [ref=e366]:
                          - generic [ref=e367]: INTERVENING TIME-OFF
                          - generic [ref=e368]:
                            - img [ref=e369]
                            - paragraph [ref=e371]: 75 mins per request
                        - generic [ref=e373]:
                          - generic [ref=e374]: REQUESTS ALLOWED
                          - paragraph [ref=e375]: 4 requests monthly
                        - generic [ref=e377]:
                          - generic [ref=e378]: APPROVAL REQUIRED
                          - generic [ref=e379]:
                            - img [ref=e380]
                            - paragraph [ref=e382]: "Yes"
  - generic [ref=e383]:
    - generic [ref=e384]:
      - heading "Theme & Style" [level=6] [ref=e385]
      - img [ref=e386] [cursor=pointer]
    - generic [ref=e388]:
      - generic [ref=e389]:
        - heading "Theme Mode" [level=6] [ref=e390]:
          - img [ref=e391]
          - text: Theme Mode
        - generic [ref=e393]:
          - button "Light" [ref=e394] [cursor=pointer]:
            - img [ref=e395]
            - text: Light
          - button "Dark" [ref=e397] [cursor=pointer]:
            - img [ref=e398]
            - text: Dark
          - button "Auto" [ref=e400] [cursor=pointer]:
            - img [ref=e401]
            - text: Auto
      - generic [ref=e403]:
        - heading "Theme Color" [level=6] [ref=e404]:
          - img [ref=e405]
          - text: Theme Color
        - generic [ref=e407]:
          - generic "Default" [ref=e408] [cursor=pointer]
          - generic "Orange" [ref=e410] [cursor=pointer]
          - generic "Marun" [ref=e412] [cursor=pointer]
          - generic "Blue" [ref=e414] [cursor=pointer]
          - generic "Green" [ref=e416] [cursor=pointer]
          - generic "Gray" [ref=e418] [cursor=pointer]
      - generic [ref=e420]:
        - heading "Dashboard Layout" [level=6] [ref=e421]
        - generic [ref=e422]:
          - button "Default" [ref=e423] [cursor=pointer]:
            - img [ref=e424]
            - text: Default
          - button "New Layout" [ref=e426] [cursor=pointer]:
            - img [ref=e427]
            - text: New Layout
  - generic [ref=e429]:
    - generic [ref=e430]:
      - heading "Change Password" [level=6] [ref=e431]
      - img [ref=e432] [cursor=pointer]
    - generic [ref=e434]:
      - generic [ref=e435]:
        - text: "You are currently logged in as:"
        - strong [ref=e436]: xperts_imaging@yopmail.com
        - generic [ref=e437]: Please enter your current password to verify your identity, then create a strong new password to keep your account secure.
      - alert [ref=e438]:
        - img [ref=e440]
        - generic [ref=e443]:
          - strong [ref=e444]: Security Notice
          - generic [ref=e445]: For your safety, you will be automatically logged out after a successful password change.
      - generic [ref=e446]:
        - generic [ref=e448]:
          - generic [ref=e449]:
            - generic [ref=e451]:
              - text: Old Password
              - generic [ref=e452]: "*"
            - textbox "Enter your current password" [ref=e454]
          - img [ref=e456] [cursor=pointer]
        - generic [ref=e459]:
          - generic [ref=e460]:
            - generic [ref=e462]:
              - text: New Password
              - generic [ref=e463]: "*"
            - textbox "Create a strong new password" [ref=e465]
          - img [ref=e467] [cursor=pointer]
        - generic [ref=e470]:
          - generic [ref=e471]:
            - generic [ref=e473]:
              - text: Confirm Password
              - generic [ref=e474]: "*"
            - textbox "Re-enter your new password" [disabled] [ref=e476]
          - img [ref=e478]
        - button "Update Password" [ref=e480] [cursor=pointer]
```

# Test source

```ts
  1   | const { expect } = require('@playwright/test');
  2   | const BaseModal = require('@pages/modals/base.modal');
  3   | const UnsavedPolicyChangesModal = require('./unsavedPolicyChanges.modal');
  4   | 
  5   | class TimeTrackingPolicyModal extends BaseModal {
  6   |     constructor(page) {
  7   |         super(page, page.locator('[role="dialog"], .MuiDialog-paper, .modal-container').filter({ has: page.locator('.channels-list, input[name="name"], .policy-config-panel') }).first());
  8   |         this.modalTitle = this.modal.getByText(/(?:Add|Edit)?\s*Time Tracking Policy|Edit Policy/i).first();
  9   |         this.nameInput = this.modal.locator('input[name="name"]');
  10  |         this.nameError = this.modal.getByText('Policy Name is required', { exact: true });
  11  |         this.descriptionInput = this.modal.locator('textarea[name="description"], input[name="description"], [placeholder*="description"]');
  12  |         this.helpPanel = this.modal.locator('.policy-help-panel, [class*="help"], .help-center-container, div').filter({ hasText: /Help Center|What is/i }).first();
  13  |         this.addMethodButton = this.modal.getByRole('button', { name: 'Add time tracking methods' });
  14  |         this.methodPicker = page.getByRole('menu').or(page.locator('.MuiMenu-paper, [role="menu"]')).first();
  15  |         this.configPanel = this.modal.locator('.policy-config-panel');
  16  |         this.webSwitch = this.configPanel.getByRole('switch');
  17  |         this.commentCheckbox = this.configPanel.getByRole('checkbox', {
  18  |             name: 'Comment is mandatory at the time of first clock-in'
  19  |         });
  20  |         this.networkCheckbox = this.configPanel.getByRole('checkbox', {
  21  |             name: 'Allow web clock-in only from the selected networks.'
  22  |         });
  23  |         this.networkSelector = this.configPanel.getByRole('combobox');
  24  |         this.networkError = this.configPanel.getByText('At least one network configuration must be selected', { exact: true });
  25  |         this.addNetworkLink = this.configPanel.locator('.ip-select-link');
  26  |         this.actionBar = this.modal.locator('#hrms-floating-bottom-bar, [id*="bottom-bar"], .action-bar');
  27  |         this.resetButton = this.modal.getByRole('button', { name: 'Reset' });
  28  |         this.saveButton = this.modal.getByRole('button', { name: /Save Time Tracking Policy|Save Policy/i })
  29  |             .or(page.locator('#hrms-floating-bottom-bar button:has-text("Save")'))
  30  |             .or(page.getByRole('button', { name: /Save Time Tracking Policy|Save Policy/i }))
  31  |             .first();
  32  |         this.unsavedChanges = new UnsavedPolicyChangesModal(page);
  33  |     }
  34  | 
  35  |     get closeButton() {
  36  |         return this.modal.getByRole('button', { name: 'close' });
  37  |     }
  38  | 
  39  |     method(name) {
  40  |         return this.modal.locator('.channels-list .channel-button').filter({ hasText: name });
  41  |     }
  42  | 
  43  |     async openMethod(name) {
  44  |         await this.method(name).click();
  45  |     }
  46  | 
  47  |     async setCaptureEnabled(name, enabled) {
  48  |         await this.openMethod(name);
  49  |         // Remote work includes child WFH and On-duty switches after its master switch.
  50  |         const toggle = this.configPanel.getByRole('switch').first();
  51  |         await toggle.setChecked(enabled);
  52  |         await expect(toggle).toBeChecked({ checked: enabled });
  53  |     }
  54  | 
  55  |     async addCaptureMethod(name) {
  56  |         await this.addMethodButton.click();
  57  |         await this.page.getByRole('menuitem', { name, exact: true }).click();
  58  |         await expect(this.method(name)).toBeVisible();
  59  |         await this.openMethod(name);
  60  |         const toggle = this.configPanel.getByRole('switch').first();
  61  |         if (!(await toggle.isChecked())) {
  62  |             await toggle.setChecked(true);
  63  |             await expect(toggle).toBeChecked();
  64  |         }
  65  |     }
  66  | 
  67  |     async closeSaved() {
  68  |         if (await this.actionBar.isVisible({ timeout: 2000 }).catch(() => false)) {
  69  |             await expect(this.actionBar).toBeHidden({ timeout: 10_000 }).catch(() => {});
  70  |         }
  71  |         await this.closeButton.click({ force: true });
> 72  |         await expect(this.modal).toBeHidden({ timeout: 10_000 });
      |                                  ^ Error: expect(locator).toBeHidden() failed
  73  |     }
  74  | 
  75  |     async openMethodPicker() {
  76  |         await this.addMethodButton.click();
  77  |         await expect(this.methodPicker).toBeVisible();
  78  |         return this.methodPicker;
  79  |     }
  80  | 
  81  |     async setWebEnabled(enabled) {
  82  |         await this.openMethod('Web clock-in');
  83  |         await this.webSwitch.setChecked(enabled);
  84  |         if (enabled) await expect(this.webSwitch).toBeChecked();
  85  |         else await expect(this.webSwitch).not.toBeChecked();
  86  |     }
  87  | 
  88  |     async save(name) {
  89  |         await this.nameInput.fill(name);
  90  |         await this.saveButton.click();
  91  |     }
  92  | 
  93  |     async openNetworkConfiguration() {
  94  |         const [newPage] = await Promise.all([
  95  |             this.page.waitForEvent('popup'),
  96  |             this.addNetworkLink.click()
  97  |         ]);
  98  |         await newPage.waitForLoadState('domcontentloaded');
  99  |         return newPage;
  100 |     }
  101 | 
  102 |     async requestClose() {
  103 |         await this.closeButton.click();
  104 |         const hasUnsaved = await this.unsavedChanges.modal.isVisible({ timeout: 2000 }).catch(() => false);
  105 |         if (hasUnsaved) {
  106 |             await this.unsavedChanges.verifyOpen();
  107 |             return this.unsavedChanges;
  108 |         }
  109 |         await expect(this.modal).toBeHidden({ timeout: 10000 });
  110 |         return {
  111 |             discard: async () => {},
  112 |             continueEditing: async () => {}
  113 |         };
  114 |     }
  115 | }
  116 | 
  117 | module.exports = TimeTrackingPolicyModal;
  118 | 
```