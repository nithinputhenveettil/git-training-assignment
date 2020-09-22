# Setup the user name and email id

Setup a name and email address that is that will be associate with each history marker
- `git config --global user.name “[firstname lastname]”`
- `git config --global user.email “[valid-email]”`

# SETUP & INIT

create a local repository
- `git init [repository name]`
retrieve an entire repository from a hosted location via URL
- `git clone [url]`

# snapshotting

- `git status`
	Check status
- `git add [file]`
	Add a file that we made a change.
- `git commit -m “[Message]”`
	commit your staged content as a new commit snapshot
- `git rm -r [file-name.txt]` 
	Remove a file

# Branching & Merging

- `git branch`
	list your branches and it will highlight the currently active branch
- `git branch [branch-name]`
	create a new branch 
- `git checkout [branch-name]`
	switch to another branch and check it out into your working directory
- `git branch -d [branch name]` 
	Delete a branch 
- `git push origin --delete [branch name]` 
	Delete a remote branch 
- `git checkout -b [branch name]` 
	Create a new branch and switch to it
- `git merge [branch]`
	merge the specified branch’s history into the current one
- `git merge [source branch] [target branch]`
	Merge a branch into a target branch 

# Sharing & Updating
- `git push origin [branch name]` 
	Push a branch to your remote repository
- `git push -u origin [branch name]` 
	Push changes to remote repository 
- `git push origin --delete [branch name]` 
	Delete a remote branch 
- `git pull` 
	Update local repository to the newest commit 
- `git pull origin [branch name]` 
	Pull changes from remote repository 
- `git remote add origin ssh://git@github.com/[username]/[repository-name].git`
	Add a remote repository
- `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` 
	Set a repository's origin branch to SSH

#  Inspection & Comparison
- `git log`
	show all the commits 
- `git log --summary` 
	View changes (detailed) 
- `git diff`
	This command shows the file differences which are not yet staged.
- `git diff [source branch] [target branch]` 
	Preview changes before merging 






