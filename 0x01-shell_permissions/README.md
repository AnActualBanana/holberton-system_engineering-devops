# Shell Permissions Project

## Overview
This project covers essential concepts of file and directory permissions in Linux. The scripts provided demonstrate how to modify user ownership, group ownership, and permission settings for files and directories.

### Files and Scripts

| Script/File | Description |
|------------|-------------|
| `0-iam_betty` | Switches the current user to "betty". |
| `1-who_am_i` | Prints the effective username of the current user. |
| `2-groups` | Displays the groups the current user belongs to. |
| `3-new_owner` | Changes the owner of the file `hello` to "betty". |
| `4-empty` | Creates an empty file called `hello`. |
| `5-execute` | Adds execute permission to `hello` for the owner. |
| `6-multiple_permissions` | Adds execute permission for the owner and group, and read permission for others on `hello`. |
| `7-everybody` | Grants execution permissions to all users on `hello`. |
| `8-James_Bond` | Sets `hello` permissions so that only others have all permissions. |
| `9-John_Doe` | Sets specific permissions (`-rwxr-x--x`) for `hello`. |
| `10-mirror_permissions` | Mirrors the permissions of one file onto another. |
| `11-directories_permissions` | Grants execute permission to all subdirectories of the current directory. |
| `12-directory_permissions` | Creates a directory with specific permissions (`751`). |
| `13-change_group` | Changes the group ownership of `hello` to "school". |
| `100-change_owner_and_group` | Changes the owner and group of multiple files. |
| `101-symbolic_link_permissions` | Changes the owner and group of a symbolic link. |

### Usage
To execute any script, use:
./script_name

### Ensure the script has execution permissions using:
chmod +x script_name

### Learning Objectives
Understanding file and directory permissions.
Changing user and group ownership.
Modifying read, write, and execute permissions.
Working with symbolic links and directories.

### Author
Logan McClain
