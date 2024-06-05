User Management Screen Specification

Overview
The User Management Screen is designed to facilitate the management of users in the system. It allows administrators to create, view, edit, and enable/disable users. This document outlines the requirements, UI components, behavior, and initial display of the user management interface.

Requirements
User List: Display a list of users with their details.
New User Creation: Provide a form to add new users.
Edit User: Allow editing of existing user details.
Enable/Disable User: Allow toggling the enabled status of users.
Hide Disabled Users: Option to hide disabled users from the list.
UI Components
User List
Table Columns:

ID: Unique identifier for each user.
User Name: The username of the user.
Email: The user's email address.
Enabled: Status indicating if the user is enabled or disabled.
Table Actions:

Sortable columns for ID, User Name, Email, and Enabled status.
Checkbox to hide/show disabled users.
New User Form
Fields:

Username: Text input for the username.
Display Name: Text input for the user's display name.
Phone: Text input for the user's phone number.
Email: Text input for the user's email address.
User Roles: Dropdown to select user roles (Guest, Admin, SuperAdmin).
Enabled: Checkbox to set the user's enabled status.
Buttons:

Save User: Button to save the new or edited user details.
New User: Button to clear the form and prepare for new user creation.
Checkbox
Hide Disabled User: Checkbox to filter out disabled users from the user list.
Page Behavior
Initial Display
User List:
Display all users in a table.
By default, all users, both enabled and disabled, are shown.
New User Form:
The form is initially empty and ready for new user data entry.
"User Roles" dropdown defaults to "Guest".
"Enabled" checkbox is unchecked by default.
Interactions
Add New User:

Click "New User" button.
Fill in the details in the "New User" form.
Click "Save User" to add the user to the list.
Edit User:

Select a user from the list.
The selected user's details populate the form.
Modify the desired fields.
Click "Save User" to update the user's details.
Enable/Disable User:

Select a user from the list.
Toggle the "Enabled" checkbox.
Click "Save User" to apply the changes.
Hide Disabled Users:

Check the "Hide Disabled User" checkbox.
The user list updates to show only enabled users.
Visual Feedback
Success Message: Display a success message upon successful addition or update of a user.
Error Message: Display an error message if there is an issue with saving the user details.
Example UI State
Initial State
User List: Shows all users with sortable columns.
New User Form: Empty fields ready for new data entry.
Hide Disabled User: Checkbox is unchecked.
After User Addition
User List: Updates to include the new user.
New User Form: Clears the form for potential additional entries.
Success Message: "User successfully added" displayed briefly.
