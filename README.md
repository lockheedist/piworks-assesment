# piworks-assesment
```markdown
# User Management Screen UI Specification

## Overview
This document outlines the specifications for the user management screen of our application. The user management screen allows administrators to view, add, edit, and delete user accounts.

## Requirements
1. Display a list of existing user accounts.
2. Allow administrators to add a new user account.
3. Enable administrators to edit existing user accounts.
4. Filter only enabled users.

## UI Components

### User List
- Display a table listing all existing user accounts.
- Include columns for user ID, username, email, enabled status as boolean.
- Allow sorting of user list based on different columns.

### New User Form
- Include input fields for username,display name, email, phone, user role and enabled box.
- User roles should include; Guest, Admin, SuperAdmin
- Implement validation for each field.
- Display appropriate error messages if validation fails.
- Include a "Save" button to add the new user.

### Save User Form
- Make it clickable after the inputs of new user form is filled.

## Page Behavior

### Initial Load
- Upon initial load, display the list of existing user accounts.
- Provide options to filter and order by.

### Add User
- When the "New User" button is clicked, display the New User form.
- Allow administrators to input user details and save the new user.
- After successful addition, refresh the user list to display the updated data.

## Conclusion
This document provides a detailed specification for the user management screen UI. Adhering to these specifications will ensure consistency and usability across the application.

```
