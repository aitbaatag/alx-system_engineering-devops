# shell permissions command

<br>

#### su
script that switches the current user to another user
<br> <br>

#### whoami
script that prints the effective username of the current user
<br> <br>

#### groups
script that prints all the groups the current user is part of
<br> <br>

#### chown
The owner (and the root user) can change the
owner to another user, too, using the chown
command
<br> <br>

#### touch hello
script that creates an empty file called hello
<br> <br>

#### chmod u+x hello
script that adds execute permission to the owner of the file hello
<br> <br>

#### chmod ug+x,o+r hello
script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
<br> <br>

#### chmod ugo+x hello
script that adds execution permission to the owner, the group owner and the other users, to the file hello
<br> <br>

#### chmod 007 hello
script that sets the permission to the file hello as follows:
Owner: no permission at all
Group: no permission at all
Other users: all the permissions
<br> <br>

#### chmod 753 hello
script that sets the mode of the file hello to this:
```
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
```
<br> <br>

#### chmod --reference=olleh hello
cript that sets the mode of the file hello the same as olleh’s mode
<br> <br>

#### chmod -R +X .
script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users
<br> <br>

#### mkdir -m 751 my_dir
script that creates a directory called my_dir with permissions 751 in the working directory
<br> <br>

#### chgrp school hello
script that changes the group owner to school for the file hello
<br> <br>

<h4> chown vincent:staff * </h4> script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
<br> <br>

#### chown -h vincent:staff _hello
script that changes the owner and the group owner of _hello to vincent and staff respectively
<br> <br>

#### chown --from=guillaume betty hello
script that changes the owner of the file hello to betty only if it is owned by the user guillaume
<br> <br>

#### telnet towel.blinkenlights.nl
script that will play the StarWars IV episode in the terminal
