# Open Source SW - Lecture Note 4 
Writer: 202334273_KimYeseo (김예서)

### *About 'Shell command'...*

Shell provides and interface with the operating system and the user. It can be used to execute and deal the functions of the operating program. People use it when they want a interface that connect with the operating system and them. The shell interprets the input (commands) and executes the commands(input).

---

### Run Shell Terminal

- Linux or IOS : Search for "Terminal" in my apps and run it
- Windows : Install "Git Bash"

---
## Shell command

1. **pwd** 
shows the current path in a hierarchical directory

2. **cd**
change directory

3. **ls**
list files and directories


##### *More about 'ls'*
The ls command is used to list the contents of a directory. It is probably the most commonly used Linux command. It can be used in a number of different ways. Here are some examples.
```
ls ; List the files in the working directory
ls/bin ; List the files in the /bin directory
ls -l
; List the files in the working directory in long format
ls -1/etc/bin ; List the files in the /bin directory and the /etc directory in long format
ls -la ; List all files in the parent of the working directory in long format
```
##### options - Tip ; past commands

- -l : long format  
- -lh : long format with size in

##### clear

clear the terminal screen.

$ mkdir asdf
$ clear

---
## Manipulation

1. **cp**
copy files and directories
2. **mv**
move files and directories or rename them
3. **rm**
delete files and directories permantely and irreversevely
4. **mkdir**
make a new directory



- **/** : root directory  
- **.** : current directory  
- **..** : parent directory  
- **~** : home directory
--

    -/[directory name] : absolute path
    ./[directory name] : relative path  
    ../[directory name] : relative path

---
## Exiting Terminal
- **exit**
exit the shell.