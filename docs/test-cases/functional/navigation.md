### OHRM-TC-026
**Description**
- Verify that the navigation search bar filters menu items based on user input
**Preconditions**
- User is currently signed in
**Steps**
1. Click on the navigation search bar
2. Enter the name of a menu item (e.g., "Admin")
**Expected Results**
- Only menu items matching the search input are displayed
- Non-matching menu items are hidden

### OHRM-TC-027
**Description**
- Verify that if a menu item that doesn'texist is searched no items are retuned
**Preconditions**
- User is currently signed in
**Steps**
1. Search for an item that is not on the menu list
**Expected Results**
- No item should be displayed on the menu

### OHRM-TC-028
**Description**
- Verify that the menu is collapsibleon desk top using the icon located on the side of the menu
**Preconditions**
- User is currently signed in
**Steps**
1. Click the chevron icon on the menu
**Expected Results**
- Menu should callapse when pressed

### OHRM-TC-029
**Description**
- Verify that each menu item navigates the user to the appropriate module
**Preconditions**
- User is currently signed in
**Steps**
1. Click on a menu item (e.g., "PIM")
2. Observe the page loaded
3. Repeat for each menu item
**Expected Results**
- User is redirected to the correct module page
- The page header matches the selected menu item