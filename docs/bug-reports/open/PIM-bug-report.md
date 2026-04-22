### BUG-003 – Inconsistent Search Results in PIM Module with Empty Filters

**Environment**
- Application: OrangeHRM Demo
- Browser: Google Chrome
- Device: Desktop

**Description**
When submitting the PIM search form with all fields empty, the number of employee records returned is inconsistent across multiple submissions. The inconsistency is also observed when navigating away from the module and returning.

**Preconditions**
- User is logged into the application
- User has access to the PIM module
- All search filters are cleared

**Steps to Reproduce**
1. Navigate to the PIM module
2. Ensure all search fields are empty
3. Click the Search button
4. Note the number of records displayed
5. Repeat steps 2–4 multiple times
6. Navigate to another module (e.g., Dashboard)
7. Return to the PIM module
8. Repeat the search

**Expected Result**
- The same number of employee records is consistently displayed when no filters are applied

**Actual Result**
- The number of records returned varies between searches under the same conditions

**Severity**
Medium

**Priority**
Medium

**Notes**
- Issue may be related to inconsistent data loading, caching, or pagination behavior
- Further investigation may be required to determine root cause