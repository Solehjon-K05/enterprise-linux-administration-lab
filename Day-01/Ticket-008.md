# Ticket 008 - Shared Project Permissions

## Objective
Enable collaborative access for the Falcon9 project.

## Tasks Performed
- Enabled the SetGID permission on the Falcon9 directory.
- Verified the permission change.

## Commands Used

```bash
sudo chmod g+s Falcon9
ls -ld Falcon9
```

## Outcome
New files created inside Falcon9 will inherit the Engineering group.

## Screenshot

![alt text](<Ticket-008 Configure Project Permissions.png>)