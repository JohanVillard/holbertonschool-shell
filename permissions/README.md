list of scripts of this folder:

change user to betty				su betty
see the actual username of current user		whoami
groups of the current user			groups
change owner of the file			chown betty hello
create an empty file				touch hello
give execute permission				chmod +100 hello
give multiple permissions			chmod +114 hello
give permissions to everybody			chmod +111 hello
sets some permissions				chmod 007 hello
sets other permissions				chmod 753 hello
mirror permissions to other file		chmod --reference=hello olleh
give permission to current dir and sub		chmod -R 111 .
