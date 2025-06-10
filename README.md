# GIT
This file will walk you through the git commands that a DevOps Engineer should know.
### Git Basics
- **git init**: Initializes a new git repository.
- **git add**: Stages changes in the working directory to be committed.
- **git commit**: Commits the changes in the staging area.
- **git log**: Displays a log of all commits made to the repository.
- **git status**: Displays the status of the repository.
- **git branch**: Lists, creates, or deletes branches.
- **git checkout**: Switches between branches or restores working tree files.
- **git merge**: Merges changes from one branch into another.
- **git remote**: Adds, removes, updates, and lists remote repositories.
- **git fetch**: Downloads objects and refs from another repository.
- **git push**: Updates remote refs using local refs.
- **git pull**: Fetches from and integrates with another repository or remote branch.
- **git diff**: Shows changes between commits, commit and working tree, etc.
- **git reset**: Resets current HEAD to the specified state.
- **git tag**: Creates, lists, deletes, or verifies a tag object signed with GPG
### Git Branching
- **git branch -m
- **git branch -d
- **git branch -r
- **git checkout -b
- **git checkout -t
- **git checkout -m
- **git merge --no-ff
- **git merge --squash
- **git merge --abort
- **git merge --continue
- **git merge -s
- **git merge -X

Let's take a closer look at some of these commands.

- git add file :	Adds a specific file to the staging area
- git add . :	Stages all changes in the working directory
- git add dir :	Adds all files in a directory
- git add -A :	Adds all changes in the entire repo (same as . but more explicit)
- git add -u :	Adds only modified and deleted files (not new/untracked ones)
- git add -i :	Interactive staging (for more complex staging scenarios)

