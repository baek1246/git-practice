# Open Source SW - Lecture Note 6

##### **Writer: 202334273_KimYeseo (김예서)**



---

### Version Control and Collaboration

*It's essential to use a version control system for software development and other documentation works.*
- Basic solution: Making copies

We need asystematic management system for version control and collaboration.

---
### Changes vs Snapshots

1. Storing data as changes to the base version
2. Storing data as snapshots

----

### Local, Centralized, and Distributed Version Control
* Local : 
Local computer - (Checkout)File <-> (Version Database) Version 3 - Version 2 - Version 1

* Centralized
(Conputer A)File / (Couputer B)File
(Central VCS Server - Version Database) Version 3 - Version 2 - Version 1

* Distributed
(Server Computer - Version Database) Version 3 - Version 2 - Version 1
(Computer A - File - Version Database) Version 3 - Version 2 - Version 1
(Computer B - File - Version Database) Version 3 - Version 2 - Version 1


---

### Three Staes in Git
Modified - Working Directory [Stage Fixes] Staged - Staging Area [Commit] Comitted - git directory (Repository)

[Checkout the project]
Comitted - git directory (Repository) -> Staged - Staging Area -> Modified - Working Directory
   
---
##### Git config : First-time setup

*Git configurations are stored in three levels:*

1. System level : -- system option. Affefts all uses and repositories on the system
2. Global level : -- global option. Affects all repositories of a current user
3. Local level: -- local option. Specific to the current repository

*Each level overrides values in the previous level: system -> global -> local*

--- 

##### Initializing a Repository in an existing directory
$ git init

##### Checking Repository Status
$ git status

##### Adding a new file to be staged (tracked)
$ git add [file_name]
$ git add .

##### Unstaging a file
$ git rm - cached [file_name]

##### Ignoring a file
.gitignore file

##### Commit
$ git commit -m "commit message"

##### Change branch name

--- 

