#  0x01. Shell, permissions 

In this project, I learnt the functions of commands like `chmod`, `sudo`, `su`, `chown`, `chgrp` etc...

## Tasks :page_with_curl:

**Task 0**: The [0-iam_betty](./0-iam_betty) file contains a script that switches the current user to the user `betty`

**Task 1**: The [1-who_am_i](./1-who_am_i) file contains a script that prints the effective username of the current user.

**Task 2**: The [2-groups](./2-groups) file contains a script that prints all the groups the current user is part of.

**Task 3**: The [3-new_owner](./3-new_owner) file contains  a script that changes the owner of the file `hello` to the user `betty`

**Task 4**: The [4-empty](./4-empty) file contains a script that creates an empty file called `hello`.

**Task 5**: The [5-execute](./5-execute) file contains a script that adds execute permission to the owner of the file `hello`.

**Task 6**: The [6-multiple_permissions](./6-multiple_permissions) file contains a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.

**Task 7**: The [7-everybody](./7-everybody) file contains a script that adds execution permission to the owner, the group owner and the other users, to the file `hello`
 
**Task 8**: The [8-James_Bond](./8-James_Bond) file contains a script that sets the permission to the file `hello` as follows:

   * Owner: no permission at all
   * Group: no permission at all
   * Other users: all the permissions

**Task 9**: The [9-John_Doe](./9-John_Doe) file contains  a script that sets the mode of the file `hello` to this:

   * `-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello`
   * The file `hello` will be in the working directory

**Task 10**: The [10-mirror_permissions](./10-mirror_permissions) file contains a script that sets the mode of the file `hello` the same as `olleh’s` mode.

   * The file `hello` will be in the working directory
   * The file `olleh` will be in the working directory

**Task 11**: The [11-directories_permissions](./11-directories_permissions) file contains a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.

**Task 12**: The [12-directory_permissions](./12-directory_permissions) file contains a script that creates a directory called `my_dir` with permissions 751 in the working directory.

**Task 13**: The [13-change_group](./13-change_group) file contains a script that changes the group owner to `school` for the file `hello`

**Task 14**: The [100-change_owner_and_group](./100-change_owner_and_group) file contains a script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory.

**Task 15**: The [101-symbolic_link_permissions](./101-symbolic_link_permissions) file contains a script that changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively.

   * The file `_hello` is in the working directory
   * The file `_hello` is a symbolic link

**Task 16**: The [102-if_only](./102-if_only) file contains a script that changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`.

**Task 17**: The [103-Star_Wars](./103-Star_Wars) file contains a script that will play the StarWars IV episode in the terminal.
 
