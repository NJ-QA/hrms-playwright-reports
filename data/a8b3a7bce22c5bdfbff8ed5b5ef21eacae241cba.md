# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: exit/taskTemplates.spec.js >> PIN-142: System Task Library (Exit & Onboarding) Matrix >> PIN_142_03 Verify task library columns and predefined Exit tasks
- Location: tests/exit/taskTemplates.spec.js:97:5

# Error details

```
Error: NAME OF TASK column should be displayed

expect(locator).toBeVisible() failed

Locator: getByRole('dialog').getByText('NAME OF TASK', { exact: true }).first()
Expected: visible
Timeout: 9000ms
Error: element(s) not found

Call log:
  - NAME OF TASK column should be displayed with timeout 9000ms
  - waiting for getByRole('dialog').getByText('NAME OF TASK', { exact: true }).first()

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
              - generic [ref=e38]: "59"
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
        - generic [ref=e144]: Good Evening Neeraj !
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
              - generic [ref=e163]: "2"
          - button [ref=e165] [cursor=pointer]:
            - img [ref=e166]
          - button [ref=e169] [cursor=pointer]:
            - img [ref=e171]
            - generic [ref=e178]: EN
            - img [ref=e179]
          - generic [ref=e182] [cursor=pointer]:
            - img [ref=e184]
            - generic [ref=e185]:
              - generic [ref=e186]: Neeraj
              - generic [ref=e187]: xperts_imaging@yopmail.com
      - generic [ref=e189]:
        - generic [ref=e190]:
          - tablist [ref=e191]:
            - tab [ref=e192] [cursor=pointer]:
              - generic [ref=e193]: Dashboard
            - tab [ref=e194] [cursor=pointer]:
              - generic [ref=e195]: Employee Management
            - tab [ref=e196] [cursor=pointer]:
              - generic [ref=e197]: Organization Structure
            - tab [ref=e198] [cursor=pointer]:
              - generic [ref=e199]: Onboarding
            - tab [selected] [ref=e200] [cursor=pointer]:
              - generic [ref=e201]: Exit
            - tab [ref=e202] [cursor=pointer]:
              - generic [ref=e203]: Hiring
            - tab [ref=e204] [cursor=pointer]:
              - generic [ref=e205]: Documents
            - tab [ref=e206] [cursor=pointer]:
              - generic [ref=e207]: Expenses & Travel
            - tab [ref=e208] [cursor=pointer]:
              - generic [ref=e209]: Settings
          - separator [ref=e210]
        - generic [ref=e212]:
          - tablist [ref=e213]:
            - tab [ref=e214] [cursor=pointer]:
              - generic [ref=e215]: Exit Summary
            - tab [ref=e216] [cursor=pointer]:
              - generic [ref=e217]: Exit Process
            - tab [ref=e218] [cursor=pointer]:
              - generic [ref=e219]: Reverted Exits
            - tab [ref=e220] [cursor=pointer]:
              - generic [ref=e221]: Task Tracking
            - tab [selected] [ref=e222] [cursor=pointer]:
              - generic [ref=e223]: Task Templates
            - tab [ref=e224] [cursor=pointer]:
              - generic [ref=e225]: Bulk Actions
            - tab [ref=e226] [cursor=pointer]:
              - generic [ref=e227]: Exit Survey
            - tab [ref=e228] [cursor=pointer]:
              - generic [ref=e229]: Settings
          - tabpanel [ref=e230]:
            - generic [ref=e231]:
              - generic [ref=e233]:
                - heading [level=3] [ref=e234]: Exit Task Templates
                - paragraph [ref=e235]: Manage and organize exit task templates by task lists.
              - generic [ref=e236]:
                - generic [ref=e237]:
                  - generic [ref=e238]:
                    - generic [ref=e239]:
                      - img [ref=e240]
                      - paragraph [ref=e242]: Task Lists
                    - button [ref=e244] [cursor=pointer]: + Add Task List
                  - generic [ref=e247]:
                    - img [ref=e249]
                    - textbox [ref=e251]:
                      - /placeholder: Search task lists...
                    - group
                  - generic [ref=e252]:
                    - generic [ref=e253] [cursor=pointer]:
                      - generic [ref=e254]:
                        - paragraph [ref=e255]: Auto List
                        - generic [ref=e257]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e258] [cursor=pointer]:
                      - generic [ref=e259]:
                        - paragraph [ref=e260]: Checkbox List
                        - generic [ref=e262]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e263] [cursor=pointer]:
                      - generic [ref=e264]:
                        - paragraph [ref=e265]: PIN142_RepeatSelection_1791872...
                        - generic [ref=e267]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e268] [cursor=pointer]:
                      - generic [ref=e269]:
                        - paragraph [ref=e270]: PIN142_RepeatSelection_1791872...
                        - generic [ref=e272]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e273] [cursor=pointer]:
                      - generic [ref=e274]:
                        - paragraph [ref=e275]: PIN142_RepeatSelection_1791872...
                        - generic [ref=e277]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e278] [cursor=pointer]:
                      - generic [ref=e279]:
                        - paragraph [ref=e280]: PIN142_Library_1791872684097
                        - generic [ref=e282]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e283] [cursor=pointer]:
                      - generic [ref=e284]:
                        - paragraph [ref=e285]: PIN142_Library_1791872729414
                        - generic [ref=e287]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e288] [cursor=pointer]:
                      - generic [ref=e289]:
                        - paragraph [ref=e290]: PIN142_Library_1791872779238
                        - generic [ref=e292]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e293] [cursor=pointer]:
                      - generic [ref=e294]:
                        - paragraph [ref=e295]: PIN142_Library_1791872819444
                        - generic [ref=e297]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e298] [cursor=pointer]:
                      - generic [ref=e299]:
                        - paragraph [ref=e300]: PIN142_Library_1791873032796
                        - generic [ref=e302]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e303] [cursor=pointer]:
                      - generic [ref=e304]:
                        - paragraph [ref=e305]: PIN142_Library_1791873064065
                        - generic [ref=e307]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e308] [cursor=pointer]:
                      - generic [ref=e309]:
                        - paragraph [ref=e310]: PIN142_Library_1791873102804
                        - generic [ref=e312]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e313] [cursor=pointer]:
                      - generic [ref=e314]:
                        - paragraph [ref=e315]: PIN142_Library_1791873131538
                        - generic [ref=e317]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e318] [cursor=pointer]:
                      - generic [ref=e319]:
                        - paragraph [ref=e320]: PIN142_MultipleTemplates_17918...
                        - generic [ref=e322]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e323] [cursor=pointer]:
                      - generic [ref=e324]:
                        - paragraph [ref=e325]: PIN142_Checkbox_1791873396827
                        - generic [ref=e327]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e328] [cursor=pointer]:
                      - generic [ref=e329]:
                        - paragraph [ref=e330]: PIN142_RepeatSelection_1791873...
                        - generic [ref=e332]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e333] [cursor=pointer]:
                      - generic [ref=e334]:
                        - paragraph [ref=e335]: PIN142_RepeatSelection_1791877...
                        - generic [ref=e337]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e338] [cursor=pointer]:
                      - generic [ref=e339]:
                        - paragraph [ref=e340]: PIN142_Library_1791877717234
                        - generic [ref=e342]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e343] [cursor=pointer]:
                      - generic [ref=e344]:
                        - paragraph [ref=e345]: PIN142_Library_1791877725942
                        - generic [ref=e347]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e348] [cursor=pointer]:
                      - generic [ref=e349]:
                        - paragraph [ref=e350]: PIN142_Library_1791877734139
                        - generic [ref=e352]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e353] [cursor=pointer]:
                      - generic [ref=e354]:
                        - paragraph [ref=e355]: PIN142_Library_1791877742654
                        - generic [ref=e357]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e358] [cursor=pointer]:
                      - generic [ref=e359]:
                        - paragraph [ref=e360]: PIN142_MultipleTemplates_17918...
                        - generic [ref=e362]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e363] [cursor=pointer]:
                      - generic [ref=e364]:
                        - paragraph [ref=e365]: PIN142_Checkbox_1791877800119
                        - generic [ref=e367]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e368] [cursor=pointer]:
                      - generic [ref=e369]:
                        - paragraph [ref=e370]: PIN142_RepeatSelection_1791877...
                        - generic [ref=e372]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e373] [cursor=pointer]:
                      - generic [ref=e374]:
                        - paragraph [ref=e375]: PIN142_Library_1791878246523
                        - generic [ref=e377]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e378] [cursor=pointer]:
                      - generic [ref=e379]:
                        - paragraph [ref=e380]: PIN142_RepeatSelection_1791878...
                        - generic [ref=e382]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e383] [cursor=pointer]:
                      - generic [ref=e384]:
                        - paragraph [ref=e385]: PIN142_RepeatSelection_1791878...
                        - generic [ref=e387]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e388] [cursor=pointer]:
                      - generic [ref=e389]:
                        - paragraph [ref=e390]: PIN142_Library_1791878496711
                        - generic [ref=e392]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e393] [cursor=pointer]:
                      - generic [ref=e394]:
                        - paragraph [ref=e395]: PIN142_Library_1791878531989
                        - generic [ref=e397]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e398] [cursor=pointer]:
                      - generic [ref=e399]:
                        - paragraph [ref=e400]: PIN142_MultipleTemplates_17918...
                        - generic [ref=e402]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e403] [cursor=pointer]:
                      - generic [ref=e404]:
                        - paragraph [ref=e405]: PIN142_Checkbox_1791878620237
                        - generic [ref=e407]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e408] [cursor=pointer]:
                      - generic [ref=e409]:
                        - paragraph [ref=e410]: PIN142_RepeatSelection_1791878...
                        - generic [ref=e412]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e413] [cursor=pointer]:
                      - generic [ref=e414]:
                        - paragraph [ref=e415]: PIN142_Library_1791878871678
                        - generic [ref=e417]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e418] [cursor=pointer]:
                      - generic [ref=e419]:
                        - paragraph [ref=e420]: PIN142_Library_1791878979261
                        - generic [ref=e422]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e423] [cursor=pointer]:
                      - generic [ref=e424]:
                        - paragraph [ref=e425]: PIN142_MultipleTemplates_17918...
                        - generic [ref=e427]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e428] [cursor=pointer]:
                      - generic [ref=e429]:
                        - paragraph [ref=e430]: PIN142_RepeatSelection_1791879...
                        - generic [ref=e432]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e433] [cursor=pointer]:
                      - generic [ref=e434]:
                        - paragraph [ref=e435]: PIN142_Library_1791879623484
                        - generic [ref=e437]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e438] [cursor=pointer]:
                      - generic [ref=e439]:
                        - paragraph [ref=e440]: PIN142_MultipleTemplates_17918...
                        - generic [ref=e442]: 3 Task Templates
                      - generic:
                        - img
                    - generic [ref=e443] [cursor=pointer]:
                      - generic [ref=e444]:
                        - paragraph [ref=e445]: PIN142_RepeatSelection_1791879...
                        - generic [ref=e447]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e448] [cursor=pointer]:
                      - generic [ref=e449]:
                        - paragraph [ref=e450]: PIN142_Library_1791879877695
                        - generic [ref=e452]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e453] [cursor=pointer]:
                      - generic [ref=e454]:
                        - paragraph [ref=e455]: PIN142_MultipleTemplates_17918...
                        - generic [ref=e457]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e458] [cursor=pointer]:
                      - generic [ref=e459]:
                        - paragraph [ref=e460]: PIN142_Checkbox_1791879983084
                        - generic [ref=e462]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e463] [cursor=pointer]:
                      - generic [ref=e464]:
                        - paragraph [ref=e465]: PIN142_RepeatSelection_1791879...
                        - generic [ref=e467]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e468] [cursor=pointer]:
                      - generic [ref=e469]:
                        - paragraph [ref=e470]: PIN142_Library_1791880409167
                        - generic [ref=e472]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e473] [cursor=pointer]:
                      - generic [ref=e474]:
                        - paragraph [ref=e475]: PIN142_Library_1791880549741
                        - generic [ref=e477]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e478] [cursor=pointer]:
                      - generic [ref=e479]:
                        - paragraph [ref=e480]: PIN142_Library_1791880583073
                        - generic [ref=e482]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e483] [cursor=pointer]:
                      - generic [ref=e484]:
                        - paragraph [ref=e485]: PIN142_Library_1791880704053
                        - generic [ref=e487]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e488] [cursor=pointer]:
                      - generic [ref=e489]:
                        - paragraph [ref=e490]: PIN142_Library_1791880767612
                        - generic [ref=e492]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e493] [cursor=pointer]:
                      - generic [ref=e494]:
                        - paragraph [ref=e495]: PIN142_MultipleTemplates_17918...
                        - generic [ref=e497]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e498] [cursor=pointer]:
                      - generic [ref=e499]:
                        - paragraph [ref=e500]: PIN142_Checkbox_1791880839402
                        - generic [ref=e502]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e503] [cursor=pointer]:
                      - generic [ref=e504]:
                        - paragraph [ref=e505]: PIN142_RepeatSelection_1791880...
                        - generic [ref=e507]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e508] [cursor=pointer]:
                      - generic [ref=e509]:
                        - paragraph [ref=e510]: PIN142_Library_1791881009263
                        - generic [ref=e512]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e513] [cursor=pointer]:
                      - generic [ref=e514]:
                        - paragraph [ref=e515]: PIN142_MultipleTemplates_17918...
                        - generic [ref=e517]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e518] [cursor=pointer]:
                      - generic [ref=e519]:
                        - paragraph [ref=e520]: PIN142_Checkbox_1791881096708
                        - generic [ref=e522]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e523] [cursor=pointer]:
                      - generic [ref=e524]:
                        - paragraph [ref=e525]: PIN142_RepeatSelection_1791881...
                        - generic [ref=e527]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e528] [cursor=pointer]:
                      - generic [ref=e529]:
                        - paragraph [ref=e530]: PIN142_Library_1791881400631
                        - generic [ref=e532]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e533] [cursor=pointer]:
                      - generic [ref=e534]:
                        - paragraph [ref=e535]: PIN142_Library_1791881423140
                        - generic [ref=e537]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e538] [cursor=pointer]:
                      - generic [ref=e539]:
                        - paragraph [ref=e540]: PIN142_MultipleTemplates_17918...
                        - generic [ref=e542]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e543] [cursor=pointer]:
                      - generic [ref=e544]:
                        - paragraph [ref=e545]: PIN142_Checkbox_1791881494051
                        - generic [ref=e547]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e548] [cursor=pointer]:
                      - generic [ref=e549]:
                        - paragraph [ref=e550]: PIN142_Library_1791881605417
                        - generic [ref=e552]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e553] [cursor=pointer]:
                      - generic [ref=e554]:
                        - paragraph [ref=e555]: PIN142_Library_1791881628909
                        - generic [ref=e557]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e558] [cursor=pointer]:
                      - generic [ref=e559]:
                        - paragraph [ref=e560]: PIN142_MultipleTemplates_17918...
                        - generic [ref=e562]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e563] [cursor=pointer]:
                      - generic [ref=e564]:
                        - paragraph [ref=e565]: PIN142_Library_1791881676365
                        - generic [ref=e567]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e568] [cursor=pointer]:
                      - generic [ref=e569]:
                        - paragraph [ref=e570]: PIN142_Checkbox_1791881691317
                        - generic [ref=e572]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e573] [cursor=pointer]:
                      - generic [ref=e574]:
                        - paragraph [ref=e575]: PIN142_RepeatSelection_1791881...
                        - generic [ref=e577]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e578] [cursor=pointer]:
                      - generic [ref=e579]:
                        - paragraph [ref=e580]: PIN142_MultipleTemplates_17918...
                        - generic [ref=e582]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e583] [cursor=pointer]:
                      - generic [ref=e584]:
                        - paragraph [ref=e585]: PIN142_Library_1791881775601
                        - generic [ref=e587]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e588] [cursor=pointer]:
                      - generic [ref=e589]:
                        - paragraph [ref=e590]: PIN142_Checkbox_1791881783290
                        - generic [ref=e592]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e593] [cursor=pointer]:
                      - generic [ref=e594]:
                        - paragraph [ref=e595]: PIN142_RepeatSelection_1791881...
                        - generic [ref=e597]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e598] [cursor=pointer]:
                      - generic [ref=e599]:
                        - paragraph [ref=e600]: PIN142_Checkbox_1791881864338
                        - generic [ref=e602]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e603] [cursor=pointer]:
                      - generic [ref=e604]:
                        - paragraph [ref=e605]: PIN142_RepeatSelection_1791881...
                        - generic [ref=e607]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e608] [cursor=pointer]:
                      - generic [ref=e609]:
                        - paragraph [ref=e610]: PIN142_Library_1791882032372
                        - generic [ref=e612]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e613] [cursor=pointer]:
                      - generic [ref=e614]:
                        - paragraph [ref=e615]: PIN142_Checkbox_1791882109956
                        - generic [ref=e617]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e618] [cursor=pointer]:
                      - generic [ref=e619]:
                        - paragraph [ref=e620]: PIN143_1791882579197
                        - generic [ref=e622]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e623] [cursor=pointer]:
                      - generic [ref=e624]:
                        - paragraph [ref=e625]: PIN143_1791882600332
                        - generic [ref=e627]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e628] [cursor=pointer]:
                      - generic [ref=e629]:
                        - paragraph [ref=e630]: PIN143_1791882611377
                        - generic [ref=e632]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e633] [cursor=pointer]:
                      - generic [ref=e634]:
                        - paragraph [ref=e635]: PIN143_1791882621654
                        - generic [ref=e637]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e638] [cursor=pointer]:
                      - generic [ref=e639]:
                        - paragraph [ref=e640]: PIN143_1791882640767
                        - generic [ref=e642]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e643] [cursor=pointer]:
                      - generic [ref=e644]:
                        - paragraph [ref=e645]: PIN143_1791882661162
                        - generic [ref=e647]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e648] [cursor=pointer]:
                      - generic [ref=e649]:
                        - paragraph [ref=e650]: PIN143_1791882683310
                        - generic [ref=e652]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e653] [cursor=pointer]:
                      - generic [ref=e654]:
                        - paragraph [ref=e655]: PIN143_1791882705465
                        - generic [ref=e657]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e658] [cursor=pointer]:
                      - generic [ref=e659]:
                        - paragraph [ref=e660]: PIN143_1791882725523
                        - generic [ref=e662]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e663] [cursor=pointer]:
                      - generic [ref=e664]:
                        - paragraph [ref=e665]: PIN143_1791882751193
                        - generic [ref=e667]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e668] [cursor=pointer]:
                      - generic [ref=e669]:
                        - paragraph [ref=e670]: PIN143_1791882865940
                        - generic [ref=e672]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e673] [cursor=pointer]:
                      - generic [ref=e674]:
                        - paragraph [ref=e675]: PIN143_1791882888020
                        - generic [ref=e677]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e678] [cursor=pointer]:
                      - generic [ref=e679]:
                        - paragraph [ref=e680]: PIN143_1791882897536
                        - generic [ref=e682]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e683] [cursor=pointer]:
                      - generic [ref=e684]:
                        - paragraph [ref=e685]: PIN143_1791882906344
                        - generic [ref=e687]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e688] [cursor=pointer]:
                      - generic [ref=e689]:
                        - paragraph [ref=e690]: PIN143_1791882923667
                        - generic [ref=e692]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e693] [cursor=pointer]:
                      - generic [ref=e694]:
                        - paragraph [ref=e695]: PIN143_1791882942281
                        - generic [ref=e697]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e698] [cursor=pointer]:
                      - generic [ref=e699]:
                        - paragraph [ref=e700]: PIN143_1791882960774
                        - generic [ref=e702]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e703] [cursor=pointer]:
                      - generic [ref=e704]:
                        - paragraph [ref=e705]: PIN143_1791882980278
                        - generic [ref=e707]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e708] [cursor=pointer]:
                      - generic [ref=e709]:
                        - paragraph [ref=e710]: PIN143_1791883002101
                        - generic [ref=e712]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e713] [cursor=pointer]:
                      - generic [ref=e714]:
                        - paragraph [ref=e715]: PIN143_1791883022929
                        - generic [ref=e717]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e718] [cursor=pointer]:
                      - generic [ref=e719]:
                        - paragraph [ref=e720]: PIN143_1791883844925
                        - generic [ref=e722]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e723] [cursor=pointer]:
                      - generic [ref=e724]:
                        - paragraph [ref=e725]: PIN143_1791883857287
                        - generic [ref=e727]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e728] [cursor=pointer]:
                      - generic [ref=e729]:
                        - paragraph [ref=e730]: PIN143_1791883869920
                        - generic [ref=e732]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e733] [cursor=pointer]:
                      - generic [ref=e734]:
                        - paragraph [ref=e735]: PIN143_1791883880456
                        - generic [ref=e737]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e738] [cursor=pointer]:
                      - generic [ref=e739]:
                        - paragraph [ref=e740]: PIN143_1791883899477
                        - generic [ref=e742]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e743] [cursor=pointer]:
                      - generic [ref=e744]:
                        - paragraph [ref=e745]: PIN143_1791883910229
                        - generic [ref=e747]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e748] [cursor=pointer]:
                      - generic [ref=e749]:
                        - paragraph [ref=e750]: PIN143_1791883930121
                        - generic [ref=e752]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e753] [cursor=pointer]:
                      - generic [ref=e754]:
                        - paragraph [ref=e755]: PIN143_1791883941390
                        - generic [ref=e757]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e758] [cursor=pointer]:
                      - generic [ref=e759]:
                        - paragraph [ref=e760]: PIN143_1791883952545
                        - generic [ref=e762]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e763] [cursor=pointer]:
                      - generic [ref=e764]:
                        - paragraph [ref=e765]: PIN143_1791883963502
                        - generic [ref=e767]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e768] [cursor=pointer]:
                      - generic [ref=e769]:
                        - paragraph [ref=e770]: PIN143_1791884084182
                        - generic [ref=e772]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e773] [cursor=pointer]:
                      - generic [ref=e774]:
                        - paragraph [ref=e775]: PIN143_1791884095699
                        - generic [ref=e777]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e778] [cursor=pointer]:
                      - generic [ref=e779]:
                        - paragraph [ref=e780]: PIN143_1791884106950
                        - generic [ref=e782]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e783] [cursor=pointer]:
                      - generic [ref=e784]:
                        - paragraph [ref=e785]: PIN143_1791884118517
                        - generic [ref=e787]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e788] [cursor=pointer]:
                      - generic [ref=e789]:
                        - paragraph [ref=e790]: PIN143_1791884129530
                        - generic [ref=e792]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e793] [cursor=pointer]:
                      - generic [ref=e794]:
                        - paragraph [ref=e795]: PIN143_1791884141858
                        - generic [ref=e797]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e798] [cursor=pointer]:
                      - generic [ref=e799]:
                        - paragraph [ref=e800]: PIN143_1791884152291
                        - generic [ref=e802]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e803] [cursor=pointer]:
                      - generic [ref=e804]:
                        - paragraph [ref=e805]: PIN143_1791884162766
                        - generic [ref=e807]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e808] [cursor=pointer]:
                      - generic [ref=e809]:
                        - paragraph [ref=e810]: PIN143_1791884174552
                        - generic [ref=e812]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e813] [cursor=pointer]:
                      - generic [ref=e814]:
                        - paragraph [ref=e815]: PIN143_1791884186003
                        - generic [ref=e817]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e818] [cursor=pointer]:
                      - generic [ref=e819]:
                        - paragraph [ref=e820]: PIN143_1791884635005
                        - generic [ref=e822]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e823] [cursor=pointer]:
                      - generic [ref=e824]:
                        - paragraph [ref=e825]: PIN143_1791885074060
                        - generic [ref=e827]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e828] [cursor=pointer]:
                      - generic [ref=e829]:
                        - paragraph [ref=e830]: PIN143_1791885230005
                        - generic [ref=e832]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e833] [cursor=pointer]:
                      - generic [ref=e834]:
                        - paragraph [ref=e835]: PIN143_1791885266191
                        - generic [ref=e837]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e838] [cursor=pointer]:
                      - generic [ref=e839]:
                        - paragraph [ref=e840]: PIN143_1791885317343
                        - generic [ref=e842]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e843] [cursor=pointer]:
                      - generic [ref=e844]:
                        - paragraph [ref=e845]: PIN143_1791885329413
                        - generic [ref=e847]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e848] [cursor=pointer]:
                      - generic [ref=e849]:
                        - paragraph [ref=e850]: PIN143_1791885338914
                        - generic [ref=e852]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e853] [cursor=pointer]:
                      - generic [ref=e854]:
                        - paragraph [ref=e855]: PIN143_1791885349099
                        - generic [ref=e857]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e858] [cursor=pointer]:
                      - generic [ref=e859]:
                        - paragraph [ref=e860]: PIN143_1791885358850
                        - generic [ref=e862]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e863] [cursor=pointer]:
                      - generic [ref=e864]:
                        - paragraph [ref=e865]: PIN143_1791885368420
                        - generic [ref=e867]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e868] [cursor=pointer]:
                      - generic [ref=e869]:
                        - paragraph [ref=e870]: PIN143_1791885379996
                        - generic [ref=e872]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e873] [cursor=pointer]:
                      - generic [ref=e874]:
                        - paragraph [ref=e875]: PIN143_1791885393628
                        - generic [ref=e877]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e878] [cursor=pointer]:
                      - generic [ref=e879]:
                        - paragraph [ref=e880]: PIN143_1791885406116
                        - generic [ref=e882]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e883] [cursor=pointer]:
                      - generic [ref=e884]:
                        - paragraph [ref=e885]: PIN143_1791885418673
                        - generic [ref=e887]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e888] [cursor=pointer]:
                      - generic [ref=e889]:
                        - paragraph [ref=e890]: PIN143_1791885994913
                        - generic [ref=e892]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e893] [cursor=pointer]:
                      - generic [ref=e894]:
                        - paragraph [ref=e895]: PIN143_1791886048290
                        - generic [ref=e897]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e898] [cursor=pointer]:
                      - generic [ref=e899]:
                        - paragraph [ref=e900]: PIN143_1791886240460
                        - generic [ref=e902]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e903] [cursor=pointer]:
                      - generic [ref=e904]:
                        - paragraph [ref=e905]: PIN143_1791886309332
                        - generic [ref=e907]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e908] [cursor=pointer]:
                      - generic [ref=e909]:
                        - paragraph [ref=e910]: PIN143_1791886332383
                        - generic [ref=e912]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e913] [cursor=pointer]:
                      - generic [ref=e914]:
                        - paragraph [ref=e915]: PIN143_1791886343115
                        - generic [ref=e917]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e918] [cursor=pointer]:
                      - generic [ref=e919]:
                        - paragraph [ref=e920]: PIN143_1791886353647
                        - generic [ref=e922]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e923] [cursor=pointer]:
                      - generic [ref=e924]:
                        - paragraph [ref=e925]: PIN143_1791886362606
                        - generic [ref=e927]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e928] [cursor=pointer]:
                      - generic [ref=e929]:
                        - paragraph [ref=e930]: PIN143_1791886372890
                        - generic [ref=e932]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e933] [cursor=pointer]:
                      - generic [ref=e934]:
                        - paragraph [ref=e935]: PIN143_1791886382423
                        - generic [ref=e937]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e938] [cursor=pointer]:
                      - generic [ref=e939]:
                        - paragraph [ref=e940]: PIN143_1791886392607
                        - generic [ref=e942]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e943] [cursor=pointer]:
                      - generic [ref=e944]:
                        - paragraph [ref=e945]: PIN143_1791886419845
                        - generic [ref=e947]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e948] [cursor=pointer]:
                      - generic [ref=e949]:
                        - paragraph [ref=e950]: PIN143_1791887655990
                        - generic [ref=e952]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e953] [cursor=pointer]:
                      - generic [ref=e954]:
                        - paragraph [ref=e955]: PIN143_1791887856359
                        - generic [ref=e957]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e958] [cursor=pointer]:
                      - generic [ref=e959]:
                        - paragraph [ref=e960]: PIN144_1791889071745
                        - generic [ref=e962]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e963] [cursor=pointer]:
                      - generic [ref=e964]:
                        - paragraph [ref=e965]: PIN144_1791889135029
                        - generic [ref=e967]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e968] [cursor=pointer]:
                      - generic [ref=e969]:
                        - paragraph [ref=e970]: PIN144_1791889729543
                        - generic [ref=e972]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e973] [cursor=pointer]:
                      - generic [ref=e974]:
                        - paragraph [ref=e975]: PIN144_1791889812537
                        - generic [ref=e977]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e978] [cursor=pointer]:
                      - generic [ref=e979]:
                        - paragraph [ref=e980]: PIN144_1791889882560
                        - generic [ref=e982]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e983] [cursor=pointer]:
                      - generic [ref=e984]:
                        - paragraph [ref=e985]: PIN144_1791889992122
                        - generic [ref=e987]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e988] [cursor=pointer]:
                      - generic [ref=e989]:
                        - paragraph [ref=e990]: PIN144_1791890107614
                        - generic [ref=e992]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e993] [cursor=pointer]:
                      - generic [ref=e994]:
                        - paragraph [ref=e995]: PIN144_Library_1791890123373
                        - generic [ref=e997]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e998] [cursor=pointer]:
                      - generic [ref=e999]:
                        - paragraph [ref=e1000]: PIN144_LibraryMultiple_1791890...
                        - generic [ref=e1002]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1003] [cursor=pointer]:
                      - generic [ref=e1004]:
                        - paragraph [ref=e1005]: PIN144_Library_1791890329122
                        - generic [ref=e1007]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1008] [cursor=pointer]:
                      - generic [ref=e1009]:
                        - paragraph [ref=e1010]: PIN144_Edit_1791890369486_Upda...
                        - generic [ref=e1012]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1013] [cursor=pointer]:
                      - generic [ref=e1014]:
                        - paragraph [ref=e1015]: PIN144_1791890494907
                        - generic [ref=e1017]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1018] [cursor=pointer]:
                      - generic [ref=e1019]:
                        - paragraph [ref=e1020]: PIN144_Library_1791890510767
                        - generic [ref=e1022]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1023] [cursor=pointer]:
                      - generic [ref=e1024]:
                        - paragraph [ref=e1025]: PIN144_Library_1791890641609
                        - generic [ref=e1027]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1028] [cursor=pointer]:
                      - generic [ref=e1029]:
                        - paragraph [ref=e1030]: PIN144_Library_1791890763473
                        - generic [ref=e1032]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1033] [cursor=pointer]:
                      - generic [ref=e1034]:
                        - paragraph [ref=e1035]: PIN144_LibraryMultiple_1791890...
                        - generic [ref=e1037]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1038] [cursor=pointer]:
                      - generic [ref=e1039]:
                        - paragraph [ref=e1040]: PIN144_1791890828141
                        - generic [ref=e1042]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1043] [cursor=pointer]:
                      - generic [ref=e1044]:
                        - paragraph [ref=e1045]: PIN144_Library_1791890912988
                        - generic [ref=e1047]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1048] [cursor=pointer]:
                      - generic [ref=e1049]:
                        - paragraph [ref=e1050]: PIN144_1791891251132
                        - generic [ref=e1052]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1053] [cursor=pointer]:
                      - generic [ref=e1054]:
                        - paragraph [ref=e1055]: PIN144_Library_1791891267407
                        - generic [ref=e1057]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1058] [cursor=pointer]:
                      - generic [ref=e1059]:
                        - paragraph [ref=e1060]: PIN144_LibraryMultiple_1791891...
                        - generic [ref=e1062]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1063] [cursor=pointer]:
                      - generic [ref=e1064]:
                        - paragraph [ref=e1065]: PIN144_LibraryMultiple_1791891...
                        - generic [ref=e1067]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1068] [cursor=pointer]:
                      - generic [ref=e1069]:
                        - paragraph [ref=e1070]: PIN144_LibraryMultiple_1791891...
                        - generic [ref=e1072]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1073] [cursor=pointer]:
                      - generic [ref=e1074]:
                        - paragraph [ref=e1075]: PIN144_LibraryMultiple_1791891...
                        - generic [ref=e1077]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1078] [cursor=pointer]:
                      - generic [ref=e1079]:
                        - paragraph [ref=e1080]: PIN144_Library_1791891866648
                        - generic [ref=e1082]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1083] [cursor=pointer]:
                      - generic [ref=e1084]:
                        - paragraph [ref=e1085]: PIN144_LibraryMultiple_1791891...
                        - generic [ref=e1087]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1088] [cursor=pointer]:
                      - generic [ref=e1089]:
                        - paragraph [ref=e1090]: PIN143_1791893074663
                        - generic [ref=e1092]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1093] [cursor=pointer]:
                      - generic [ref=e1094]:
                        - paragraph [ref=e1095]: PIN143_1791893437347
                        - generic [ref=e1097]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1098] [cursor=pointer]:
                      - generic [ref=e1099]:
                        - paragraph [ref=e1100]: PIN143_1791894555986
                        - generic [ref=e1102]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1103] [cursor=pointer]:
                      - generic [ref=e1104]:
                        - paragraph [ref=e1105]: PIN145_1791894566710
                        - generic [ref=e1107]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1108] [cursor=pointer]:
                      - generic [ref=e1109]:
                        - paragraph [ref=e1110]: PIN143_1791894687433
                        - generic [ref=e1112]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1113] [cursor=pointer]:
                      - generic [ref=e1114]:
                        - paragraph [ref=e1115]: PIN143_1791894696671
                        - generic [ref=e1117]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1118] [cursor=pointer]:
                      - generic [ref=e1119]:
                        - paragraph [ref=e1120]: PIN143_1791894743348
                        - generic [ref=e1122]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1123] [cursor=pointer]:
                      - generic [ref=e1124]:
                        - paragraph [ref=e1125]: PIN143_1791894750587
                        - generic [ref=e1127]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1128] [cursor=pointer]:
                      - generic [ref=e1129]:
                        - paragraph [ref=e1130]: PIN143_1791894759596
                        - generic [ref=e1132]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1133] [cursor=pointer]:
                      - generic [ref=e1134]:
                        - paragraph [ref=e1135]: PIN143_1791894769565
                        - generic [ref=e1137]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1138] [cursor=pointer]:
                      - generic [ref=e1139]:
                        - paragraph [ref=e1140]: PIN143_1791894780578
                        - generic [ref=e1142]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1143] [cursor=pointer]:
                      - generic [ref=e1144]:
                        - paragraph [ref=e1145]: PIN143_1791894792507
                        - generic [ref=e1147]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1148] [cursor=pointer]:
                      - generic [ref=e1149]:
                        - paragraph [ref=e1150]: PIN143_1791894805562
                        - generic [ref=e1152]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1153] [cursor=pointer]:
                      - generic [ref=e1154]:
                        - paragraph [ref=e1155]: PIN143_1791894817957
                        - generic [ref=e1157]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1158] [cursor=pointer]:
                      - generic [ref=e1159]:
                        - paragraph [ref=e1160]: PIN143_1791894846106
                        - generic [ref=e1162]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1163] [cursor=pointer]:
                      - generic [ref=e1164]:
                        - paragraph [ref=e1165]: PIN143_1791894890416
                        - generic [ref=e1167]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1168] [cursor=pointer]:
                      - generic [ref=e1169]:
                        - paragraph [ref=e1170]: PIN143_1791894933420
                        - generic [ref=e1172]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1173] [cursor=pointer]:
                      - generic [ref=e1174]:
                        - paragraph [ref=e1175]: PIN143_1791894946037
                        - generic [ref=e1177]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1178] [cursor=pointer]:
                      - generic [ref=e1179]:
                        - paragraph [ref=e1180]: PIN145_25_1791894956672
                        - generic [ref=e1182]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1183] [cursor=pointer]:
                      - generic [ref=e1184]:
                        - paragraph [ref=e1185]: PIN145_01_1791895161754
                        - generic [ref=e1187]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1188] [cursor=pointer]:
                      - generic [ref=e1189]:
                        - paragraph [ref=e1190]: PIN143_1791895184487
                        - generic [ref=e1192]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1193] [cursor=pointer]:
                      - generic [ref=e1194]:
                        - paragraph [ref=e1195]: PIN143_1791895192921
                        - generic [ref=e1197]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1198] [cursor=pointer]:
                      - generic [ref=e1199]:
                        - paragraph [ref=e1200]: PIN143_1791895201625
                        - generic [ref=e1202]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1203] [cursor=pointer]:
                      - generic [ref=e1204]:
                        - paragraph [ref=e1205]: PIN143_1791895224241
                        - generic [ref=e1207]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1208] [cursor=pointer]:
                      - generic [ref=e1209]:
                        - paragraph [ref=e1210]: PIN143_1791895233002
                        - generic [ref=e1212]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1213] [cursor=pointer]:
                      - generic [ref=e1214]:
                        - paragraph [ref=e1215]: PIN143_1791895242786
                        - generic [ref=e1217]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1218] [cursor=pointer]:
                      - generic [ref=e1219]:
                        - paragraph [ref=e1220]: PIN143_1791895256062
                        - generic [ref=e1222]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1223] [cursor=pointer]:
                      - generic [ref=e1224]:
                        - paragraph [ref=e1225]: PIN143_1791895266465
                        - generic [ref=e1227]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1228] [cursor=pointer]:
                      - generic [ref=e1229]:
                        - paragraph [ref=e1230]: PIN143_1791895278853
                        - generic [ref=e1232]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1233] [cursor=pointer]:
                      - generic [ref=e1234]:
                        - paragraph [ref=e1235]: PIN143_1791895291279
                        - generic [ref=e1237]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1238] [cursor=pointer]:
                      - generic [ref=e1239]:
                        - paragraph [ref=e1240]: PIN143_1791895303833
                        - generic [ref=e1242]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1243] [cursor=pointer]:
                      - generic [ref=e1244]:
                        - paragraph [ref=e1245]: PIN143_1791895332626
                        - generic [ref=e1247]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1248] [cursor=pointer]:
                      - generic [ref=e1249]:
                        - paragraph [ref=e1250]: PIN143_1791895356615
                        - generic [ref=e1252]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1253] [cursor=pointer]:
                      - generic [ref=e1254]:
                        - paragraph [ref=e1255]: PIN143_1791895373097
                        - generic [ref=e1257]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1258] [cursor=pointer]:
                      - generic [ref=e1259]:
                        - paragraph [ref=e1260]: PIN145_21_1791895383138
                        - generic [ref=e1262]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1263] [cursor=pointer]:
                      - generic [ref=e1264]:
                        - paragraph [ref=e1265]: PIN143_1791895398731
                        - generic [ref=e1267]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1268] [cursor=pointer]:
                      - generic [ref=e1269]:
                        - paragraph [ref=e1270]: PIN143_1791895411825
                        - generic [ref=e1272]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1273] [cursor=pointer]:
                      - generic [ref=e1274]:
                        - paragraph [ref=e1275]: PIN145_Flow1_1791895407741
                        - generic [ref=e1277]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1278] [cursor=pointer]:
                      - generic [ref=e1279]:
                        - paragraph [ref=e1280]: PIN143_1791895425303
                        - generic [ref=e1282]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1283] [cursor=pointer]:
                      - generic [ref=e1284]:
                        - paragraph [ref=e1285]: PIN143_1791895435508
                        - generic [ref=e1287]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1288] [cursor=pointer]:
                      - generic [ref=e1289]:
                        - paragraph [ref=e1290]: PIN145_25_1791895437063
                        - generic [ref=e1292]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1293] [cursor=pointer]:
                      - generic [ref=e1294]:
                        - paragraph [ref=e1295]: PIN143_1791895448630
                        - generic [ref=e1297]: 3 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1298] [cursor=pointer]:
                      - generic [ref=e1299]:
                        - paragraph [ref=e1300]: PIN143_1791895470286
                        - generic [ref=e1302]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1303] [cursor=pointer]:
                      - generic [ref=e1304]:
                        - paragraph [ref=e1305]: PIN145_Flow5_1791895495045
                        - generic [ref=e1307]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1308] [cursor=pointer]:
                      - generic [ref=e1309]:
                        - paragraph [ref=e1310]: PIN143_1791895924886
                        - generic [ref=e1312]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1313] [cursor=pointer]:
                      - generic [ref=e1314]:
                        - paragraph [ref=e1315]: PIN143_1791895937469
                        - generic [ref=e1317]: 3 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1318] [cursor=pointer]:
                      - generic [ref=e1319]:
                        - paragraph [ref=e1320]: PIN143_1791895959012
                        - generic [ref=e1322]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1323] [cursor=pointer]:
                      - generic [ref=e1324]:
                        - paragraph [ref=e1325]: PIN145_Flow5_1791895981955
                        - generic [ref=e1327]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1328] [cursor=pointer]:
                      - generic [ref=e1329]:
                        - paragraph [ref=e1330]: PIN143_1791896507835
                        - generic [ref=e1332]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1333] [cursor=pointer]:
                      - generic [ref=e1334]:
                        - paragraph [ref=e1335]: PIN145_Flow1_1791896755578
                        - generic [ref=e1337]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1338] [cursor=pointer]:
                      - generic [ref=e1339]:
                        - paragraph [ref=e1340]: PIN143_1791896773250
                        - generic [ref=e1342]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1343] [cursor=pointer]:
                      - generic [ref=e1344]:
                        - paragraph [ref=e1345]: PIN143_1791896784783
                        - generic [ref=e1347]: 3 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1348] [cursor=pointer]:
                      - generic [ref=e1349]:
                        - paragraph [ref=e1350]: PIN143_1791896810192
                        - generic [ref=e1352]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1353] [cursor=pointer]:
                      - generic [ref=e1354]:
                        - paragraph [ref=e1355]: PIN145_Flow5_1791896835633
                        - generic [ref=e1357]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1358] [cursor=pointer]:
                      - generic [ref=e1359]:
                        - paragraph [ref=e1360]: PIN144_1792055534548
                        - generic [ref=e1362]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1363] [cursor=pointer]:
                      - generic [ref=e1364]:
                        - paragraph [ref=e1365]: PIN145_Flow1_1792055562630
                        - generic [ref=e1367]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1368] [cursor=pointer]:
                      - generic [ref=e1369]:
                        - paragraph [ref=e1370]: PIN143_1792055580390
                        - generic [ref=e1372]: 1 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1373] [cursor=pointer]:
                      - generic [ref=e1374]:
                        - paragraph [ref=e1375]: PIN143_1792055594737
                        - generic [ref=e1377]: 0 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1378] [cursor=pointer]:
                      - generic [ref=e1379]:
                        - paragraph [ref=e1380]: PIN143_1792055622029
                        - generic [ref=e1382]: 2 Task Templates
                      - generic:
                        - img
                    - generic [ref=e1383] [cursor=pointer]:
                      - generic [ref=e1384]:
                        - paragraph [ref=e1385]: PIN145_Flow5_1792055645228
                        - generic [ref=e1387]: 1 Task Templates
                      - generic:
                        - img
                - generic [ref=e1389]:
                  - generic [ref=e1390]:
                    - paragraph [ref=e1392]: Auto List
                    - generic [ref=e1393]:
                      - button [ref=e1394] [cursor=pointer]:
                        - generic [ref=e1395]:
                          - text: Add Task Template
                          - img [ref=e1396]
                      - button [ref=e1398] [cursor=pointer]:
                        - img [ref=e1399]
                  - generic [ref=e1403]:
                    - paragraph [ref=e1404]: No Templates Yet
                    - paragraph [ref=e1405]: Add task templates to this list by creating from scratch or importing from the template library.
    - generic [ref=e1406]:
      - generic [ref=e1407]:
        - heading [level=6] [ref=e1408]: Theme & Style
        - img [ref=e1409] [cursor=pointer]
      - generic [ref=e1411]:
        - generic [ref=e1412]:
          - heading [level=6] [ref=e1413]:
            - img [ref=e1414]
            - text: Theme Mode
          - generic [ref=e1416]:
            - button [ref=e1417] [cursor=pointer]:
              - img [ref=e1418]
              - text: Light
            - button [ref=e1420] [cursor=pointer]:
              - img [ref=e1421]
              - text: Dark
            - button [ref=e1423] [cursor=pointer]:
              - img [ref=e1424]
              - text: Auto
        - heading [level=6] [ref=e1427]:
          - img [ref=e1428]
          - text: Theme Color
        - generic [ref=e1443]:
          - heading [level=6] [ref=e1444]: Dashboard Layout
          - generic [ref=e1445]:
            - button [ref=e1446] [cursor=pointer]:
              - img [ref=e1447]
              - text: Default
            - button [ref=e1449] [cursor=pointer]:
              - img [ref=e1450]
              - text: New Layout
    - generic [ref=e1452]:
      - generic [ref=e1453]:
        - heading [level=6] [ref=e1454]: Change Password
        - img [ref=e1455] [cursor=pointer]
      - generic [ref=e1457]:
        - generic [ref=e1458]:
          - text: "You are currently logged in as:"
          - strong [ref=e1459]: xperts_imaging@yopmail.com
          - generic [ref=e1460]: Please enter your current password to verify your identity, then create a strong new password to keep your account secure.
        - alert [ref=e1461]:
          - img [ref=e1463]
          - generic [ref=e1466]:
            - strong [ref=e1467]: Security Notice
            - generic [ref=e1468]: For your safety, you will be automatically logged out after a successful password change.
        - generic [ref=e1469]:
          - generic [ref=e1471]:
            - generic [ref=e1472]:
              - generic [ref=e1474]:
                - text: Old Password
                - generic [ref=e1475]: "*"
              - textbox [ref=e1477]:
                - /placeholder: Enter your current password
            - img [ref=e1479] [cursor=pointer]
          - generic [ref=e1482]:
            - generic [ref=e1483]:
              - generic [ref=e1485]:
                - text: New Password
                - generic [ref=e1486]: "*"
              - textbox [ref=e1488]:
                - /placeholder: Create a strong new password
            - img [ref=e1490] [cursor=pointer]
          - generic [ref=e1493]:
            - generic [ref=e1494]:
              - generic [ref=e1496]:
                - text: Confirm Password
                - generic [ref=e1497]: "*"
              - textbox [disabled] [ref=e1499]:
                - /placeholder: Re-enter your new password
            - img [ref=e1501]
          - button [ref=e1503] [cursor=pointer]: Update Password
  - dialog [ref=e1506]:
    - banner [ref=e1507]:
      - generic [ref=e1508]:
        - button "close" [ref=e1509] [cursor=pointer]:
          - img [ref=e1510]
        - generic [ref=e1513]: System Task Library
        - generic [ref=e1514]:
          - button "Cancel" [ref=e1515] [cursor=pointer]
          - button "Add to Task List" [disabled]
    - generic [ref=e1517]:
      - generic [ref=e1518]:
        - generic [ref=e1519]: CATEGORIES
        - generic [ref=e1520] [cursor=pointer]:
          - paragraph [ref=e1521]: HR Tasks (3)
          - img [ref=e1522]
        - paragraph [ref=e1525] [cursor=pointer]: IT Admin tasks (2)
        - paragraph [ref=e1527] [cursor=pointer]: Reporting Manager Tasks (1)
        - paragraph [ref=e1529] [cursor=pointer]: Payroll Tasks (0)
      - generic [ref=e1530]:
        - heading "HR Tasks" [level=6] [ref=e1532]
        - table "Data table" [ref=e1535]:
          - rowgroup [ref=e1536]:
            - row "TASK TEMPLATE NAME ASSIGNED TO DUE ON APPROVER Actions" [ref=e1537]:
              - columnheader "TASK TEMPLATE NAME" [ref=e1538]:
                - generic [ref=e1539]:
                  - generic [ref=e1541] [cursor=pointer]:
                    - checkbox [ref=e1542]
                    - img [ref=e1543]
                  - generic [ref=e1547]: TASK TEMPLATE NAME
              - columnheader "ASSIGNED TO" [ref=e1548]:
                - generic [ref=e1550]: ASSIGNED TO
              - columnheader "DUE ON" [ref=e1551]:
                - generic [ref=e1553]: DUE ON
              - columnheader "APPROVER" [ref=e1554]:
                - generic [ref=e1556]: APPROVER
              - columnheader "Actions" [ref=e1557]:
                - generic [ref=e1559]: Actions
          - rowgroup [ref=e1560]:
            - row "Exit interview EMPLOYEE 0d Joining Day Not Specified View Details" [ref=e1561]:
              - cell "Exit interview" [ref=e1562]:
                - generic [ref=e1563]:
                  - generic [ref=e1565] [cursor=pointer]:
                    - checkbox [ref=e1566]
                    - img [ref=e1567]
                  - paragraph [ref=e1570]: Exit interview
              - cell "EMPLOYEE" [ref=e1571]:
                - generic [ref=e1572]:
                  - img [ref=e1574]
                  - generic [ref=e1576]: EMPLOYEE
              - cell "0d Joining Day" [ref=e1577]:
                - paragraph [ref=e1578]: 0d Joining Day
              - cell "Not Specified" [ref=e1579]:
                - paragraph [ref=e1580]: Not Specified
              - cell "View Details" [ref=e1581]:
                - generic "View Details" [ref=e1582]:
                  - button [ref=e1583] [cursor=pointer]:
                    - img [ref=e1584]
            - row "exit documentation EMPLOYEE on LWD Not Specified View Details" [ref=e1586]:
              - cell "exit documentation" [ref=e1587]:
                - generic [ref=e1588]:
                  - generic [ref=e1590] [cursor=pointer]:
                    - checkbox [ref=e1591]
                    - img [ref=e1592]
                  - paragraph [ref=e1595]: exit documentation
              - cell "EMPLOYEE" [ref=e1596]:
                - generic [ref=e1597]:
                  - img [ref=e1599]
                  - generic [ref=e1601]: EMPLOYEE
              - cell "on LWD" [ref=e1602]:
                - paragraph [ref=e1603]: on LWD
              - cell "Not Specified" [ref=e1604]:
                - paragraph [ref=e1605]: Not Specified
              - cell "View Details" [ref=e1606]:
                - generic "View Details" [ref=e1607]:
                  - button [ref=e1608] [cursor=pointer]:
                    - img [ref=e1609]
            - row "Email & remiders EMPLOYEE on LWD EMPLOYEE View Details" [ref=e1611]:
              - cell "Email & remiders" [ref=e1612]:
                - generic [ref=e1613]:
                  - generic [ref=e1615] [cursor=pointer]:
                    - checkbox [ref=e1616]
                    - img [ref=e1617]
                  - paragraph [ref=e1620]: Email & remiders
              - cell "EMPLOYEE" [ref=e1621]:
                - generic [ref=e1622]:
                  - img [ref=e1624]
                  - generic [ref=e1626]: EMPLOYEE
              - cell "on LWD" [ref=e1627]:
                - paragraph [ref=e1628]: on LWD
              - cell "EMPLOYEE" [ref=e1629]:
                - generic [ref=e1630]:
                  - img [ref=e1632]
                  - generic [ref=e1634]: EMPLOYEE
              - cell "View Details" [ref=e1635]:
                - generic "View Details" [ref=e1636]:
                  - button [ref=e1637] [cursor=pointer]:
                    - img [ref=e1638]
        - alert [ref=e1640]:
          - img [ref=e1642]
          - generic [ref=e1644]: Tasks can be edited after adding them as your task template
```

