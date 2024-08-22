## Git Cheat Sheet and Branching Practice

Examples of Common Git Commands - Practice dealing with branching and resolving merge conflicts.


### General Commands
* 'git init' - initialize local git repo in current working directory
* 'git add filename' - stage 'filename' for commit
* 'git commit -m msg' - commit stages files into local repo


### Information Commands
* 'git status' - show status of local repo
* 'git log' - list commit history of current branch
* 'git log --oneline' - list commit history (compact format)

### Branching Commands
* 'git branch' - lost of local branches
* 'git branch branchName' - create local branch 'branchName'

* 'git checkout branchName' - switch to branch 'branchName'
* 'git checkout -b branchName' - create and switch to branch 'branchName'


### Remote Commands
* 'git remote add alias url' - add new remote 'url' with alias 'origin'
* ' git push origin branchName' - push current local branch to remote branch 'branchName'
* 'git pull origin branchName' - pull and merge remote branch 'branchName' with current local branch