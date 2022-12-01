Scripts and what they are doing: 
0. My name is Betty
su betty >> Create a script that switches the current user to the user betty.

1. Who am I
id -un >> Write a script that prints the effective username of the current user.

2. Groups
groups >> Write a script that prints all the groups the current user is part of.

3. New owner
chown betty hello >> Write a script that changes the owner of the file hello to the user betty.

4. Empty!
touch hello >> Write a script that creates an empty file called hello.

5. Execute
chmod u+x hello >> Write a script that adds execute permission to the owner of the file hello.

6. Multiple permissions
chmod u+x,g+x,o+r hello >> Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.

7. Everybody!
chmod a+x hello >> Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello

8. James Bond
chmod 007 hello >> Write a script that sets the permission to the file hello as follows:

9. John Doe
chmod 753 hello >> Set permissions so owner has all permissions, group has read and execute permissions and others have write and execute permissions.

10. Look in the mirror
chmod --reference=olleh hello >> Copies the mode of file olleh to file hello.

11. Directories
chmod ugo+X ./* >> Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

12. More directories
mkdir -m 751 my_dir >> Create a script that creates a directory called my_dir with permissions 751 in the working directory.

13. Change group
chgrp school hello >> Write a script that changes the group owner to school for the file hello

14. Owner and group
chown vincent:staff ./* >> Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

15. Symbolic links
chown -h vincent:staff _hello >> script that changes the owner and the group owner of _hello to vincent and staff respectively.

16. If only
chown --from=guillaume betty hello >> Change owner of the file hello to betty only if it is currently owned by guillaume

17. Star Wars
telnet towel.blinkenlights.nl >> Write a script that will play the StarWars IV episode in the terminal.(searched online)
