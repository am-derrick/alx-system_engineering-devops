This repo directory contains scripts and what tasks they perform:
0-iam_betty changes the user to betty
1-who_am_i prints current username
2-groups shows the groups the user is in
3-new_owner changes owner of the file hello to betty
4-empty creates an empty file named hello
5-execute adds execute permission to the owner of the file hello
6-multiple_permissions adds execute permissions to owner and group owner and read permission to other user
7-everybody adds execution permissions to the owner, group owner and other users.
8-James_Bond grants no permission to th owner and owner group but grants all permission to other users
9-John_Doe grants the following permissions: -rwxr-x-wx
10-mirror_permissions sets mode permissions of file hello the same as olleh
11-directories_permissions grants execute permissions to all subdirectories for owner, groups and users
12-directory_permissions makes a directory and grants permissions 751
13-change_group changes group owner of the file hello to holberton
100-change_owner_and_group changes the owner to betty and group owner to holberton for all files and directories
101-symbolic_link_permissions changes owner and group owner of _hello to betty and holberton respectively
102-if_only changes owner to betty if and only if file hello belongs to guillaume
103-Star_Wars plays Star wars episode IV in terminal