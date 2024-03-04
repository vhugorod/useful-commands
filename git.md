## git config
Usage: `git config --global user.name “[name]”`

Usage: `git config --global user.email “[email address]”`

This command sets the author name and email address respectively to be used with your commits.

## git config
Usage: `git config --list`

This command shows your github configuration.

## git clone
Usage: `git clone [url]` 

This command is used to obtain a repository from an existing URL.

## git init
Usage: `git init [repository name]`

This command is used to start a new repository.

## git add
Usage: `git add [file]`

This command adds a unique file to the staging area.

Usage: `git add .`  

This command adds all files to the staging area.

## git clean -fd
Usage: `git clean -fd`

This command remove untracked directories in addition to untracked files.

Usage: `git clean -fd`  

## git commit
Usage: `git commit -m “[write a semantic commit message]”`

This command records or snapshots the file permanently in the version history.

Usage: `git commit -a`  

This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then. 
Note: with this command you dont need to use git add.

Usage: `git commit --amend -m “[write a semantic commit message]”`

This command change the last commit message locally.

## git status
Usage: `git status`  

This command lists all the files that have to be committed.

## git log
Usage: `git log`  

This command is used to list the version history for the current branch.

Usage: `git log –follow[file]`

This command lists version history for a file, including the renaming of files also.

Usage: `git log --oneline` 

This command is used to observe all changes on my branch DEV.

## git checkout
Usage: `git checkout [branch name]`

This command is used to switch from one branch to another.

Usage: `git checkout -b [branch name]`  

This command creates a new branch and also switches to it.

Usage: `git checkout -t [remote name]/[branch name]`

This command get remote branch to local project.

## git branch
Usage: `git branch`  

This command lists all the local branches in the current repository.

Usage: `git branch --all`  

This command lists all the local and remote branches in the repository.

Usage: `git branch [branch name]`  

This command creates a new branch.

Usage: `git branch -d [branch name]`  

This command deletes the branch.

## git push
Usage: `git push [variable name] master`  

This command sends the committed changes of master branch to your remote repository.

Usage: `git push [variable name] [branch]`

This command sends the branch commits to your remote repository.

Usage: `git push –all [variable name]` 

This command pushes all branches to your remote repository.

Usage: `git push [variable name] :[branch name]` 

This command deletes a branch on your remote repository.

Usage: `git push origin 1.0.0`
  
This command is used to push a tag in remote repository.

Usage: `git push --delete origin v1.0`

This command is used to delete a remote tag.

## git pull
Usage: `git pull`

This command fetches changes on the remote server to your working directory.

Usage: `git pull [repository Link]`

This command fetches and merges changes on the remote server to your working directory.

## git diff
Usage: `git diff`  

This command shows the file differences which are not yet staged.

Usage: `git diff –staged` 

This command shows the differences between the files in the staging area and the latest version present.

Usage: `git diff [first branch] [second branch]`  

This command shows the differences between the two branches mentioned.

## git revert
Usage: `git revert [commit]`  

This command unstages the file and add a commit.

## git reset
Usage: `git reset [file]`  

This command unstages the file, but it preserves the file contents.

Usage: `git reset [commit]`  

This command undoes all the commits after the specified commit and preserves the changes locally.

Usage: `git reset --hard [commit]`  

This command undoes the commits and deletes the changes locally.

Usage: `git reset HEAD~3 --hard [commit]`  

This command undoes the last 3 commits and preserves the changes locally(staging area).

Usage: `git reset HEAD~3 --soft [commit]` 

This command discards all history and goes back to the specified commit.

## git reflog
Usage: `git reflog`

This command is used to list the Hashes in lines.

## git show
Usage: `git show [commit]`  

This command shows the metadata and content changes of the specified commit.

## git merge
Usage: `git merge [branch name]`  

This command merges the specified branch’s history into the current branch.

## git remote
Usage: `git remote add [variable name] [remote Server Link]`  

This command is used to connect your local repository to the remote server.

This command fetches and merges changes on the remote server to your working directory.

## git stash
Usage: `git stash`  

This command temporarily stores the modified tracked files.
Later on, we need to change to the main branch, create another branch from the main one, fix the code, merge, go back to the old branch and use git stash apply.

Usage: `git stash apply`  

This command get back the modifications u were working on.

Usage: `git stash save`  

This command temporarily stores all the modified tracked files.

Usage: `git stash pop` 

This command restores the most recently stashed files.

Usage: `git stash list`  

This command lists all stashed changesets.

Usage: `git stash drop`  

This command discards the most recently stashed changeset.

## git tag
Usage: `git tag 1.0.0 [commitID]`
  
You can use tagging to mark a significant changeset, such as a release.

Usage: `git tag -d v1.0`

This command is used to delete a local tag.

## git cherry-pick

Usage: `git cherry-pick COMMIT HASH`

This command get the specified commit:

## git search

Usage: `git grep "foo()"`

This command search the working directory for foo():

## git fetch
Usage: `git fetch origin git reset --hard origin/master git clean -f -d`

This command is used to sync remote repositories to localhost. It won't show the branch's name, but it's in your SO.

## git rm
Usage: `git rm -r [file]`

This command is used to delete a file or directory from local tracking git. It helps us to delete files from remote origin(GITHUB). 

Usage: `git rm --cached -r [file]`

This command is used to remove duplicate file tracking in Git.

Usage: `git rm [file]`  

This command deletes the file from your working directory and stages the deletion.

## Semantic commit messages

### chore: A change that neither fix a bug nor adds a feature

### ci: A CI change

### docs: A documentation change or fix

### feat: A new feature

### refactor: Refactor a method or function

### fix: A bug fix

### test: A test-related change

### wip: A implementation that is not finished
