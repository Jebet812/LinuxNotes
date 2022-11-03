# 	Linux
***
## Introduction
__Linux__ is an operating system. Linux is used fairly widely because it offers a higher level of control via a few different methods.
1. __Linux is open source__: Its source code is available hence can change and can be manipulated as one pleases.
2. __Linux offers granular control__: You have infinite amount of control over the system . Everything can be controlled by the terminal at the miniscule level or the most macro level. Linux makes sxripting in any of the scripting simple and effective.
3. __Linux is transparent__: You can see and manipulate its working parts.
### Introductory terms and concepts
1. __Case Sensitivity__: Linux is very case sensitive. Desktop/desktop/deskTop are not similar. “file or directory not
found” this error will be indicated in such a case.
2. __Directory__: This provides a way of organising files. 
3. __Root__: This is an admin account to be used by a trusted person who can do anything e.g change passwords, add users etc.
4. __Home__: This is a directory where files created are saved by default.
5. __Binaries__: These are files that can be executed and they generally reside in the */usr/sbin* or *usr/bin*.
6. __Terminal__: command line interface (CLI)
7. __Shell__: This is the environment running commands on Linux. 
8. __Script__: Series of commands run in an interpretive environment that converts each line to source code.
### The Linux Filesystem.
At the top of the filesystem is the root */*
Important subdirectories are:
1. __*/root*__: Home directory of the root user.
2. __*/bin*__: Where application binaries reside.
3. __*/etc*__: The configuration files are contained here. 
4. __*/lib*__: Where you'll find *libraries.*
5. __*/home*__: This is user's home directory.
6. __*/mnt*__: This is where other file systems are mounted or attached to the filesystem.
7. __*/media*__: This where USBs and CDs are usually mounted on the filesystem.
### Basic Commands in Linux

#### Finding yourself with pwd
This is present working directory : It returns location within the directory.

#### Checking Login with whoami
Used to check which user you are logged in as.

#### Navigating the Linux Filesystem
This helps to find applications, files and directories located in other directories. The structure is entirely text based since Linux is Command Line Interface (CLI)
hence commands are used to navigate the file system. 
1. __*Changing Directories with cd*__: We use the *change directory, cd* command to change directory from terminal.
To move up a level in file structure towards *root* we use *cd* followed by double dots (..), or more double dots pairs as many levels as needed.
To move to the root level from the file structure from anywhere type *cd /*. */* represents the root file system.
2. __*Listing the contents of directory with, ls*__: We use the *ls, list* command to see the contents of directory, files and subdirectories.
It lists both files and directory contained in the directory.
To get more information about the files and directories like the owner, size, permission and when last modified add an *-l* switch after the "ls*. The *l* stands for *long* hence *ls -l, long listing.*
To show hidden files that cannot be found using *ls -l* use *ls -la.*
3. __*Getting help*__: Nearly every command, application or utility in Linux has a dedicated help file to provide guidance for use.
Type command you need help with followed by *-- help.* For example *ls --help*
You can also use *-h* or *-?*

#### Referencing Manual pages with , man
In order to view more information on applications and commands use the , *manual (man) page* in Linux.
To view the *man page* type *man* before the application, utility or command.
To quit the manual page press Q to return to the commad prompt.


