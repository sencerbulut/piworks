*****User Management Screen*****

**Requirements**

- The user management screen should allow an administrator to view and add  users to the system.
- The user management screen should display the following information for each user:
  - Username
  - Display Name
  - Phone
  - Email
  - User Roles (e.g. "Guest", "Admin",” SuperAdmin”)
  - Enabled (e.g. "true", "false")
- The user management screen should allow the administrator to filter the list of users by ID, Username, Email, or Enabled.
- The user management screen should allow the administrator to sort the list of users by name, email, role, or status.

**UI Components**

- **New User Button**: A button that opens a modal window allowing the administrator to add a new user to the system.
- **Save User Button**: A button that closes a modal window allowing the administrator to save the details of an existing user.
- **Filter** :A filter field that allows the administrator to filter the list of users by User ID, Name, Email, or Enabled.
- **Sort Selector**: A sort selector that allows the administrator to sort the list of users by ID, User Name, Email, or Enabled.

**Behavior**

- When the administrator clicks the **Add User** button, a modal window should appear with a form for the administrator to enter the following details for the new user:
  - Username
  - Display Name
  - Phone
  - Email
  - User Roles 
  - Enabled 
- When the administrator clicks the **Save User** button, a modal window should close with a form pre-populated with the details of the new user. The administrator should be able to save the new user.
- When the administrator types in the **Filter Input Field**, the list of users should be filtered in real-time based on the input value.
- When the administrator selects an option in the **Sort Selector**, the list of users should be sorted accordingly.

**Initial Display**

- When the user management screen is first displayed, the list of users should be displayed in the order they were added to the system, with the most recently added user at the top.
- The default **Filter** should be empty and **Sort Selector** should be ID.

