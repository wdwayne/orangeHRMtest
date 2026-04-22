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

### OHRM-BUG-002 – Dashboard Accessible via Browser Back Button After Logout

**Environment**
- Application: OrangeHRM Demo
- Browser: Google Chrome
- Device: Desktop

**Description**
After logging out of the application, navigating back using the browser back button allows the user to view the dashboard page without re-authentication.

**Preconditions**
- User is logged into the application

**Steps to Reproduce**
1. Log in with valid credentials
2. Click the Logout option
3. Click the browser back button

**Expected Result**
- User is redirected to the login page
- Protected pages (e.g., dashboard) should not be accessible after logout

**Actual Result**
- Dashboard page is displayed after clicking the back button

**Severity**
High

**Priority**
High

**Notes**
- This may be due to browser caching of authenticated pages
- Sensitive information may be exposed to unauthorized users
- Proper cache-control headers or session validation should be enforced