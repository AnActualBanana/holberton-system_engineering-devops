# Overview
This project contains a collection of basic shell scripts and commands designed to improve familiarity with Linux command-line operations. The scripts cover navigation, file management, permissions, and symbolic links.

## Files and Scripts

| Script/File | Description |
|------------|-------------|
| `0-current_working_directory` | Prints the absolute path of the current working directory. |
| `1-listit` | Lists files in the current directory. |
| `2-bring_me_home` | Changes the working directory to the user's home directory. |
| `3-listfiles` | Lists all files (including hidden ones) in long format. |
| `4-listmorefiles` | Lists all files (including hidden ones). |
| `5-listfilesdigitonly` | Displays files in long format with user and group IDs shown numerically. |
| `6-firstdirectory` | Creates a directory named `my_first_directory` in `/tmp/`. |
| `7-movethatfile` | Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory/`. |
| `8-firstdelete` | Deletes the file `betty` in `/tmp/my_first_directory/`. |
| `9-firstdirdeletion` | Deletes the directory `my_first_directory` in `/tmp/`. |
| `10-back` | Changes the working directory to the previous one. |
| `11-lists` | Lists all files in multiple directories. |
| `12-file_type` | Prints the type of a given file. |
| `13-symbolic_link` | Creates a symbolic link named `__ls__` to `/bin/ls`. |
| `14-copy_html` | Copies all `.html` files from the current directory to the parent directory, only copying newer versions. |

### Usage
To execute any script, use:
./script_name

Ensure the script has execution permissions using:
chmod +x script_name

### Learning Objectives
Understanding shell navigation and directory structure.
Using ls, cd, pwd, and other essential commands.
Managing files and directories (create, move, delete).
Handling file permissions and symbolic links.

### Author
Logan McClain
