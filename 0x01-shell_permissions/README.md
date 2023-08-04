Shell permissions tasks

0)su + username  ==> changes the current user to the username

1)whoami  ==> print the current username

2)groups ==>  prints all the groups the current user is part of

3)chown + username ==> hanges the owner of the file to username

4)touch ==> create an empty file

5)chmod ==> change the permission of file or dir
           
6)chmod , , ===> commas are used to seperate permissions 

7)chmod  ==> (4,2,1) if the permission present it takes 1 if not it takes 0 then we add the value of the whole group

10)chmod --reference=(name of the file we want to copy it's permission)  (name of the file the permission will apply to) ===> to copy one file's permission to another

11)chmod -R ==> aplly the changes to all subdir 

12)mkdir -m ==> to create a file with specific permissions

13)chgrp ==> to change the group owner 

14)chown (user):(group) (file or dir name) ==> change the owner and group owner of a file

15)chown -h ==> change the ownening of a symbolic link 

16)chown --from=(the name of the file owner in which the if start) (the name of the new file owner) (name of the file)

17)wth ?????  may the force be with me               