# Test source

```ts
  1   | const { test, expect } = require('@playwright/test');
  2   | const TaskTemplatesComponent = require('../../pages/exit/components/taskTemplates.component');
  3   | const SessionHelper = require('@utils/helpers/sessionHelper');
  4   | const logger = require('@utils/logger/logger');
  5   | 
  6   | test.use({
  7   |     storageState: 'playwright/.auth/user.json'
  8   | });
  9   | 
  10  | /**
  11  |  * PIN-142: System Task Library (Exit & Onboarding) Matrix
  12  |  *
  13  |  * Coverage Mapping:
  14  |  * - Flow 0: Setup & cleanup utilities (uniqueTaskListName, createdTaskListNames)
  15  |  * - Flow 1: Exit‑module UI basics
  16  |  *   • PIN_142_01 – Add Task List button availability
  17  |  *   • PIN_142_02 – Library opens on task‑template creation
  18  |  *   • PIN_142_03 – Library columns & predefined Exit tasks
  19  |  *   • PIN_142_04 – Read‑only mode for system tasks
  20  |  *   • PIN_142_05 – Single‑template add to task list
  21  |  *   • PIN_142_06 – Multi‑template add to task list
  22  |  * - Flow 2: Onboarding‑module UI basics
  23  |  *   • PIN_142_07 – Library rows visible in onboarding
  24  |  *   • PIN_142_08 – Library opens on onboarding creation
  25  |  *   • PIN_142_09 – Read‑only mode in onboarding
  26  |  *   • PIN_142_10 – Add‑to‑task‑list button enabled
  27  |  * - Flow 3: Common behaviour
  28  |  *   • PIN_142_11 – Checkboxes start unchecked
  29  |  *   • PIN_142_12 – Re‑select same task multiple times
  30  |  */
  31  | 
  32  | const {
  33  |     uniqueTaskListName,
  34  |     openTaskLibrary,
  35  |     selectLibraryTasks,
  36  |     navigateToOnboarding,
  37  |     openExitTaskLibrary,
  38  | } = require('./helpers/taskTemplatesHelpers');
  39  | 
  40  | test.describe('PIN-142: System Task Library (Exit & Onboarding) Matrix', { tag: '@daily-full' }, () => {
  41  |     test.describe.configure({ mode: 'default', timeout: 180_000 });
  42  | 
  43  |     /** @type {TaskTemplatesComponent} */
  44  |     let taskTemplatesPage;
  45  |     let createdTaskListNames;
  46  | 
  47  |     test.beforeEach(async ({ page }) => {
  48  |         taskTemplatesPage = new TaskTemplatesComponent(page);
  49  |         createdTaskListNames = [];
  50  |     });
  51  | 
  52  |     // ---------------------------------------------------------------------------
  53  |     // EMPTY‑STATE SANITY CHECK (PIN_142_00)
  54  |     // ---------------------------------------------------------------------------
  55  |     test('PIN_142_00 Verify empty state UI when no task lists exist', async () => {
  56  |         await taskTemplatesPage.goto();
  57  |         await taskTemplatesPage.verifyEmptyState();
  58  |         await expect(taskTemplatesPage.addTaskListButton.first(), 'Add Task List button should be enabled in empty state')
  59  |             .toBeEnabled();
  60  |     });
  61  | 
  62  |     test.afterEach(async ({ page }) => {
  63  |     if (createdTaskListNames.length === 0) {
  64  |         return;
  65  |     }
  66  | 
  67  |     await taskTemplatesPage.goto();
  68  |     for (const taskListName of createdTaskListNames.reverse()) {
  69  |         try {
  70  |             await taskTemplatesPage.deleteTaskList(taskListName);
  71  |         } catch (err) {
  72  |             logger.warn(`Failed to delete task list "${taskListName}": ${err.message}`);
  73  |         }
  74  |     }
  75  | });
  76  | 
  77  |     async function createTestTaskList(name) {
  78  |         createdTaskListNames.push(name);
  79  |         await taskTemplatesPage.createTaskList(name);
  80  |     }
  81  | 
  82  |     // ---------------------------------------------------------------------------
  83  |     // EXIT MODULE TESTS
  84  |     // ---------------------------------------------------------------------------
  85  | 
  86  |     test('PIN_142_01 Verify Add Task List action is available', async () => {
  87  |         await taskTemplatesPage.goto();
  88  |         await expect(taskTemplatesPage.addTaskListButton, 'Add Task List should be enabled').toBeEnabled();
  89  |     });
  90  | 
  91  |     test('PIN_142_02 Verify task library availability on task template creation', async () => {
  92  |         await taskTemplatesPage.goto();
  93  |         await createTestTaskList(uniqueTaskListName('Library'));
  94  |         await openTaskLibrary(taskTemplatesPage.page);
  95  |     });
  96  | 
  97  |     test('PIN_142_03 Verify task library columns and predefined Exit tasks', async () => {
  98  |         const library = await openExitTaskLibrary(taskTemplatesPage);
  99  |         for (const column of ['NAME OF TASK', 'ASSIGNED TO', 'DUE ON', 'APPROVER']) {
> 100 |             await expect(library.getByText(column, { exact: true }).first(), `${column} column should be displayed`).toBeVisible();
      |                                                                                                                      ^ Error: NAME OF TASK column should be displayed
  101 |         }
  102 |         await expect(library.locator('tr.table-view-data-row'), 'Predefined Exit tasks should be listed').toHaveCount(3);
  103 |     });
  104 | 
  105 |     test('PIN_142_04 Verify system task library templates are in read-only mode', async () => {
  106 |         const library = await openExitTaskLibrary(taskTemplatesPage);
  107 |         const taskRows = library.locator('tr.table-view-data-row');
  108 |         await expect(taskRows.first()).toBeVisible();
  109 |         const editButtons = taskRows.getByRole('button', { name: /edit/i });
  110 |         const deleteButtons = taskRows.getByRole('button', { name: /delete/i });
  111 |         await expect(editButtons, 'Edit buttons should not be visible (read-only)').toHaveCount(0);
  112 |         await expect(deleteButtons, 'Delete buttons should not be visible (read-only)').toHaveCount(0);
  113 |     });
  114 | 
  115 |     test('PIN_142_05 Verify templates can be added as task list copies', async () => {
  116 |         await taskTemplatesPage.goto();
  117 |         const taskListName = uniqueTaskListName('Library');
  118 |         await createTestTaskList(taskListName);
  119 |         const library = await openTaskLibrary(taskTemplatesPage.page);
  120 |         await selectLibraryTasks(library, 1);
  121 |         await library.getByRole('button', { name: 'Add to Task List' }).click();
  122 |         await expect(
  123 |             taskTemplatesPage.getTaskListRow(taskListName).locator('.split-list-item-count'),
  124 |             'The selected task list should contain the copied template'
  125 |         ).toHaveText('1 Task Templates');
  126 |         await expect(library).toBeHidden();
  127 |     });
  128 | 
  129 |     test('PIN_142_06 Verify multi templates can be added from task library at once', async () => {
  130 |         await taskTemplatesPage.goto();
  131 |         const taskListName = uniqueTaskListName('MultipleTemplates');
  132 |         await createTestTaskList(taskListName);
  133 |         const library = await openTaskLibrary(taskTemplatesPage.page);
  134 |         const selections = await selectLibraryTasks(library, 2);
  135 |         await library.getByRole('button', { name: 'Add to Task List' }).click();
  136 |         await expect(
  137 |             taskTemplatesPage.getTaskListRow(taskListName).locator('.split-list-item-count'),
  138 |             'Selected templates should be added to the task list'
  139 |         ).toHaveText(`${selections} Task Templates`);
  140 |     });
  141 | 
  142 |     // ---------------------------------------------------------------------------
  143 |     // ONBOARDING MODULE TESTS
  144 |     // ---------------------------------------------------------------------------
  145 | 
  146 |     test('PIN_142_07 Verify task templates in task library for onboarding module', async ({ page }) => {
  147 |         await navigateToOnboarding(page);
  148 |         const library = await openTaskLibrary(page);
  149 |         await expect(library.locator('tr.table-view-data-row').first(), 'Onboarding should list system tasks').toBeVisible({ timeout: 20000 });
  150 |     });
  151 | 
  152 |     test('PIN_142_08 Verify system task template availability on task template creation in onboarding module', async ({ page }) => {
  153 |         await navigateToOnboarding(page);
  154 |         await openTaskLibrary(page);
  155 |     });
  156 | 
  157 |     test('PIN_142_09 Verify system task library templates are in read-only mode in onboarding module', async ({ page }) => {
  158 |         await navigateToOnboarding(page);
  159 |         const library = await openTaskLibrary(page);
  160 |         const taskRows = library.locator('tr.table-view-data-row');
  161 |         await expect(taskRows.first()).toBeVisible();
  162 |         const editButtons = taskRows.getByRole('button', { name: /edit/i });
  163 |         const deleteButtons = taskRows.getByRole('button', { name: /delete/i });
  164 |         await expect(editButtons, 'Edit buttons should be absent in onboarding (read-only)').toHaveCount(0);
  165 |         await expect(deleteButtons, 'Delete buttons should be absent in onboarding (read-only)').toHaveCount(0);
  166 |     });
  167 | 
  168 |     test('PIN_142_10 Verify templates have option to add in task list in onboarding module', async ({ page }) => {
  169 |         await navigateToOnboarding(page);
  170 |         const library = await openTaskLibrary(page);
  171 |         const addButton = library.getByRole('button', { name: 'Add to Task List' });
  172 |         await selectLibraryTasks(library, 1);
  173 |         await expect(addButton, 'Selected onboarding tasks should be available to add').toBeEnabled();
  174 |     });
  175 | 
  176 |     // ---------------------------------------------------------------------------
  177 |     // COMMON BEHAVIOUR TESTS
  178 |     // ---------------------------------------------------------------------------
  179 | 
  180 |     test('PIN_142_11 Verify checkboxes are not auto-selected on selecting task from library', async () => {
  181 |         await taskTemplatesPage.goto();
  182 |         await createTestTaskList(uniqueTaskListName('Checkbox'));
  183 |         const library = await openTaskLibrary(taskTemplatesPage.page);
  184 |         const rows = library.locator('tr.table-view-data-row');
  185 |         await expect(rows.first(), 'System task rows should be available').toBeVisible({ timeout: 20000 });
  186 |         const checkboxes = rows.locator('input[type="checkbox"]');
  187 |         const count = await checkboxes.count();
  188 |         for (let i = 0; i < count; i++) {
  189 |             await expect(checkboxes.nth(i), `Task checkbox ${i} should be unchecked`).not.toBeChecked();
  190 |         }
  191 |     });
  192 | 
  193 |     test('PIN_142_12 Verify same task can be selected multiple times irrespective of prior selection', async () => {
  194 |         await taskTemplatesPage.goto();
  195 |         const taskListName = uniqueTaskListName('RepeatSelection');
  196 |         await createTestTaskList(taskListName);
  197 |         let library = await openTaskLibrary(taskTemplatesPage.page);
  198 |         await selectLibraryTasks(library, 1);
  199 |         await library.getByRole('button', { name: 'Add to Task List' }).click();
  200 |         await expect(
```