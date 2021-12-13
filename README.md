## Git Cheat Sheet

Added in branch main.
Reference for using Git in team projects.
Summary of Git Commands.


### Basic Commands
* `git init` - Initialize local Git Repository
* `git add .` - Add all files in and under current directory to git index, staging them for commit
* `git commit -m "Message"` - Commit changes to local repo with commit message "Message"

### Information Commands
* `git status` - display current status of working directory/repository
* `git log` - list commit history
* `git log --oneline`  - List commit history, compact format

### Branching Commands
* `git branch` - check to see what branch you are on
* `git branch newBranchName` - create a new branch where you can chose the name
* `git checkout newBranchName` - switch to the new branch
* `git branch -M otherBranch` - rename current branch


### Remote Commands
* `git remote add origin remote URL ` - Add alias "origin" for rmeote reposity Url "remoteURL"
* `git push origin main` - Push locally-commited changes to `main` branch on remote repository
* `git push -u origin main` - Same, setting `origin main` as a default for subsequent `git push`
