
# git basics

- `git init`  : initialize git repository in current working directory
- `git status` : gives you the status
- `git add <FILE>`: adds FILE to the staging area
- `git commit`: creates a commit, you provide message

- `git log`: shows you the log of commits
	- `git log --oneline` : shows you the one line version of log
- `HEAD` : where you are currently are (the version of the file on your comp)
- `git diff HEAD~<NUM> <FILE>` : compare current file to file <NUM> ago
	- `git diff <HASH> <FILE>`: compares the current file to file on  <HASH>

- Use `git status` to help you find the commands to unstage or restore file
- `git checkout <HASH> <FILE>` : to undelete/restore a file from prev commit
	
#remotes
	
	- `ssh-keygen` : to create ssh keys
	- `git remote add <URL>` : adss the URL
	- `git push origin main`: push to the main branch to the origin remote
