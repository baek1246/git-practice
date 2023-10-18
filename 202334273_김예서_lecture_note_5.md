# Open Source SW - Lecture Note 5

##### **Writer: 202334273_KimYeseo (김예서)**



---

### I/O Redirection: Standard Output
*By default, standard output is screen.*

1. ">"
-> redirect output using ">" after a command to create and save the output in a file

2. ">>"
-> Using ">>" appends output to an extising file or create and write to a new file if it doesn't exist.

---
### I/O Redirection: Standard Input
*By default, standard input is from keyboard.*

1. "<"
-> redirect input from a file using "<".

2. "<" and ">"
-> Mix "<" and ">" together in a single line.

----

* Piplelines : "|"
pipeline feeds output of previous command to input of next command.
-> command1 | command2 | command3

* Expansion
Special characters expand its meaning when given to shell commands.


---
   
*> Tip ; Backslash*
Backslash can be used to ignore line change in command ("enter"), to enter a long command in multiple lines.
---
##### Permissions

Linux is a multi-user system.
Files and directiors have a permission assigned differently to owner / group / others.

1. Read, write, and execute permissions for all other users.
2. Read, write, and execute permissions for the group owner of the file.
3. Read, write, and execute permissions for the file owner.
-> File tipe: indicates regular filed indicates directory.


##### Changing Permissions
"chmod" changes permissions.

* value - Meaning ; ex)
777 - (rwxrwxrwx)

Change the permission of a file "word.txt" that only the owner can read and write, but all the others can only read it. No execution is needed for all users.

##### Superuser
- A superuser has all system administation authority.
- Some commands need superuser's privilleges.
- Put "sudo" before the command if you are a superuser.

##### Text Editors
In Linux, you can choose CLI-based or GUI-based text editors.

##### Shell Script
Wirte and run a shell script

---
*> Tip : History*
Type "History" to see previous command history. Or, save it to a text file.
--- 
### *About 'Shell command'...*

Shell provides and interface with the operating system and the user. It can be used to execute and deal the functions of the operating program. People use it when they want a interface that connect with the operating system and them. The shell interprets the input (commands) and executes the commands(input).
