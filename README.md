# ALL LINUX COMMANDS CHEETSHEET

1)	ls Command: ls command is used to list the contents of a directory.
     Syntax: ls [option] 
•	we can specify option in ls commands
•	there are some predefined options, that is used to fetch the contents of a directory according to user’s need.
•	There are 6 options in ls command
-l, -r, -u, -s, -x, -R, -al
a)	-l option: It is used to list one file per line {which is default}   
b)	-r option: It is used to list file in reverse order
c)	-u option: It is used to list file according to file access time.
d)	-s option: It is used to list file according to file size in blocks
e)	-x option: It is used to list file sorted in rows across the screen
f)	      -R option: It is used to list subdirectories recursively.
g)	-al option: It is used to list all empty directory

2)	Clear command: Clear Commands is used to clear contents of the screen.
3)	Cat command: Cat command is used to make a file or to see contents of a file.
Syntax:  Cat filename

4)	Mkdir command: Mkdir command is used to make directory
     Syntax: Mkdir [option] directoryName
•	We can specify option in Mkdir command.
•	There are some predefined options in Mkdir command that is used to make directory according to user’s need
•	There are 2 options in Mkdir command:
-p and -m mode
a)	-p option: It is used to create parent directory, if parent directory do not exist.
b)	 -m mode: It is used to set access mode for new directory.


5)	Rmdir command: Rmdir is used to remove or delete empty directory from file system. We can check empty directories using ls -al command.
    Syntax: Rmdir directoryName

6)	Rm command: Rm command is used to remove or delete a file 
     Syntax: Rm [option] filename
•	We can specify option in rm command,
•	There are some predefined options in rm command that is used to delete a file according to user’s need.
•	There are 3 options in rm command:
-i, -r and -f 
a)	-i option: It is used to ask whether to delete each file.
b)	-r option: It delete the files and subDirectories associated with a directory
c)	-f option: It forcely remove the file, even if permission is not allowed


7)	Cp command: Cp command is used to copy the content of one file into another.
     Syntax: Cp sourceFile destinationFile
8)	Mv Command: Mv command is used to move file and directory from one directory to another.
        Syntax: Mv [option] sourceLocation destinationLocation
•	We can specify option in mv command.
•	There are predefined options that is used to move file/directory according to user’s need.
•	There are 4 options in mv command:
        -i, -f, -u, and -v
a)	-i option:  Using this option generate an interactive prompt that ask before overwriting destination file (if exist any)
b)	-f option: It is used to forcely move file by overwriting destination file without prompt
c)	-u option: It is used to update move when source is newer
d)	-v option: It is used to print source and destination file.

9)	Grep command: Grep command is used to search a particular pattern of character in a file and it returns all lines that contains those patterns.
      Syntax: grep [options] <pattern_of_characters> filename
•	We can specify option in grep command.
•	There are some predefined options that is used to returns pattern search result according to user’s need.
•	There are 5 options in grep command:
                -c, -h, -i, -l, -n and -v 
a)	-c options: It is used to print only no. of line that match the specified pattern
b)	-h option: It is used to display the matched line but not filename
c)	-i option: It ignore case of pattern during searching
d)	-n option: It is used to return matched line and line number too
e)	-v option: It is used to return all the lines that do not match the pattern.


10)	Chmod command: Chmod command is used to change the access mode of a file.
         Syntax: Chmod [reference][operator][mode] filename
a)	Reference: it is used to specify users to whom the permission apply
      There are 4 references, we can specify:
1.	u:  Owner 
2.	g: group member (users who are member of file group)
3.	o: others (users who are neither owner nor group member)
4.	a: all (all three of above)
b)	Operator: it is used to specify how mode will be adjusted
      There are 3 operators, we can specify:
1.	+:  It adds the specified mode to specified reference
2.	-: It removes the specified mode from specified reference
3.	=: It specifies mode is permitted exact to specified reference.
c)	Mode: It is used to specify which permission is to be grated or removed from the specified reference.
      There are 3 modes, we can specify:
1.	r: read mode (Permission to read the file)
2.	w: write mode (Permission to write the file)
3.	x: execute mode (Permission to execute the file)

11)	Sort command: Sort command is used to sort records of a file.
         Syntax: sort filename

12)	Touch command: like cat command, Touch command is also used to create file.
              But file created using Touch command will be empty.
            Syntax: touch filename
            To edit the file created, we use vi command.
            Syntax: vi fileName

13)	File command: File command is used to print type of file
           Syntax: file fileName

14)	Pwd command: pwd command is used to display current directory
15)	History command: history command is used to list all the previously used commands 

16)	Who command: Who command is used to list the name of all users currently logged into system. 
                         Syntax: who [option] 
•	We can specify option in who command
•	There are some predefined options, that is used to list the users according to our requirement.
•	There are 4 options in who command:
-b, -l, -s and -u
a.	-b option: it is used to display when system is last booted
b.	-l option: it is used to list the terminal that no one is logged in
c.	-s option: it is used to display name of user, login time and terminal
d.	-u option: it is used to list only current user

17)	Date command: Date command is used to display current date and time, only superuser can change the date
           Syntax: date nnddhhmmss[ccyy]
                  Here, nn: no. of month
                           dd: no. of day
                           hh: no. of hour
                           mm: no. of minute
                            ss: no. of seconds
                            cc: no. of century
                            yy: no. of year


18)	Cal command: cal command is used to display calender for current month and year
        Syntax: cal [month no.] [year] 
    
