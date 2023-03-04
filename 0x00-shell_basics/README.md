# 0x00-shell-basics

### Scripts
#### 0-current_working_directory -> uses the `pwd` command to get the current working directory

#### 1-listit -> uses the `ls` command to list all files and folders in the current directory

#### 2-bring_me_home -> uses the `cd` command to change working directory to `/root`

#### 3-listfiles -> uses the `ls` command with flag `-l` to give a long listing of files

#### 4-listmorefiles -> uses the `ls` command with flags `-la` the flag `-a` to show the hidden files [files starting with `.`]

#### 5-listfilesdigitonly -> uses `ls -lan` command to give long listing of files & hidden files but with numeric user & group ID's

#### 6-firstdirectory -> uses `mkdir` command to create a directory named 'my_first_directory' inside 'temp' dir

#### 7-movethatfile -> uses the `mv` command to move the file 'betty' from 'temp' to '/temp/my_first_directory'

#### 8-firstdelete -> uses the `rm` command to remove file 'betty' in location '/temp/my_first_directory'

#### 9-firstdirdeletion -> uses `rm` command with flag `-r` to remove directory 'my_first_directory' in '/temp' dir

#### 10-back -> uses the `cd -` command to change to working directory to the previous one

#### 11-lists -> lists all the files (including hidden ones) in [current dir + parent dir + /boot dir] in long format

#### 12-file_type -> uses the `file` command to print the type of the file named 'iamafile' in '/temp' dir

#### 13-symbolic_link -> uses the `ln` command to create symbolic link to /bin/ls named "__ls__"

#### 14-copy_html -> it copies all the Html files from the current directory to the parent directory but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory using command `cp` with `-u` for only updating the parent directory and *.html to select html files only

#### 100-lets_move -> moves all files beginning with an uppercase letter to the directory /tmp/u using `mv` command with `[A-Z]*` option

#### 101-clean_emacs -> deletes all files in the current working directory that end with the character ~

#### 102-tree -> this script creats nested dirs using command `mkdir -p` the flag `-p` to be able to create nested dirs

#### 103-commas -> lists all the files and dirs in the current dirs alphaorderd, comma separated, and ends with new line, the . files is the at the top and dirs starts with /



## basic commands
- `pwd` - prints the current working directory to the stdout

- `ls`  - lists all files in the current directory (`ls <dirpath>` for other dirs)
- `ls -l` display files in long format and `ls -a` to show hidden files `ls -la` for both
- `ls -ln` to display users and groups ID's numerically

- `cd`  - used to navigate the system dirs 
- `cd ~` - goes to the home
- `cd ~-` - goes to the last working directory

- `mkdir` - used to create directories `mkdir <dirname>`

- `mv` - used to change file's and dir's location and rename them

- `rm` - used to remove files and dirs `rm <filepath>` `rm -r <dirpath>`

- `cp` - used to copy files
