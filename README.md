# File-permissions
Managing file permissions with linux commands
In this exercise i explored how to manage files with linux commands 
The permission string rwxrwxrwx with r(read)= ability to read a file, w(write)= ability to write to a file and x(execute)= ability to execute a file if its a program are given to the 3 types of owners - user(owner of the file ), group(a large group the owner is part of) and others(other users in the system). I'll be modifying the permission for some owners using t he command "chmod" which is used to change permissions on files and directories
From the first file i used "pwd" to get the directory i am working on and used the command "cd" to open a sub directory named "project"
In the second file i highled how i listed the files under projects with the command "ls -la" which function is to list eveery file includig the hidden ones
In the third file i disabled the permission for the "others" to be able to write to the file using the command "chmod o-w project_k.txt" and proceeded to list the files under projects to confirm the changes made
In the fourth file i disabled the permission for "groups" to be able to read into the file project_m.txt using the command "chmod g-r project_m.txt" and proceeded to list the files under projects to confirm the changes made
In the fifth file i disabled the permission for "groups" and "user" to be able to write into the file project_x.txt using the command "chmod u-w,g-w .project_x.txt" and proceeded to list the files under projects to confirm the changes made
In the sixth file i gave permisssion to "group" to be able to read .project_x.txt using the command "chmod g+r .project_x.txt" and proceeded to list the files under projects to confirm the changes made
In the last file i disabled permission for "groups" to be able to execute on the drafts file using the command "chmod g-x drafts" and proceeded to list the files under projects to confirm the changes were made 
This task was to get familiar with permissions of files and giving access to whichever groups deserves to read, write or execute on a particular file
