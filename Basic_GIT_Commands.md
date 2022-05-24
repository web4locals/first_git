List of basic GIT commands
==========================

*   `git init` initializes git
  
*   `git status` Check status of changes (tracked-and untracked files)
  
*   `git add *filename*` adds your new file to git
  
*   Make sure you close the file before using `git diff`
  
*   `git diff *filename*` checks new changes in lines, in \*file\* (new lines will have + removed lines will have -)
  
*   To exit from the `git diff` view press `q`
*   `git commit -m "My Latest Change! blah blah"`(`-m` = message `commit` is like a comment about your changes)
*   `git log`shows a list of previous and current commits
  
*   `git checkout *branch name*`allows you to load a branch or detached HEAD or SHA
  
*   `git branch`lists the branches if you want to create a branch `git branch *cool name*`
  
*   `git merge *branch name*`merges branch to the master
  
*   `git branch -d *branch name*`deletes the branch
  
*   `HEAD` Is the commit your currently on
*   `git show HEAD` Shows the latest vs last changes in the files
*   `git checkout HEAD *filename*`Will restore back to the last changes
*   if you made a mistake `git checkout *filename*` to undo your mistake
*   A short way to add and commit at the same time `git commit -a -m "my awesome mod"`

### Git Hub commands

  

#### Adding a new repository

1.  Before you start make sure you git email is the same as your github account

*   To change git username `git config --global user.name "FIRST_NAME LAST_NAME"`
*   To change git email `git config --global user.email "MY_NAME@example.com"`
*   To check your git details `git config --list`
  

3.  Create a repository on the Github website
  
5.  in git you can create a new repo or push existing one over from git

*   #### Create from git
    
      
    `echo "*MyProjectName*" >> README.md`  
    `git init`  
    `git commit -m "first commit"`  
    `git remote add origin *HTTPS or SSH address(username.github.com/*MyProjectName*.git)`
  
*   #### Push an existing Project to Github from git
    
      
    
`git remote add origin *HTTPS or SSH address(username.github.com/*MyProjectName*.git)`  
`git push -u origin`

### Commands

*   `git clone *remote location name* *clone name*` clones the github repo
*   `git fetch` gets updates from your github repo
*   `git push` is used to upload local repository content to a remote repo. also if you add `-u` it uplinks your local files
*   `git pull`is used to download content from remote repo
*   `git log --graph --decorate --oneline --all` to check on all progresses made in the branches: 

*   ### More to come as I learn more
*   #### Also some of the infomation on here may be slightly incorrect I will fix later.



