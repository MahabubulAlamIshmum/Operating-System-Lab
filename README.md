# Operating-System-Lab
## 📋 Topics Covered

1. [🖥️ Bash Command](#1-🖥️-Bash-Command)
   - Basic Linux commands
   - File and directory management
   - File permissions
   - Input/Output redirection
   - Pipes and text utilities

2. **🐧 Linux Shell Scripting**
   - Variables and user input
   - Conditional statements
   - Loops
   - Functions and arrays
   - Command-line arguments
   - File and directory handling
   - Scripting automation

3. **⚙️ Process Management**
   - Process creation and management
   - Process states
   - Foreground and background processes
   - Process monitoring
   - Signals and process termination

4. **📊 Scheduling Algorithms**
   - First Come First Serve (FCFS)
   - Shortest Job First (SJF)
   - Shortest Remaining Time First (SRTF)
   - Priority Scheduling
   - Round Robin (RR)
   - Gantt chart and scheduling calculations

5. **🔄 Synchronization**
   - Critical section
   - Race condition
   - Mutual exclusion
   - Mutex and semaphore
   - Producer-Consumer problem
   - Process synchronization

## 1. 🖥️ Bash Command

**📂 Directory Navigation**

## 1. Bash Command

```Bash
Command     Uses
pwd         To see the present directory path.
ls          To see files and folders in the current directory.
ls -l       To see detailed information about files and folders.
ls -a       To see all files and folders, including hidden files.
ls -A       To see hidden files, excluding . and ..
ls -lh      To see detailed information with human-readable file sizes.
ls -R       To list files and folders recursively.
ls -S       To sort files by size.
ls -s       To show the allocated size of files.
clear       To clear the terminal screen.

📂 Directory Navigation

Command     Uses
cd          To move to another directory.
cd ..       To move one level up.
cd ~        To move to the home directory.
cd /        To move to the root directory.
cd -        To return to the previous directory.
cd ./       To refer to the current directory.

📁 Directory Management

Command     Uses
mkdir       To create a new directory.
mkdir -p    To create parent and nested directories.
rmdir       To delete an empty directory.
rm          To delete a file.
rm -r       To delete a directory and its contents recursively.
rm -rv      To recursively delete and show deleted items.

📄 File Management

Command     Uses
touch       To create a new empty file.
mv          To move or rename a file or folder.
cp          To copy a file.
cp -r       To copy a directory and its contents recursively.

📖 File Content & Editing

Command     Uses
cat         To display the content of a file.
cat -n      To display file content with line numbers.
cat -b      To display line numbers only for non-empty lines.
cat -s      To reduce multiple blank lines.
cat -sn     To display line numbers and squeeze blank lines.
cat -E      To show the end of each line.
nano        To create or edit a file using a terminal-based text editor.

🔢 Counting

Command     Uses
wc          To display line, word and byte counts.
wc -l       To count the number of lines.
wc -w       To count the number of words.
wc -c       To count the number of bytes.

🔎 Searching

Command       Uses
grep          To search for specific text or a pattern inside a file.
grep -i       To search without considering uppercase or lowercase letters.
grep -n       To display matching text with line numbers.
grep -in      To search case-insensitively with line numbers.
grep -v       To display non-matching lines.
grep -c       To count the number of matching lines.
grep -r       To search recursively inside directories.
grep -E       To search using Extended Regular Expressions.
grep -oE      To display only the matched parts using Extended Regular Expressions.

🔝 Head & Tail

Command     Uses
head        To display the beginning of a file.
head -n     To display a specific number of lines from the beginning.
head -c     To display a specific number of characters or bytes from the beginning.
tail        To display the end of a file.
tail -n     To display a specific number of lines from the end.
tail -f     To continuously display new content added to a file.

🔍 Find

Command         Uses
find            To search for files and directories.
find -name      To search for a file or folder by name.
find -type d    To search only for directories.

🔐 File Permissions

Command       Uses
chmod         To change file or folder permissions.
chmod u+x     To add execute permission for the user.
chmod g-x     To remove execute permission from the group.
chmod o+x     To add execute permission for others.
chmod u-r     To remove read permission from the user.
chmod u+r     To add read permission for the user.
chmod 666     To give read and write permission to user, group and others.
chmod 777     To give read, write and execute permission to user, group and others.

🕘 History

Command             Uses
history             To display previously executed commands.
history > file      To save command history into a file.
history >> file     To append command history to a file.

📚 Manual

Command     Uses
man         To display the manual/help page of a command.
