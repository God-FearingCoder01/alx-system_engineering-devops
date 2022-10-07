#Explanations of what each file in this project folder does/is for.

1. 0-current_working_directory - prints the absolute path name of the current working directory.
2. 1-listit - displays the contents of your current working directory.
3. 2-bring_me_home - chenges the working directory to the user's home directory
4. 3-listfiles - displays the current working directory's contents in a long format.
5. 4-listmorefiles - displays current directory contents, including the hidden files (i.e. files that start with a period or a dot), using the long format.
6. 5-listfilesdigitonly - displays the current working directory's contents in long format, with user and group IDs displayed numerically and the hideen files also shown too.
7. 6-firstdirectory - creates a directory called my\_first\_directory, in the /tmp/ directory.
8. 7-movethatfile - moves the file names {betty} from the directory **/tmp** to the one called **/tmp/my_first_directory**.
9. 8-firstdelete - deletes the file named betty from the directory **/tmp/my_first_directory**.
9-firstdirdeletion - deleted the directory with the name **/tmp/my_first_directory** .
10-back - changes the current working directory to the previous one.
11-lists - lists all files in the current working directory and its parent and in the /boot directory (in that order) using a long format and including all hidden files.
12-file\_type prints the type of the file named 'iamafile' which is in the directory '/tmp' .
13-symbolic link - creates a symbolic link to '/bin/ls' , named '__ls__' in the current working directory.
14-copy\_html - copies all the HTML files in the current working directory, but only copies those that did not exist in the parent of the working  directory or tat where newer than the versions in the parent of the working directory.
*[HTML]: HyperText Markup Language
100-lets_move - moves all files beginning with an uppercase letter to the directory '/tmp/u' *{assuming that the directory '/tmp/u' already exists.'
101-clean\_emacs - deletes all files in the current working directory that end with the character '~' 
102-tree - creates the directories 'welcome/ , 'welcome/to/' and 'welcome/to/school'
103-commas - lists all the files and directories of the current working directory, separated by connas(',') :
   * Directory names should end with a slash ('/')
   * Files and directories starting with a dot ('.') whould be listed
   * The listing should be alpha ordered, except for the directories '.' and '..' which should be listing at the very beginning
   * Only digits and letters are used to sortl Digits should come first
   * You can assume that at least all lines will test with will have at least one letter or one digit
   * The listing should end with a new line
school.mgc - creates a magic file 'school.mgc' that can be used with the command 'file ' to detect 'School' data files.Schook data files always contain the string 'SCHOOL' at offset 0. 
