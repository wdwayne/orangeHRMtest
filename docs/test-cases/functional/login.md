ID
### OHRM-TC-001
**Description**
- Verify that a registered user can successfully login using a valid username and password.
**Preconditions**
- User is on the login page.
- User has valid credentials.
**Steps**
1. Enter a valid username.
2. Enter a valid password.
3. Click the login button.
**Expected Result**
- User is successfully logged in and redirected to the dashboard page.

### OHRM-TC-002
**Description**
- Verify that login fails when a valid username is entered with an incorrect password
**Preconditions**
- User is on the login page.
- User has a valid username.
**Steps**
1. Enter a valid username.
2. Enter an invalid password.
3. Click login
**Expected Results**
- login page refreshes and displays the message "invalid credentials".

### OHRM-TC-003
**Description**
- Attempt to login with a valid username and empty password field.
**Preconditions**
- User is on the login page.
- Valid username.
**Steps**
1. Enter a valid username.
2. Leave the password field empty.
3. Click thelogin button.
**Expected results**
- Password field is highlighted red and the message "Required" is displayed under the password field.

### OHRM-TC-004
**Description**
- Attempt to submit the login form with both username and password fields empty.
**Preconditions**
- user is on the login page.
**Steps**
1. Leave both the username and the password field empty. 
2. Click login button.
**Expected Results**
- Both the username and the password fields are highlighted red and a message "Required" is displayed under both fields.

### OHRM-TC-005
**Description** 
- Verify that an unregistered user is unable to login.
**Precondition**
- User is on the login page.
**Steps**
1. Enter an unregistered username.
2. Enter a password.
3. Click login button.
**Expected Results**
- Login page refreshes and the message "invalid credentials" is displayed.

### OHRM-TC-006
**Description**
- Verify that a registered user is able to successfully login using the enter button.
**Preconditions**
- User is on the login page.
- Valid username.
- Valid password.
**Steps**
1. Enter valid username.
2. Enter valid password.
3. Press enter button.
**Expected Results**
- User is successfully logged in and redirected to the dashboard page.

### OHRM-TC-007
**Description**
- Verify that a registered user is unable to successfully login if the incorrect password casing is used.
**Precondition**
- User is on the login page.
- A valid username.
- A valid password
**Steps**
1. Enter a valid username.
2. Enter password with incorrect letter casing.
3. Click the login button.
**Expected results**
- User stays on the login page.
- Message "invalid credentials" is displayed.

### OHRM-TC-008
**Description**
- Verify system behavior when SQL injection is attempted in login fields.
**Preconditions**
- user is on the login page.
**Steps**
1. Enter SQL injection payload (e.g., ' OR '1'='1)
2. press the login button.
**Expected results**
- User stays on the login page.
- Message "invalid credentials" is displayed.