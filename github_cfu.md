# **Git Commands Charles Knows**

## `git init`
> Initializes "git" inside of what ever directory you are currently in.

## `git status`
> Displays the status of the project btween your local repo and the remote repo. Typically used to see if you have added your changes to the staging area.

## `git diff`
> Displays what is different between local and remote repos. How many lines have been added, deletions, etc.

## `git log`
> Shows a log of the git commits made in that repo. There is a flag that you can add to display just the commit messages but I can't remember what it is just now.

### *THIS LIST OF GIT COMMANDS IS NOT COMPREHENSIVE!*

# **How to remove origin connection with git commands**

## Removing Connection to Remote Repo
> First run  git command `git remote -v` to identify your current connection. Then run `git remote remove origin` to break connection to current remote repo. Optional to run `git remote -v` to verify no connection to remote repo. Then run `git rmote add origin [insert remote SSH code here]` to connect to the preferred remote repo!