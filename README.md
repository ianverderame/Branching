## Git Cheat Sheet

Reference for using Git in team projects.
Summary of Git commands.

### Basic Commands
* `git init` - Initialize local Git repository
* `git add .` - Add all files in and under current directory to git index, staging them for commit
* `git commit -m "message"` - Commit changes to local repo with commit message "Message"

### Information Commands
* `git status` - display current status of local working directory/repository
* `git log` - list commit history
* `git log --oneline` - list commit history, compact format
* `git config -l` - List local Git configuration settings.

### Branching Commands
* `git branch` - List local git branches
* `git branch newBranchName` - Create local branch "newBranchName"
* `git checkout newBranchName` - Check out local branch "newBranchName"
* `git branch -M otherBranch` - Rename current branch to 'otherBranch'

### Remote Commands
* `git remote add origin remoteUrl` = Add alias "origin" for remote repository Url "remoteUrl"
* `git push origin main` - Push locally-committed changes to `main` branch on remote repository
* `git push -u origin main` - Same, setting "origin main" as default for subsequent `git push`
