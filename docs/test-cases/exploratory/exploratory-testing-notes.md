# Exploratory Testing Session 0 – Initial System Analysis

# Application Overview
OrangeHRM is a Human Resource Management System used to manage employee information, leave, time tracking, and administrative functions.

# Testing Approach
Initial exploratory testing was conducted to understand system functionality, identify key features, and determine high-risk areas before creating formal test cases.

# Application Features Identified ### 

# Authentication
- User login page

# Navigation System
- Sidebar navigation menu
- Expand/collapse functionality
- Application logo
- Global search bar

# Dashboard
## Widgets include:
- Time at Work widget
- My Actions widget
- Quick Launch widget
- Buzz Latest Posts
- Employees on Leave
- Employee Distribution by Sub Unit
- Employee Distribution by Location
# PIM (Personnel Information Management)
## Employee management features:
- Employee search
- Employee list
- Filters:
    - Employee name
    - Employee ID
    - Employment status
    - Supervisor
    - Job title
    - Sub unit

# Admin Module
## User management features:
- System user search
- System user list
- Filters:
    - Username
    - User role
    - Employee name
    - Status

# Leave Module
## Leave management features:
- Leave list search
- Filters:
    - From date
    - To date
    - Leave status
    - Leave type

# User types
Possible User Roles
Admin
- Manages system users and permissions
HR Manager
- Manages employee records and leave
Supervisor / Manager
- Reviews and approves employee activities such as leave and timesheets
Employee
- Views personal records and applies for leave


# Risks & Critical Areas
- High Risk Areas
    -Employee records accuracy
    -Timesheet tracking
    -Leave management
    -Manager approval workflows
    -Employee location / department information

# Supported Browsers
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari (if macOS users exist)

# Test Scope
## In Scope
- Login functionality
- Navigation modules
- Employee management(PIM)
- Dashboard widgets

## Out of Scope
- Third-party integrations
- Backend/database validation
- Performance testing

