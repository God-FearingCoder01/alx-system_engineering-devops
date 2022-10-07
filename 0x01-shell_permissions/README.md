## This is to describe what each file at root of the  folder of the project is doing.

**0-iam_betty**  switches the current user to the user ```betty```.  
**1-who_am_i** prints the effective username of the current user.  
**2-groups** prints all the groups that the current user is a part of.
**3-new_owner** changes the owner of the file ~~~~hello~~~~ to the user ~~~~betty~~~~.  
**4-empty** creates an *empty file* called ~~~~hello~~~~.
**5-execute** adds execute permission to the owner of the file ~~~~hello~~~~ .
**6-multiple_permissions** adds execute permission to the owner and the group owner, and read permission to the other users, to the file called ```hello``` in the current working directory.
**7-everybody** adds execution permission to the owner, the group owner and to the other users, for the file called ```hello``` which is in the current working directory.
**8-James_Bond** sets the permission to the file called ```hello``` as follows:
     * Owner: no permission at all
     * Group: no permission at all
     * Other users: all the permissions
to the file called ```hello``` which is in the current working directory.
**9-John_Doe** sets the mode of the file called ```hello``` in this manner ~~~~-rwxr-x-wx 1 julien julien 23 Sep 20 14:45 hello~~~~.
**10-mirror_permissions** sets the mode of the file hello as the same as that of the file called olleh, where both files are in the same working directory.
**11-directories_permissions** adds execution permission to all subdirectories of the current working directory for the owner, the group owner and all other users. Regular files whould not be changed.
**12-directory_permissions** creates a directory called my_dir with permissions 751 in the working directory.
**13-change_group** changes the group owner to school for the file called hello, that is in the current working directory.
**100-change_owner_and_group** changes the owner to vincent and the group owner to staff for all the files and dircetories in the current working directory.
**101-symbolic_link_permissions** changes the owner and the group owner of -hello to cincent and staff respectively.
**102-if_only** changes the owner of the file hello to betty only if it is owned by the user guillaume.
**103-Star_Wars* plays the StarWars IV episode in the terminal.