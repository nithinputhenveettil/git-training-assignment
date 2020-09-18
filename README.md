# SOME BASIC GIT COMMANDS

## Initialise the Github Repositories

Initialise the name and email address to be used with your repositories.
```
git config --global user.name "Edwin Yeldho"
git config --global user.email edwin@example.com
```
## Create a new local repository

```
git init [repository name]
```
## Check out a repository

```
git clone [url]
```

## Basic Snapshotting

* `git status` To check status.
* `git add [file-name.txt]` To add a file to the staging area.
* `git add -A` To add all new and changed files to the staging area.
* `git commit -m "[commit message]"` Commit changes.
* `git commit -a  `This command commits any files you’ve added with the git add command and commit any files you’ve changed since then.
* `git rm -r [file-name.txt]` Remove a file (or folder).

## Branching & Merging

* `git branch -a` List all branches (local and remote).
* `git branch [branch name]` Create a new branch.
* `git branch -d [branch name]` Delete a branch.
* `git checkout [branch name]` Switch to a branch.
* `git checkout -` Switch to the branch last checked out.
* `git checkout -- [file-name.txt]` Discard changes to a file.
* `git merge [branch name]` Merge a branch into the active branch.
* `git merge [source branch] [target branch]` Merge a branch into a target branch.
* `git branch` List branches (the asterisk denotes the current branch).
* `git push origin --delete [branch name]` Delete a remote branch.
* `git checkout -b [branch name]` Create a new branch and switch to it.
* `git checkout -b [branch name] origin/[branch name]` Clone a remote branch and switch to it.
* `git branch -m [old branch name] [new branch name]` Rename a local branch.


## Sharing & Updating Projects

* `git push` Push changes to remote repository (remembered branch).
* `git push origin --delete [branch name]` Delete a remote branch.
* `git pull` Update local repository to the newest commit.
* `git push origin [branch name]` Push a branch to your remote repository.
* `git push -u origin [branch name]` Push changes to remote repository (and remember the branch).
* `git pull origin [branch name]` Pull changes from remote repository.
* `git remote add origin ssh://git@github.com/[username]/[repository-name].git` Add a remote repository.
* `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` Set a repository's origin branch to SSH.

## Inspection & Comparison

* `git log` View changes.
* `git log --oneline` View changes (briefly).
* `git log --summary` View changes (detailed).
* `git diff [source branch] [target branch]` Preview changes before merging.
* `git diff`This command shows the file differences which are not yet staged.
* `git diff –staged `This command shows the differences between the files in the staging area and the latest version present.
