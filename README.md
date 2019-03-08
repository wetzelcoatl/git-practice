adfdfadfd fadfaefeawf

test

- git init: create a repository
-git status: compare working directory, stagin area and current branch
- git add: add changes from working directory to staging area
-git commit changes from staging area to current branch
-git config: set or get configuration
-git log: show history of project commits
git branch: list branches
git checkout -b create "branch name": creates and checksout new branch
a branch is a reference to a commit. when HEAD points to a branch, we say we're "on" that branch. When we make a commit while we're on a branch, the branch is updated to refer to the new commits
git checkout: checkout a branch

git stash: stash changes from working directory
git stash list: list stashes
git stash pop: apply stashed changes to working directory
What's HEAD?

Head is a ref to the "current" branch git commands like status, log, and branch use HEAD
## commit messages

Default editor is vim (can be changed)
or use git commit -m <message> to insert

first line should be clear
