

test

- git init: create a new git repository
-git status: compare working directory, stagin area and current branch
- git add: add changes from working directory to staging area
-git commit changes from staging area to current branch
-git config: set or get configuration
-git log: show a history (or log) of project commits
-git checkout: check out branch
-git show: show a single commits
- git diff: show the difference between commits, the staging area and the working directory
git merege: Merge changes from different branches
## commit messages

Default editor is vim (can be changed)
or use git commit -m <message> to insert

first line should be clear

## Merging

Merging means to bring the changes from one branch into another

A fast-forward merge happens when the target branch was branched from the current one, and there are no new changes to the current branch since then.

An automatic merge happens when the tow histories have diverged, but git is able ot reconcile them into one set of changes. This creates a new commit on the current branch
