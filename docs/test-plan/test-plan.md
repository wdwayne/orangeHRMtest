# Test Plan Overview
This test plan outlines the testing approach for the OrangeHRM application. OrangeHRM is an open-source Human Resource Management System (HRMS) designed to manage employee data, leave, time tracking, recruitment, and performance through a web-based platform.

# Objectives
1. Verify that core system functionalities work as expected
2. Identify and document defects within the application
3. Assess system behavior under valid and invalid conditions
4. Ensure critical business workflows function correctly

# Test Scope

*In Scope*
- Login functionality
- Navigation modules
- Employee management
- Leave management
- Dashboard widgets

*Out of Scope*
- Third-party integrations
- Backend/database validation
- Performance testing

# Test Strategy
Testing will be conducted using the following approaches:
1. Manual Testing
2. Functional Testing
3. Exploratory testing
4. Negative testing


# Test Environment 
- Browser: Google Chrome (latest version)
- Device: Desktop
- Operating System: Windows
- Environment: OrangeHRM demo site

# Test Deliverables
- Test cases
- Bug reports
- Exploratory notes

# Risks and Mitigation

Risk: Incorrect employee data  
Mitigation: Perform input validation and boundary testing on employee forms  

Risk: Incorrect timesheet data  
Mitigation: Validate time calculations and input constraints

Risk: Unauthorized access after logout  
Mitigation: Verify session invalidation and restricted access to protected pages after logout


## Entry and Exit Criteria

### Entry Criteria
- Application is accessible
- Test data is available

### Exit Criteria
- All test cases executed
- Critical bugs resolved