# Unix

Unix repo contains some useful commands we normally used.


## Unix Notes: Day 1
Windows vs Unix: no virus, good performance
Windows : will have the client tools only, Client Software like Putty as well as Cigwin, sql developers, 
Unix: All server softwares are installed.

Cigwin SW provide Unix system without installing unix OS, so that we can practice Unix commands.

Unix: CUI, 1970 developed in C
Windows: GUI

Unix Required. less resource
Unix Flavors: Linux(CUI+GUI): Micorsoft, IBM, Oracle, Ubuntu, Fedora, Open 

Unix Features:
- Multiuser Capability:
- Multitasking Capability
- Program Facility
- Portability
- Communication 
- Security: log in, Permission on file for User, File Encryption -> Decryption, 

Unix Architecture:
User -> SHELL : Utilities, Applicaitons -> KERNEL -> Hardware
SHELL is the utility the process user command., SHELL interpret the command.(takes the request and giving response to user).
KERNEL  : manage the data in hardware, manage memory, file system, scheduling
SHELL: C SHELL, SH SHELL, BASS SHELL,

Unix OS is also called File Operating System.
Files, 
Folder, 
Special Files : Character Special File, Block Special Files, 
Windows: Administrator User by default create
- bin, temp, etc folder can see

Unix: Root User by default create
- / (root), /lib, /dev, /user, /usr, /tmp, /etc, /var, /home

SHELL Program are nothing but collection of Unix commands.
/home directory every user has their one directory

## Unix Note: Day 2
Under which SHELL you are working.
#### command: echo $0
change to SHELL
#### command: csh
#### command: ksh
Cygwin dont have many SHELLs as with Unix Server
login SHELL vs Current SHELL
#### command: echo $SHELL
#### command: man ls
#### command: man cat
man vd --help command: man is real, help is shortcut.

Date: 
 

command for CAL:

 

know server name: host name;
 

create 0 byte file
 

## Unix Note: Day 3
Commands: 
#### cat : command to create and view the file
To create file
$ cat > type your text once done do -> cntrl+d : save and exit
 
To See the content of file with line number.
 
To concatenate content of all specified file into new file
 
To display every file in single column
 

 
To display in reverse order
 

To create hidden files
#### cat >.filename
 

To display hidden file
 
- means reg. file, d for directory
 

Permission
 
r read
w write
x execute

To display all files the files which starts from a, display file which end at l
 
To display the files with three and 4 char
 
 

To see the data of directory : ls command
To See the data of file : cat command

 

To check perticular file with full details 
 

change the permission
 


 

 

change the permission of file with number 
 

 
 
 


To Create File : cat >[file_name]
then enter the text to be enter. Then Ctrl+d to save and exit

To edit the existing file: nano [file_name]
then edit the file text per requrement. Then Ctrl+o to save, then press Enter, then Ctrl+x to exit.
Note: This command doesn't works in cygwin.


## Unix Note: Day 4
Copy or move files
#### Copy: $ cp file_name directory_name
 

with copy command you can also create new file. 
#### $ cp oldfile_name new_file_name
 

copy directory
cp -r (mean recursive including all files and sub directores).
 
Command : more -> Display page full of file content.
 
This will display content of the a1 file
space-> next page
enter -> next line
Command : less -> more options 
b = backward
g =  last page
f = forwad 

#### Command: head
top 10 lines will dispay by default, we can also limit them as shown below.
 
#### Command tail : similar in tail 
 
specific lines: want to see lets say line no: 25
 

## Unix Note : Day 5
#### Command : cd (change directory)
create sub directory under directory

#### Command: mv -> you can rename of file or dir, move the files.
 

 

#### Command: wc (word count)
 

#### Command: cd, cd.., cd ../.. (jump out of parent directory)

#### Remove: 
$rm directory(empty), rm file, rm -r <directory>
$rm a1 a2 a3 (remove multiple files)
$rm -i tula (i for interactive)

#### Search command
#### grep : globely search reg expression and print
 
-i is for ignore the case
- w
- v
Q. Which are the lines begin with?
Use this command: 
#### grep ^..$
^ : start with
..: two char
#### grep -c  '^$' : find the count of space in files

Find how many files in the current directory
#### ls -l  | grep ^- |wc -l
 









