This is a project on permissions as used in the shell.

The following scripts are created to meet the learning objectives of the aforementioned topic

	1. 0-iam_betty - switches the current user to the user betty.
	2. 1-who_am_i - prints the effective username of the current user.
	3. 2-groups - prints all the groups the current user is part of.
	4. 3-new_owner - changes the owner of the file hello to the user betty
	5. 4-empty - creates an empty file called hello
	6. 5-execute - adds execute permission to the owner of the file hello
	7. 6-multiple_permissions - adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
	8. 7-everybody - adds execution permission to the owner, the group owner and the other users, to the file hello
	9. 8-James_Bond - sets the permission to the file hello as follows:
		Owner: no permission at all
		Group: no permission at all
		Other users: all the permissions

	10. 9-John_Doe - sets the mode of the file hello to -rwxr-x-wx
	11. 10-mirror_permissions - sets the mode of the file hello the same as olleh’s mode.
	12. 11-directories_permissions - adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
	13. 12-directory_permissions - creates a directory called my_dir with permissions 751 in the working directory.
	14. 13-change_group: changes the group owner to school for the file hello
	15. 14-change_owner_and_group - changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
	16. 15-symbolic_link_permissions - changes the owner and the group owner of _hello to vincent and staff respectively.
	17. 16-if_only - changes the owner of the file hello to vincent only if it is owned by the user guillaume.
