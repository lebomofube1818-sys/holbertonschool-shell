# Permissions Project

This directory contains scripts that demonstrate different shell commands related to permissions in Linux.

## Scripts

- **0-iam_betty**  
  Script that switches the current user to the user `betty`.

- **1-who_am_i**  
  Script that prints the effective username of the current user.

- **2-groups**  
  Script that prints all the groups the current user is part of.

- **3-new_owner**  
  Script that changes the owner of the file `hello` to the user `betty`.

- **4-empty**  
  Script that creates an empty file called `hello`.

- **5-execute**  
  Script that adds execute permission to the owner of the file `hello`.

- **6-multiple_permissions**  
  Script that adds execute permission to the owner and the group owner, and read permission to others, for the file `hello`.

- **7-everybody**  
  Script that adds execution permission to the owner, the group owner, and other users, for the file `hello`.

- **8-James_Bond**  
  Script that sets the permission of the file `hello` so that only others have all the permissions, while the owner and group have none.

- **9-John_Doe**  
  Script that sets the mode of the file `hello` to `-rwxr-x-wx`.

- **10-mirror_permissions**  
  Script that sets the mode of the file `hello` to be the same as `olleh`.

- **11-directories_permissions**  
  Script that adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users.

- **12-directory_permissions**  
  Script that creates a directory called `my_dir` with permissions `751`.

- **13-change_group**  
  Script that changes the group owner of the file `hello` to `school`.

- **14-change_owner_and_group**  
  Script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory.

- **15-symbolic_link_permissions**  
  Script that changes the owner and group owner of the symbolic link `_hello` to `vincent` and `staff`.

- **16-if_only**  
  Script that changes the owner of the file `hello` to `betty` only if it is currently owned by `guillaume`.

