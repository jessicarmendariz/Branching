## Git Branching Practice and Cheat Sheet

### Basic Commands
* 'git init' - initialize a local git repo in current folder
* "git add" - stage  current changes for commit
* 'git commit -m "Message"' - commit staged changes to local repo

### Information Commands
* 'git status' - show status of working folder and repo
* 'git log' - show log of commits
* 'git log --oneline' - compact commit history
* 'git config -l' - list git configuration


### Branching Commands
* 'git branch' - list local branches, show which branch we are on
* 'git branch -M branchName' - rename current branch to 'branchName'
* 'git branch newBranch' - create local branch 'newBranch'
* 'git checkout branchName' - go to branch 'branchName'

### Remote Commands
* `git remote add origin someRemoteRepoUrl` - link local repo with remote `someRemoteRepoUrl`
* `git push origin main` - push local commits to remote branch main
*`git push origin branchName` - push to remote branch `branchName`
