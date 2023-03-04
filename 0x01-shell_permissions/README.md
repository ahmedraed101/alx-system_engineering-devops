# 0x01-shell_permissions

## Scripts

### 0-iam_betty -> switches the current user to the user betty using command `su <username>`

### 1-who_am_i -> prints the effective username of the current user - command `whoami`

### 2-groups -> prints all the groups the current user is part of - command `groups`

### 3-new_owner -> changes the owner of the file hello to the user betty - command `sudo chown betty hello`

### 4-empty -> creates an empty file called hello - command `touch`

### 5-execute -> adds execute permission to the owner of the file hello - command `chmod u+x`

### 6-multiple_permissions -> adds execute permission to the owner and the group owner, and read permission to other users, to the file hello - command `chmod ug+x,o+r <filename>`

### 7-everybody -> adds execution permission to the owner, the group owner and the other users, to the file hello - command `chmod a+x`

### 8-James_Bond -> sets the permission to the file hello as follows: 
- Owner: no permission at all
- Group: no permission at all
- Other users: all the permissions
command `chmod 007 <filename>`


### 9-John_Doe -> sets the mode of the file hello to '-rwxr-x-wx' - command `chmod 753`

### 10-mirror_permissions - >sets the mode of the file hello the same as olleh’s mode. - command `chmod --reference=olleh hello`

### 11-directories_permissions -> adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users - command `chmod -R a+X`

### 12-directory_permissions -> creates a directory called my_dir with permissions 751 in the working directory - command `mkdir -m 751 my_dir`

### 13-change_group -> changes the group owner to school for the file hello - command `chgrp school hello`

### 100-change_owner_and_group ->  changes the owner to vincent and the group owner to staff for all the files and directories in the working directory - command `chown -R vincent:staff .`

### 101-symbolic_link_permissions -> changes the owner and the group owner of _hello to vincent and staff respectively. - command `chown -h vincent:staff _hello`

### 102-if_only -> hanges the owner of the file hello to betty only if it is owned by the user guillaume - command `chown --from=guillaume betty hello`

### 103-Star_Wars ->  play the StarWars IV episode in the terminal - command `telnet towel.blinkenlights.nl`

