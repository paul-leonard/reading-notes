# Paul's Reading Notes

## Code 102

### Class 3:  Revisions in the Cloud



#### Version Control

Version Control Systems (VCS) allow you to track changes to a file and revert to previous versions, track modifictions and who made them, and compare changes.  Such a system can help identifying a bug and rectifying it much simpler and efficient.  Version control systems over the years have evolved to let more people work on the same code in the most accessible and trackable way.  Originally, local version control systems were used.  Those morphed into Centralized Version Control systems.  Now a Distributed Version Control system is the architecutre of choice.

##### Git:  The Distributed Version Control System of Choice

Git is the most common DVS in use.

**Key Take Aways About Git**
- Git takes snapshots each time you commit (or save) changes.
- Most information about the file and its modifications are stored locally on the user's machine.  This means you can work while offline.
- Git tracks every change made to a file.
- Helps prevent loss of data.
- Files managed by get can reside in one of 3 states:  Committed, Modified, and Staged.

**Three ways to get help in Git**
1. 'git help ?command?'
1. 'git ?command? --help'
1. 'man git-?command?'
*where ?command? = the command in question

###### Setting up a Git Repository
CLI is used to issue commands to import file and/or clone a repo.

In CF201, we used the clone command to copy a repo we had created on the web interface of GitHub.

'git clone <link to repo>'

To do the same thing and put the cloned repository in a directory of your chosing, you can add to that command like shown below:

'git clone <link to repo> <desired directory>'

###### Git Workflow

The local Git repo has 3 components:
1. Working Directory
1. Index
1. Head

Files (that are checked out or in the working copy of the repo) can be in one of two states:
1. Tracked
1. Untracked

Untracked files were not in the last snapshot and therefore are not in the staging area.  On the other hand, tracked files were part of the last snapshot and therefore can be considered:
1. modified
1. unmodified
1. staged

[The most helpful diagram of git work flow that I have seen was on this udemy page.](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

*Stashing Changes*
Two commands may be helpful in hiding changes until you are ready to work on them again.  It will make the working directory appear "clean" in the meantime.
'git stash'
'git stash apply'


###### Remote Repositories
To collaborate and work on the same code as others, you need to use Remote Repositories.  You can work on multiple repositories at once and can have varying degrees of read/write permission for them.  You pull data from and push data to the remote repositories.  For cloned repositories, the remote source repo is referred to as the "origin" and the cloned local branch is called "master".






[Return to Table of Contents for Paul's Reading Notes](https://paul-leonard.github.io/reading-notes/ "Go back to find more notes!")

---

Thank you for visiting my page of notes.  I hope they were helpful to you.  Please also check out [my GitHub portfolio page](https://github.com/paul-leonard "Paul's GitHub Portfolio").