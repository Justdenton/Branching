## Git Cheat Sheet and Branching Practice

Examples of Common Git Commands - Practice dealing with branching and resolving merge conflicts.

Stuff added here in newBranch.

### General Commands
* `git init` - initialize local git repo in current working directory
* `git add filename` - stage `filename` for commit
* `git commit -m msg` - commit stages files into local repo
* `git clone url` - clone remote repo `url` to local working directory


### Information Commands
* `git status` - show status of local repo
* `git log` - list commit history of current branch
* `git log --oneline` - list commit history (compact format)
* `git config --list` -- list local repo config settings


### Branching Commands
* `git branch` - lost of local branches
* `git branch branchName` - create local branch `branchName`

* `git checkout branchName` - switch to branch `branchName`
* `git checkout -b branchName` - create and switch to branch `branchName`


### Remote Commands
* 'git remote add alias url' - add new remote 'url' with alias 'origin'
* 'git push origin branchName' - push current local branch to remote branch 'branchName'
* 'git pull origin branchName' - pull and merge remote branch 'branchName' with current local branch

## Workflow:
1. Pull latest remote main into local main.	`git pull origin main`
2. Branch from updated local main.	`git checkout -b myBranch`
3. Work in local branch, committing frequently.
4. When ready to merge, pull remote `main` into local branch (must commit first) `git pull origin main`
5. Fix any merge conflicts, then commit.
6. Push to remote branch. `git push origin myBranch`
7. Create pull request.
8. Merge pull request.
