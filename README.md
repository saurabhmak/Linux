# Linux
Linux Basics and Scripting Notes
Linux Filesystem Basics
Directories and Files
Directories and Files:

In Linux, files are the fundamental components much like books in a library, forming a structured hierarchy.
Directories are akin to the shelves on which books are organized. They are used to store files in a structured manner.
Current Directory Commands:

pwd (Print Working Directory): Displays the current directory you are working in.
ls: Lists files and directories within the current directory.
Basic Commands
Creating Directories:

mkdir: Used to create new directories. For example, mkdir Geography creates a directory named "Geography".
Changing Directories:

cd: Change the current directory. For instance, cd Geography moves you inside the "Geography" directory.
cd ..: Moves you one directory up in the hierarchy.
Creating Files:

touch: Creates an empty file. For example, touch file.txt creates a file named "file.txt".
Removing Directories and Files:

rm: Remove files.
rm -rf: Remove directories and their contents recursively.
Understanding the Root and Home Directories
Root Directory (/):

The top level of the file system hierarchy. All files and directories stem from the root directory.
Home Directory (~):

A user-specific directory, typically used for storing personal files and configurations.
Shell Scripting Basics
Writing a Simple Shell Script
The Shebang (#!):

A special line at the top of a script (e.g., #!/bin/bash) that tells the system what interpreter to use to execute the script.
Creating a Script:

Use vi or vim editors to create script files (vi script.sh).
Insert executable commands within the file and save.
Executing a Script:

Use chmod +x script.sh to make the script executable.
Execute with ./script.sh.
Example Script
A simple script to create directories and files:

#!/bin/bash
mkdir B
cd B
mkdir Civics
mkdir Physics
cd Civics
touch book3.txt
cd ..
cd Physics
touch book4.txt
Common Script Commands
Exiting Vim:

Use :wq to write and quit.
Use :q! to quit without saving.
Permissions:

chmod 700 script.sh provides execution permissions.
CPU, Memory, and Disk Analogy
CPU (Central Processing Unit):

Compares to multiple burners on a stove allowing for multitasking .
RAM (Random Access Memory):

Acts like the cooking space, holding data temporarily for quick access .
