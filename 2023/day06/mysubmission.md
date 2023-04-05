Task 1:
a. Create a simple file and do ls -ltr to see the details of the files

![image](https://user-images.githubusercontent.com/99756745/228739148-d66cfdf3-efba-4140-8f93-a84c5c335a42.png)

b. "chgrp" is used to change the gropu permission of a file or directory.

c. "chown" is used to change the ownership permission of a file or directory.

d. "chmod" is used to change the other users permissions of a file or directory.

![image](https://user-images.githubusercontent.com/99756745/229983938-4509312b-b5ae-4ec6-8bb2-e0e526eb3224.png)


Task 2:
File Permission System:

The file permission system in Linux is a critical aspect of its security model, which allows users to control access to their files and directories. Each file and directory in the Linux filesystem is assigned a set of permissions that determine who can access the file and what actions they can perform on it.

There are three types of permissions in Linux: read, write, and execute. These permissions can be assigned to three categories of users: the owner of the file, the group owner of the file, and all other users on the system.

The file permission system in Linux is represented by a series of 10 characters that indicate the file type, ownership, and permissions. These 10 characters are divided into three parts: the file type and permissions, the owner, and the group owner.

Here is an example of a file permission, which comes after (ls -l):

-rw-r--r-- 1 user group 4096 Mar 31 12:30 example.txt

The first character indicates the file type, with a dash (-) indicating a regular file. The next nine characters indicate the file permissions, divided into three sets of three characters each. Each set represents the permissions for the owner, group owner, and all other users on the system, respectively.

![image](https://user-images.githubusercontent.com/99756745/229984590-5e53a683-4b62-4814-b723-5fc1a6433e2e.png)

![image](https://user-images.githubusercontent.com/99756745/229984655-40ab669f-10b3-48ba-82f8-6cf060b48cee.png)

The permission characters are as follows:

r (read): Allows the user to view the contents of the file or directory.

w (write): Allows the user to modify the contents of the file or directory.

x (execute): Allows the user to execute the file or access the contents of the directory.

The permission characters can be combined in different ways to grant specific sets of permissions. For example, the permission string "-rwxr-xr--" indicates that the owner has read, write, and execute permissions, the group owner has read and execute permissions, and all other users have read-only permissions.

Modify Permission:

chmod:

To modify file permissions, you can use the chmod command followed by the permission string and the filename. For example, the following command sets read, write, and execute permissions for the owner of the file example.txt:

Command: chmod u+rwx example.txt

The "u" indicates that the permission should be applied to the owner, and "rwx" indicates the permissions to be set.

If we want to specify the permission rights for all three categories at once, we can do this as well. Below is the command for this:

Command: chmod 777 example.txt

Here first digit (7) states, give the user all the 3 rights to read, write and execute. The digits are calculated as follows:

4 for read permission

2 for write permission

1 for execute permission

The digits are added together to create a three-digit number. For example, the permission 777 indicates that the file has read, write, and execute permissions for the owner, group, and all other users on the system.

In addition to file permissions, Linux also has a file ownership system that allows users and groups to be assigned to files and directories. The chown and chgrp commands can be used to change the ownership of a file or directory.

chown and chgrp:

chown is used to change the owner of the file and chgrp is used to chang the group of the file. Below is the command:

Command chown: chown <user name> example.txt

Command chgrp: chgrp <group name> example.txt
  
![image](https://user-images.githubusercontent.com/99756745/229984742-967fdd7f-bcf1-427d-b9cc-b403836f630c.png)


Task 3:
Access Control Lists (ACLs)

Access Control Lists (ACLs) are a type of file permission system that provide more fine-grained control over file permissions than the standard file permissions model. It can be used for giving a specific user permission for a specific file.

Let's say you want to give a specific user, write access to the file. You could add that user to the required group, but this would also give access to all other files owned by that group. With ACLs, you can grant that user write access to the specific file without giving access to any other files owned by that group.

To add an ACL to a file or directory, you use the setfacl command.

Command: setfacl -m u:<user name>:rw example.txt

In this command, -m specifies that you are modifying the ACL, u:<user name> specifies that you are adding an ACL for user <user name>, and rw specifies that you are granting read and write permissions.

You can also add ACLs for groups using the g:<group name> syntax, and you can remove ACLs using the -x option followed by the user or group and the permissions to remove.

Once you've added an ACL to a file or directory, you can view the ACLs using the getfacl command.

Command: getfacl example.txt

![image](https://user-images.githubusercontent.com/99756745/229984907-83d09a85-e272-45e0-8acd-d1d820d94430.png)

  
