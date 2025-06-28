# Permissions

The scripts for permissions.

## Scripts

| Script | Description |
|--------|-------------|
| 0-iam_betty | Switches the current user to the user `betty`. |
| 1-who_am_i | Prints the effective username of the current user. |
| 2-groups | Prints all the groups the current user is part of. |
| 3-new_owner | Changes the owner of the file `hello` to the user `betty`. |
| 4-empty | Empties the content of the file `hello`. |
| 5-execute | Adds execute permission to the owner of the file `hello`. |
| 6-multiple_permissions | Adds execute permission to the owner and group owner, and read permission to others. |
| 7-everybody | Adds read, write, and execute permission to the owner, group, and others. |
| 8-James_Bond | Sets permissions to `--x--x--x`. |
| 9-John_Doe | Sets permissions to `-rwxr-x-wx`. |
| 10-mirror_permissions | Sets permissions of the file `hello` to match those of the file `olleh`. |
| 11-directories_permissions | Adds execute permission to all subdirectories for the user. |
| 12-directory_permissions | Creates a directory named `my_dir` with permissions `751`. |
| 13-change_group | Changes the group owner of the file `hello` to `school`. |

## Usage

Each script is 2 lines long, starts with `#!/bin/bash`, and is executable. To run any script:
```bash
./script_name
