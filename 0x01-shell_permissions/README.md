This readme contains description of all the files(scripts) in this "0x01-shell_permissions" directory.

0-iam_betty: Script that switches the current user to the user "betty".

1-who_am_i: Script that prints the effective username of the current user.

2-groups: Script that prints all the groups the current user is part of.

3-new_owner: Script that changes the owner of the file "hello" to the user "betty".

4-empty: Script that creates an empty file called "hello".

5-execute: Script that adds execute permission to the owner of the file "hello".

6-multiple_permissions: Script that adds execute permission to the owner and the group owner, and read permission to other users, to the file "hello".

7-everybody: script that adds execution permission to the owner, the group owner and the other users, to the file "hello".

8-James_Bond: Script that sets the permission to the file "hello" to only "others" having all permissions. 

9-John_Doe: script that sets the mode of the file "hello" to "-rwxr-x-wx".

10-mirror_permissions:  Script that sets the mode of the file "hello' the same as olleh’s mode.

11-directories_permissions: Script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Without changing regular files. 

12-directory_permissions: Script that creates a directory called "my_dir" with permissions "751" in the working directory.

13-change_group: Script that changes the group owner to "school" for the file "hello". 

100-change_owner_and_group: Script that changes the owner to "vincent" and the group owner to "staff" for all the files and directories in the working directory.

101-symbolic_link_permissions: Script that changes the owner and the group owner of "_hello" which is a symbolic link to "vincent" and "staff" respectively.

102-if_only:  Script that changes the owner of the file "hello" to "betty"  only if it is owned by the user "guillaume".

103-Star_Wars: Script that  plqys the StarWars IV episode in the terminal.

