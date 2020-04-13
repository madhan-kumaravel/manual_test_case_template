#### **Category**: Category_id 
#### Test Case ID: Login 0001
#### Test case description: Check response when valid email and password is entered for Gmail login
#### Priority: Major
#### Prerequisite: Already signed-up for Gmail
#### Test Data 
###### Username: test_user
###### Password: test_password
| Steps no.| Steps Description        | Expected result  | 
|----------|------------------        |----------------- |
| 1         |Open browser             |                  |
| 2         |Go to www.google.com     |                  |
| 3         |Click on Sign-in button  |                  |
| 4         |Enter Username           |                  |
| 5         |Enter Password           |                  |
| 6         |Click on Sign-in button  |It should re-direct to Gmail inbox page |

#### Login truth table
| Username| Password | Expected result | 
|---------|----------|-----------------|
| valid   | valid     | Pass           |
| valid   | in-valid  | Fail           |
| invalid | valid     | Fail           |
| invalid | invalid   | Fail           |


#### Actual Result: Re-directed to Gmail login page
#### Result: Passed
#### Notes: Tested this functionality in local enviornment
#### Jira Ticket ID: 12345
