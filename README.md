

test

- git init: create a new git repository
-git status: compare working directory, staging area and current branch
- git add: add changes from working directory to staging area
-git commit changes from staging area to current branch
-git config: set or get configuration
-git log: show a history (or log) of project commits
-git branch: list branches
-git checkout: check out (switch to) a branch
-git checkout -b create "branch name": creates and checks out new branch
-git show: show a single commits
- git diff: show the difference between commits, the staging area and the working directory
-git branch -c: create a branch
-git merge: Merge changes from different branches
-git remote add <remote? <url>: add a new <remote> at <url>
-git remote -v: list remote repositories
-git push -u <rmeote> <branch>: push <branch> to <remote>, and set default upstream for <branch>
-git fetch: fetch changes from remote repository
-git pull: fetch, then merge

a branch is a reference to a commit. when HEAD points to a branch, we say we're "on" that branch. When we make a commit while we're on a branch, the branch is updated to refer to the new commits


git stash: stash changes from working directory
git stash list: list stashes
git stash pop: apply stashed changes to working directory

What's HEAD?

Head is a ref to the "current" branch git commands like status, log, and branch use HEAD

## Commit Messages

Default editor is vim (can be changed)
or use git commit -m <message> to insert

first line should be clear

## Merging

Merging means to bring the changes from one branch into another

A fast-forward merge happens when the target branch was branched from the current one, and there are no new changes to the current branch since then.

An automatic merge happens when the two histories have diverged, but git is able ot reconcile them into one set of changes. This creates a new commit on the current branch

##What's a remote?

A remote repo is one hosted somewhere other than our local machine. We can addremotes with 'git remote add', and set up *tracking branches* to track differences between our local and remote repos.

we can push to remotes with 'git push' and fetch from the with 'git fetch'. We can also fetch and merge in one command with git pull.
