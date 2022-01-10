# 0x01. Shell, permissions

---

## Learning Objectives
*At the end of this project:, I will be able to explain:*
- What the commands 'chmod', 'sudo', 'su', 'chown', and 'chgrp' do;
- Linux file permissions;
- How to represent each of the three sets of permissions as a single digit;
- How to change permissions, owner, and group of a file;
- Why a normal user can't 'chown' a file
- How to run a command with root privileges; and
- How to change the user ID or become the superuser.

---

## Requirements
- Allowed editors: 'vi', 'vim', 'emacs'
- All scripts will be tested on Ubuntu 20.04 LTS
- All scripts should be exactly two lines long
- All files should end with a new line
- The first line of all files should be '#!/bin/bash'
- A 'README.md' file (that's you!) at the root of the folder of the project, describing what each script is doing
- No use of backticks, '&&', '||', or ';'
- All files must be executable

---

## Tasks

### 0.My name is Betty
*Create a script that switches the current user to the user 'betty'.*

### 1.Who am I
*Write a script that prints the effective username of the current user.*

### 2.Groups
*Write a script that prints all the groups the current usr is part of.*

### 3.New owner
*Write a script that changes the owner of the file 'hello' to the user 'betty'.*

### 4.Empty!
*Write a script that creates an empty file called 'hello'.*

### 5.Execute
*Write a script that adds execute permission to the owner of the file 'hello'.

### 6.Multiple permissions
*Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file 'hello'.*

### 7.Everybody!
*Write a script that adds execution permission to the owner, the group owner and the other users, to the file 'hello'.*

### 8.James Bond
*Write a script that sets the permission to the file 'hello' as follows:*
*-Owner: no permission at all*
*-Group: no permission at all*
*-Other users: all the permissions*

### 9.John Doe
*Write a script that sets the mode of the file 'hello' to this:*
'-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello'

### 10.Look in the mirror
*Write a script that sets the mode of the file 'hello' to the same as 'olleh''s mode.*

### 11.Directories
*Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users. Regular files should not be changed.*

### 12.More directories
*Create a script that creates a directory called 'my_dir' with permissions 751 in the working directory.*

### 13.Change group
*Write a script that changes the group owner to 'school' for the file 'hello'.*