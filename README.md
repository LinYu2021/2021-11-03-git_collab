# 2021-11-03-git_collag

- `git clone <URL>`: download the git repository <URL> to current directory
	- `git init`: creates git repo in current folder

# branch
- `git branch <NAME>`: creates a new branch <NAME> where HEAD is
	- `git branch -a`: lists all your branches, including the remote
- `git switch <BRANCH>`: move to the branch
	- `git checkout <BRANCH>`: older way to switch
- `git log --oneline --graph --all`
- `git switch -c <BRANCH>`
- pull request

# Cleanup
- `git fetch --prune`
- `git branch -d <BRANCH>`:delte the branch, will fail if merge not completed
	- `git branch -D <BRANCH>`: force delete branch

