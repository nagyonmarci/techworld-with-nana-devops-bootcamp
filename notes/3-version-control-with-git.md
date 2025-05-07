## 3 - Version Control with Git

### Basic Commands & Features
* git clone: Clone a remote repository to your local machine.
* git init: Initialize a new local Git repository.
* git add: Add file(s) to the staging area.
* git commit: Commit staged changes to the repository history.
* git status: Show the current status of files (modified, staged, etc.).
* git log: View commit history.

### Branch Management
* git branch: List all branches or create a new branch.
* git branch -d: Delete a branch.
* git checkout <branch>: Switch to another branch.
* git checkout -b <branch>: Create and switch to a new branch.
* git merge <branch>: Merge another branch into the current branch.
* git rebase: Reapply commits on top of another base tip (linearizes history).

### Remote Repository Management
* git remote add origin <remote_repo>: Add a remote repository.
* git push: Push local commits to the remote repository.
* git pull: Fetch and merge changes from the remote repository.
* git push --set-upstream origin master: Link a local branch with its remote counterpart.

### File Management & Deletion
* git rm -r --cached <file>: Remove a file from staging (keeps it locally).
* git rm --cached <file>: Remove a file from the repository (keeps it locally).

### Other Useful Commands
* git stash: Temporarily save changes not yet committed.
* git stash pop: Reapply stashed changes, save unfinished changes.
* git reset --hard HEAD~1: Undo the last commit and discard changes, revert & discard changes to commit, ~<number commits to revert>.
* git reset HEAD~1: Undo the last commit but keep changes locally.
* git commit --amend: Edit the last commit, merge changes into last commit.
* git push --force: Force-push changes to the remote repository.
* git revert <commit_hash>: Create a new commit that undoes a previous commit.

### Removing Git from a Project
* rm -fr .git: Delete the .git directory.

### Best practices
* Use one branch per feature.
* Keep separate dev and master branches.
* Use merge/pull requests for code reviews and merging.
* Delete branches after merging.
* Use a .gitignore file to exclude unnecessary files.
