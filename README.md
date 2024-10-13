# Hello

New repo's README markdown file !!!!

## learning to use terminal and git commands

### git clone
>git clone HTTPS_link_CODE_githubRepo

>git clone SSH_link_GitHubRepo

### change directory
>cd child_folder_name

### clear terminal clutter
>clear

### check updated and untracked files/folders
>git status

### stage commits (letting git know updates)
>git add .

>git add filename

### Commit to git
>git commit -m "your_commit_message"

### Push
>git push

>git push origin main

where 
* origin is shorthand for remote repo URL location,
* main is branch_name

### Create repo
> git init

### creating origin's value
> git remote add origin https://copied.repolink.git

### remote repo connected to current repo
>git remote -v

### setting an upstream
>git push -u origin master

### check all branches and current one *
>git branch

### switch branches
> git checkout branch_name

### creating a new branch 
> git checkout -b branch_name

### check diffing of current branch to mentioned branch
>git diff branch_name

### merging locally the current branch  with mentioned branch (NOT preferred - git hub website)
> git merge branch_name

### fetch commits
> git pull

### fetchfrom master origin remote to local origin/master
> git pull origin master

### git pull = git fetch + git merge

### deleting a branch
> git branch -d branch_name

### all changes made since last commit
> git diff

### add and commit together (only modified files)
> git commit -am "message"

### merging locally the current branch  with master(or main) 
[necessary as u don't want to get too behind the master, else merging will get difficult]
> git merge master

### UNDO cstages / commits 
> git reset 

OR

> git reset file_name

### reset using HEAD pointer
> git reset HEAD~1

### all the commits are logged
> git log
     
     press 'q' to exit


### reset using Hash
> git reset g6sdf4vgd521fds53sd5

### reset Hard
> git reset --hard g6sdf4vgd521fds53sd5

### fork
* use git hub fork button
* select fork all branches or just main branch(default)
* freely perform CRUD



