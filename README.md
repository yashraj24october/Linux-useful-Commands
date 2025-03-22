# ALL LINUX COMMANDS CHEETSHEET

1)	ls Command: ls command is used to list the contents of a directory.<br>
     Syntax: ls [option] <br>
•	we can specify option in ls commands <br>
•	there are some predefined options, that is used to fetch the contents of a directory according to user’s need.<br>
•	There are 6 options in ls command<br>
-l, -r, -u, -s, -x, -R, -al <br>
a)	-l option: It is used to list one file per line {which is default}   <br>
b)	-r option: It is used to list file in reverse order <br>
c)	-u option: It is used to list file according to file access time. <br>
d)	-s option: It is used to list file according to file size in blocks <br>
e)	-x option: It is used to list file sorted in rows across the screen <br>
f)	-R option: It is used to list subdirectories recursively. <br>
g)	-al option: It is used to list all empty directory. <br>

2)	Clear command: Clear Commands is used to clear contents of the screen.<br>
3)	Cat command: Cat command is used to make a file or to see contents of a file.<br>
Syntax:  Cat filename<br>

4)	Mkdir command: Mkdir command is used to make directory <br>
     Syntax: Mkdir [option] directoryName <br>
•	We can specify option in Mkdir command. <br>
•	There are some predefined options in Mkdir command that is used to make directory according to user’s need <br>
•	There are 2 options in Mkdir command: <br>
-p and -m mode <br>
a)	-p option: It is used to create parent directory, if parent directory do not exist. <br>
b)	-m mode: It is used to set access mode for new directory. <br>
<br>
<br>
5)	Rmdir command: Rmdir is used to remove or delete empty directory from file system. We can check empty directories using ls -al command.<br>
    Syntax: Rmdir directoryName <br>

6)	Rm command: Rm command is used to remove or delete a file  <br>
     Syntax: Rm [option] filename <br>
•	We can specify option in rm command, <br>
•	There are some predefined options in rm command that is used to delete a file according to user’s need. <br>
•	There are 3 options in rm command: <br>
-i, -r and -f  <br>
a)	-i option: It is used to ask whether to delete each file. <br>
b)	-r option: It delete the files and subDirectories associated with a directory <br>
c)	-f option: It forcely remove the file, even if permission is not allowed <br>


7)	Cp command: Cp command is used to copy the content of one file into another. <br>
     Syntax: Cp sourceFile destinationFile <br>
8)	Mv Command: Mv command is used to move file and directory from one directory to another. <br>
        Syntax: Mv [option] sourceLocation destinationLocation <br>
•	We can specify option in mv command. <br>
•	There are predefined options that is used to move file/directory according to user’s need. <br>
•	There are 4 options in mv command: <br>
        -i, -f, -u, and -v <br>
a)	-i option:  Using this option generate an interactive prompt that ask before overwriting destination file (if exist any) <br>
b)	-f option: It is used to forcely move file by overwriting destination file without prompt <br>
c)	-u option: It is used to update move when source is newer <br>
d)	-v option: It is used to print source and destination file. <br>

9)	Grep command: Grep command is used to search a particular pattern of character in a file and it returns all lines that contains those patterns. <br>
      Syntax: grep [options] <pattern_of_characters> filename <br>
•	We can specify option in grep command. <br>
•	There are some predefined options that is used to returns pattern search result according to user’s need. <br>
•	There are 5 options in grep command: <br>
                -c, -h, -i, -l, -n and -v <br>
a)	-c options: It is used to print only no. of line that match the specified pattern <br>
b)	-h option: It is used to display the matched line but not filename <br>
c)	-i option: It ignore case of pattern during searching <br>
d)	-n option: It is used to return matched line and line number too <br>
e)	-v option: It is used to return all the lines that do not match the pattern. <br>

<br>
<br>
<br>

10)	Chmod command: Chmod command is used to change the access mode of a file. <br>
         Syntax: Chmod [reference][operator][mode] filename <br>
a)	Reference: it is used to specify users to whom the permission apply <br>
      There are 4 references, we can specify: <br>
1.	u:  Owner  <br>
2.	g: group member (users who are member of file group) <br>
3.	o: others (users who are neither owner nor group member) <br>
4.	a: all (all three of above) <br>
b)	Operator: it is used to specify how mode will be adjusted <br>
      There are 3 operators, we can specify: <br>
1.	+:  It adds the specified mode to specified reference <br>
2.	-: It removes the specified mode from specified reference <br>
3.	=: It specifies mode is permitted exact to specified reference. <br>
c)	Mode: It is used to specify which permission is to be grated or removed from the specified reference. <br>
      There are 3 modes, we can specify: <br>
1.	r: read mode (Permission to read the file) <br>
2.	w: write mode (Permission to write the file) <br>
3.	x: execute mode (Permission to execute the file) <br>
<br>
<br>
11)	Sort command: Sort command is used to sort records of a file. <br>
         Syntax: sort filename <br>
<br>
<br>
12)	Touch command: like cat command, Touch command is also used to create file. <br>
              But file created using Touch command will be empty. <br>
            Syntax: touch filename <br>
            To edit the file created, we use vi command. <br>
            Syntax: vi fileName <br>
<br>
<br>

13)	File command: File command is used to print type of file  <br>
           Syntax: file fileName <br>

14)	Pwd command: pwd command is used to display current directory <br>
<br>
15)	History command: history command is used to list all the previously used commands  <br><br>

16)	Who command: Who command is used to list the name of all users currently logged into system.  <br>
                         Syntax: who [option] <br>
•	We can specify option in who command<br>
•	There are some predefined options, that is used to list the users according to our requirement.<br>
•	There are 4 options in who command:<br>
-b, -l, -s and -u <br>
a.	-b option: it is used to display when system is last booted<br>
b.	-l option: it is used to list the terminal that no one is logged in<br>
c.	-s option: it is used to display name of user, login time and terminal<br>
d.	-u option: it is used to list only current user<br>
<br>
<br>
17)	Date command: Date command is used to display current date and time, only superuser can change the date<br>
           Syntax: date nnddhhmmss[ccyy] <br>
                  Here, nn: no. of month<br>
                           dd: no. of day<br>
                           hh: no. of hour<br>
                           mm: no. of minute<br>
                            ss: no. of seconds<br>
                            cc: no. of century<br>
                            yy: no. of year<br>
<br><br><br>

18)	Cal command: cal command is used to display calender for current month and year<br>
        Syntax: cal [month no.] [year] <br><br><br>
    
