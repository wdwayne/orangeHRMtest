### OHRM-TC-009
**Description**
- Verify that when all search fields are left empty on the employee search form and the search button is click all employees are returned.
**Preconditions**
- User is currently on the PIM module
**Steps**
1. with all search fields empty click the search button.
**Expected Results**
- All employee records are displayed
- Total record count remains consistent across repeated searches

### OHRM-TC-010
**Description**
- Verify that employee names can be auto populated in the employee name search field when a user starts typing.
**Preconditions**
- User is currently on the PIM module
- A valid employee name
**Steps**
1. Begin typing the name an employee 
**Expected Results**
- System should display a drop down displaying names that correspond with the letter typed

### OHRM-TC-011
**Description**
- Verify that an employee can be found by searching for their name in the employee name field.
**Preconditions**
- User is currently on the PIM module
- A valid employee name
**Steps** 
1. Enter a Valid employee name
2. Click the search button
**Expected Results**
- The employee with the name entered should be populated on  screen in a table format

### OHRM-TC-012
**Description**
- Verify an appropriate error message is displayed when an unregistered employee is searched
**Preconditions**
- User is currently on the PIM module
**Steps**
1. Enter an invalid employee name
2. click search
**Expected Results**
- No employee records are displayed
- Mesaage "No records found" is displayed

### OHRM-TC-013
**Description**
- Verify that the employee Id field returns the correct employee 
**Preconditions**
- User is currently on the PIM module
- Registered employee id 
**Steps**
1. Enter registered employee Id number into "Employee Id" Field
2. click the search button
**Expected Results**
- System displays the employee with the Id that was searched

### OHRM-TC-014
**Description**
- Verify that the "Employee Id" field and the "Employee Name" field returns matching data when searching for the same employee
**Preconditions**
- User is currently on the PIM module
- Registered employee Id 
- Matching Registered employee name
**Steps**
1. Search for Registered employee via name
2. Search for the same employee using the employee Id
**Expeceted Results**
- Systems should return the same employeefor both searches

### OHRM-TC-015
**Description**
- Verify that if and unregistered employee number is searched no results will be returned and an adequate display message is shown
**Preconditions**
- User is currently on the PIM module
**Steps**
1. Enter an unregistered employee number into the employee Id field
2. Click Search
**Expected Results**
- No employee records are displayed
- Mesaage "No records found" is displayed

### OHRM-TC-016
**Description**
- Verify that if an employee ID longer than 10 digits is entered the system will return an error
**Preconditions**
- User is currently on the PIM module
**Steps**
1. Enter an employee number that is longer than 10 digits
2. Click the search button.
**Expected Results**
- No employee records are displayed
- Mesaage "Invalid parameter" is displayed

### OHRM-TC-017
**Description**
- Verify that employees can be searched by thier employment status
**Preconditions**
- User is currently on the PIM module
**Steps**
1. Select the Employment status drop down and select a status
2. Click the search button
**Expected Results**
- All employees under the selected status should be displayed

### OHRM-TC-018
**Description**
- Verfify that employees can be searched by "Current Employee only" "include" field
**Preconditions**
- User is currently on the PIM module
**Steps**
1. Ensure the option selected in the "Include" field is "Current Employee only"
2. Click the search button
**Expected Results**
- System should only return employees that are currently employed

### OHRM-TC-019
**Description**
- Verfify that employees can be searched by "Past and Current Employee" using the "include" field
**Preconditions**
- User is currently on the PIM module
**Steps**
1. Ensure the option selected in the "Include" field is "Past and Current Employee"
2. Click the search button
**Expected Results**
- System should return all employees whetherthey are currently employed or not

### OHRM-TC-020
**Description**
- Verfify that employees can be searched by "Past employees only" using the "include" field
**Preconditions**
- User is currently on the PIM module
**Steps**
1. Ensure the option selected in the "Include" field is "Past employees only"
2. Click the search button
**Expected Results**
- System should only return past employees

### OHRM-TC-021
**Description**
- Verify that employees can be search via their supervisors name using the "Supervisor name" field
**Preconditions**
- User is currently on the PIM module
- registered Supervisor name
**Steps**
1. Enter registered supervisor name
2. Click the search button
**Expected Results**
- All employees under the selected Supervisor should be displayed

### OHRM-TC-022
**Description**
- Verify that the supervisor's name will be auto populated if the correct first letters are typed
**Preconditions**
- User is currently on the PIM module
- Registeredsupervsior name
**Steps**
1. Begin typing supervisor name
**Expected Results**
- System should display a list of names that match the entered input/s

### OHRM-TC-023
**Description**
- Verify that employees can be searched via their Job title using the "Job Title" field
**Preconditions**
- User is currently on the PIM module
**Steps**
1. Select a job title from the drop down menu
2. Click the search button
**Expected Results**
- System should return a list of employees that hold the selected Job title

### OHRM-TC-024
**Description**
- Verify that employees can be search via their Sub unit using the "Sub Unit" field
**Preconditions**
- User is currently on the PIM module
**Steps**
1. Select a sub unit from the drop down menu
2. Click the search button
**Expected Results**
- System should return a list of employees that are under the selected sub unit

### OHRM-TC-025
**Description**
- Verify that applying multiple filters (e.g., Job Title + Status) returns correct results
**Preconditions**
- User is currently on the PIM module
- registered employee details
**Steps**
- Enter a valid empployee name
- Enter a valid Employee Id
- Enter the employee Job Title
- Enter employee status
**Expected Results**
- System returns the correct employee 