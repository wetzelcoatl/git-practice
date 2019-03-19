

test

- git init: create a new git repository
-git status: compare working directory, staging area and current branch
- git add: add changes from working directory to staging area
-git commit changes from staging area to current branch
-git config: set or get configuration
-git log: show a history (or log) of project commits
git branch: list branches
git checkout: check out (switch to) a branch
git checkout -b create "branch name": creates and checks out new branch
-git show: show a single commits
- git diff: show the difference between commits, the staging area and the working directory
git branch -c: create a branch
git merge: Merge changes from different branches


a branch is a reference to a commit. when HEAD points to a branch, we say we're "on" that branch. When we make a commit while we're on a branch, the branch is updated to refer to the new commits


git stash: stash changes from working directory
git stash list: list stashes
git stash pop: apply stashed changes to working directory

What's HEAD?

Head is a ref to the "current" branch git commands like status, log, and branch use HEAD

## commit messages

Default editor is vim (can be changed)
or use git commit -m <message> to insert

first line should be clear

## Merging

Merging means to bring the changes from one branch into another

A fast-forward merge happens when the target branch was branched from the current one, and there are no new changes to the current branch since then.

An automatic merge happens when the two histories have diverged, but git is able ot reconcile them into one set of changes. This creates a new commit on the current branch
