The Learning objectives to be met by the end of this project are:

		General
	What does RTFM mean?
	What is a Shebang
	What is the Shell
	What is the shell
	What is the difference between a terminal and a shell
 	What is the shell prompt
 	How to use the history (the basics)

		Navigation
	What do the commands or built-ins cd, pwd, ls do
	How to navigate the filesystem
	What are the . and .. directories
	What is the working directory, how to print it and how tochange it
	What is the root directory
	What is the home directory, and how to go there
	What is the difference between the root directory and the home directory of the user root
	What are the characteristics of hidden files and how to list them
	What does the command cd - do

		Looking Around
	What do the commands ls, less, file do
	How do you use options and arguments with commands
	Understand the ls long format and how to display it
	A Guided Tour
	What does the ln command do
	What do you find in the most common/important directories
	What is a symbolic link
	What is a hard link
	What is the difference between a hard link and a symbolic link
		
		Manipulating Files
	What do the commands cp, mv, rm, mkdir do
	What are wildcards and how do they work
	How to use wildcards
	Working with Commands
	What do type, which, help, man commands do
	What are the different kinds of commands
	What is an alias
	When do you use the command help instead of man
		
		Reading Man Pages
	How to read a man page
	What are man page sections
	What are the section numbers for User commands, System calls and Library functions
		
		Keyboard Shortcuts for Bash
	Common shortcuts for Bash

			LTS
	What does LTS mean?


The following scripts were created to meet the following objectives:

	1. 0-current_working_directory: prints the absolute path name of the current working directory.
	
	2. 1-listit: Display the contents list of your current directory.
	
	3. 2-bring_me_home: changes the working directory to the user’s home directory.
	
	4. 3-listfiles: Display current directory contents in a long format
	
	5. 4-listmorefiles: Display current directory contents, including hidden files (starting with .). Use the long format.
	
	6. 5-listfilesdigitonly: Display current directory contents in a long
	format, with user and group IDs displayed numerically and hidden files (starting with .)
	
	7. 6-firstdirectory: creates a directory named my_first_directory in the /tmp/ directory.
	
	8. 7-movethatfile: Move the file betty from /tmp/ to /tmp/my_first_directory.
	
	9. 8-firstdelete: Delete the file betty.
	
	10. 9-firstdirdeletion: Delete the directory my_first_directory that is in the /tmp directory.
	
	11. 10-back: changes the working directory to the previous one.
	
	12. 11-lists: lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
	
	13. 12-file_type: prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
	
	14. 13-symbolic_link: Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

	15. 14-copy_html: copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

	16. 15-lets_move: moves all files beginning with an uppercase letter to the directory /tmp/u.

	17. 16-clean_emacs: deletes all files in the current working directory that end with the character ~.

	18. 17-tree: creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
