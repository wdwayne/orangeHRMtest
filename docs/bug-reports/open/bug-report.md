### OHRM-BUG-001 - Incorrect Error Message Display During Invalid Login Attempt

**Environment**
- Application: OrangeHRM Demo
- Browser: Google Chrome
- Device: Desktop

**Description**
When invalid input resembling SQL injection is entered into the login fields, the system displays a "CSRF token validation failed" error instead of a user-friendly authentication error message.

**Precondition**
- User is on the login page

**Steps to Reproduce**
1. Enter '1'='1 in the username field
2. Enter ' in the password field
3. Click the login button

**Expected Result**
- User remains on the login page
- Error message "Invalid credentials" is displayed

**Actual Result**
- Error message "CSRF token validation failed" is displayed

**Severity**
Medium

**Priority**
Medium

**Notes**
- Error message may expose internal security mechanisms
- System should handle invalid input gracefully and return a generic error message