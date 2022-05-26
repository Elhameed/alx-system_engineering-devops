**Task-0**:The `0-current_working_directory` file contains script that prints the absolute path name of the current working directory.`pwd`

**Task-1**:The `1-listit` file contains the script that displays the content list of the working directory.`ls`

**Task-2**:The `2-bring_me_home` file contains a script that changes the working directory to the user’s home directory.`cd -`

**Task-3**:The `3-listfiles` contains a sript which displays current directory contents in a long format.`ls -l`

**Task-4**:The `4-listmorefiles` contain a script to display current directory contents, including hidden files (starting with .) using long format.`ls -la`

**Task-5**:The 5-listfilesdigitonly contains a script on how to display directory contents with user and group ids displayed numerically, showing hidden files in long format.`ls -n -la`

**Task-6**:The 6-firstdirectory file contains a script that creates a directory named `my_first_directory` in the `/tmp/` directory.`mkdir` `/tmp/betty` `/tmp/my_first_directory`

**Task-7**:The `7-movethatfile` file displays a script to move the file `betty` from `/tmp/` to `/tmp/my_first_directory`.

**Task-8**:The `8-firstdelete` file displays a script to delete the file `betty`.

**Task-9**:The `9-firstdirdeletion` file displays a script to delete the directory `my_first_directory` that is in the `/tmp` directory.

**Task-10**:The `10-back` file contains script that changes the working directory to the previous one.

**Task-11**:The `11-lists` file contains a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the `/boot` directory (in this order), in long format

**Task-12**:The `12-file_type` contains a script that prints the type of the file named `iamafile`. The file `iamafile` will be in the `/tmp` directory when the script is run.

**Task-13**:The `13-symbolic_link` contains a script that creates a symbolic link to `/bin/ls`, named `__ls__`.

**Task-14**:The `14-copy_html` file contains a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

**Task-15**:The `100-lets_move` file contains a script that moves all files beginning with an uppercase letter to the directory `/tmp/u`.

**Task-16**:The `101-clean_emacs` file contains a script that deletes all files in the current working directory that end with the character `~`.

**Task-17**:The `102-tree` file contains a script that creates the directories `welcome/`, `welcome/to/` and `welcome/to/school` in the current directory.

**Task-18**:The `103-commas` file contains  a command that lists all the files and directories of the current directory, separated by commas (`,`). Given that;
- Directory names should end with a slash (`/`)

- Files and directories starting with a dot (`.`) should be listed

- The listing should be alpha ordered, except for the directories `.` and `..` which should be listed at the very beginning

- Only digits and letters are used to sort; Digits should come first

- You can assume that all the files we will test with will have at least one letter or one digit

- The listing should end with a new line

**Task-19**:The `school.mgc` is a magic file `school.mgc` that can be used with the command `file` to detect `School` data files. `School` data files always contain the string `SCHOOL` at offset 0.
