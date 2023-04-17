# P.I.Works

<figure>
    <img src="https://i.imgyukle.com/2023/04/17/QFCUdU.jpeg"
         alt="user interface specification document picture">
    <figcaption></figcaption>
</figure>

# User Management Interface Specification Document

## Requirements 
The user management interface should allow the user to:

- Add a new user
- Save a user
- Enable or disable a user
- Filter users by ID, username, email, and enable status
- Select user role from Admin, Guest, and Super Admin


## UI Components
The following UI components are required:

- A button labeled "+New User" is located in the top-left corner of the page
- A  checkbox with "Hide Disable user" label next to the "+ New User" button and it's ticked by default
- A "Save User" button in the top-right corner of the page
- A table with the following columns: ID, User Name, Email and Enable
- A filter icon next to each column header to filter by that column
- A "New User" section on the right side of the page


#### New User Form

- The right side of the page contains a form for adding a new user.
- The form includes the following fields:
    - Username: (text field)
    - Display Name: (text field)
    - Phone: (text field)
    - Email: (text field)
    - User Role: (combo box with options "Admin", "Guest", and "Super Admin")
    - Enabled: (checkbox)
    
#### User List

- The user list is divided into three columns: "ID", "User Name", and "Email".
- Each column has a filter icon next to its name, which allows the user to sort the list according to that column.
- A "Enable" column is also included, which contains a checkbox for each user that indicates whether they are enabled or disabled.

## Initial View
When the user first opens the user management interface, the table should be displayed with all the users listed. 
The "New User" section should be hidden, and the "Save User" button should be disabled. The "Hide Disable user" checkbox should be selected by default.

## Behavior
When the user clicks the "+ New User" button, the "New User" section on the right side of the page should be displayed, and the "Save User" button should become enabled.
If the "Hide Disable user" checkbox is selected, disabled users should not be shown in the table.
When the user enters values in the input fields and clicks the "Save User" button, the new user should be added to the table. The user should be able to filter the table by any of the columns.



