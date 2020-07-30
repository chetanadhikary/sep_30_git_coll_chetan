# sep_30 : Git Collaboration
To learn about the git collaboration

## Branches

- 'git clone <url>': Downloads the repository from the web to your local computer 
 - make sure you dont nest this command into another repository
 - just like 'git init', only do this once per repo
 
- 'git branch <branch name>': create a new branch where HEAD is
	- 'git branch -a': list all the branches
- 'git switch <branch name>' : move to branch

## Pull Requests (online merge)
- 'git log --oneline --graph --decorate --all': shows you your git history tree
	- you can look up how to set this as git alias
- 'git fetch --prune': clean your git history , and remove references from remote	that does not exist 
- 'git branch -d <branch_name>': deletes the branch from local 
- Pull request : when you push a branch to remote, and merge the 
