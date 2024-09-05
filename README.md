I have used many git commands in this projects  
Git commands-  
git init : to initialize a repository  
ls -lart  : shows all hidden files  
git status  : tells about the status of files whether untracked,tracked,modified,unmodified  
git add filename  : used for staging the file  
touch filename  :  used for creating a new file  
git add -A  :  to stage all files at once  
git commit -m "message"  : to commit file  
git checkout filename :  to restore file to previous commit  
git checkout -f :  to restore all files to previous commit  
git log : shows all commits along with author details  
git log -p -(number of commits)  :  shows last number of commits along with changes mentioned in the command  
git diff  :  compares working tree with staging area  
git diff --staged  :  compares staging area with last commit  
clear  :  clears the terminal  
git commit -a -m "message"  :  commits all changes without staging  
ls  :  lists all the files  
git rm  : removes files from working directory and staging area  
git rm --cached  :  removes files from staging area  
git status -s : tells which file is in staging area and which file is changed in working area  
git branch branchname  :  creates a new branch with the name provided in the command  
git branch  :  lists all branches  
checkout newBranch  : switches to the mentioned branch in the command  
git merge otherbranchname  :  merges the other branch into the current branch  
git checkout -b newBranch  : creates a new branch and switches to it  
git push : pushes the commits in the local to remote repository  
git pull : pulls the changes in the remote repository to local and merges them  
