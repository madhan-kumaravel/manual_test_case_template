**Category:** Category_id <br>
**Test Case ID:** Login 0001 <br>
**Test case description:** Check response when valid email and password is entered for Gmail login <br>
**Priority:** Major <br>
**Prerequisite:** Already signed-up for Gmail <br>
**Test Data:** <br>
**Username:** test_user <br>
**Password:** test_password <br>
| Steps no.| Steps Description        | Expected result  | 
|----------|------------------        |----------------- |
| 1         |Open browser             |                  |
| 2         |Go to www.google.com     |                  |
| 3         |Click on Sign-in button  |                  |
| 4         |Enter Username           |                  |
| 5         |Enter Password           |                  |
| 6         |Click on Sign-in button  |It should re-direct to Gmail inbox page |

**Login truth table:**
| Username| Password | Expected result | 
|---------|----------|-----------------|
| valid   | valid     | Pass           |
| valid   | in-valid  | Fail           |
| invalid | valid     | Fail           |
| invalid | invalid   | Fail           |


**Actual Result:** Re-directed to Gmail login page <br>
**Result:** Passed <br>
**Notes:** Tested this functionality in local enviornment<br>
**Jira Ticket ID:** 12345 <br>
