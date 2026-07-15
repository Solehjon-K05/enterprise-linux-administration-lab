# Ticket 004 - Create Linux User

## Objective
Create a Linux user account for a new employee.

## Tasks Performed
- Created a new user account.
- Assigned Bash as the default shell.
- Set a password.
- Verified the account.

## Commands Used

```bash
sudo useradd -m -s /bin/bash sjhonson
sudo passwd sjhonson
id sjhonson
```

## Expected Result

The user account should exist and display its UID, GID, and group membership.

## Outcome
The user account was successfully created and verified.

![alt text](<Ticket-004 Create New Linux User.png>)