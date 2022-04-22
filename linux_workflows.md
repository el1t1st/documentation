# SSH Keys

## How to create a public ssh key?

`ssh-keygen -t ed25519 -C "your_email_address"`

# Kitty

## How to copy the contents of a file into the clipboard from the command line?

`bat <file_name> | kitty +kitten clipboard`

## How to paste the clipboard contents to the command line?

`kitty +kitten clipboard --get-clipboard`

## What is the key shortcut to copy selected to clipboard?

`<Ctl-Ins>`

## What is the key shortcut to paste the contents of the clipboard?

`<Shift-Ins>`

# Git

## What is the workflow to add, comment and commit to the master repository?

`git add .`
`git commit -m "comments for this commit`
`git push origin master`

## How to create and switch to a new branch?

`git checkout -b "name_of_new_branch"`

## What is the workflow to add, comment and commit to a branch repository?

`git add .`
`git commit -m "comments for this commit"`
`git push origin "name_of_the_branch"`

## How to push the changes of a branch to the repository?

`git push origin "name_of_the_branch"`

## How to merge a branch to the master?

`git checkout master`
`git merge "name_of_the_branch_to_merge"`
`git push origin master`

## How to delete a local branch?

`git branch -D "name_of_the_branch_to_delete"`

## How to delete a remote branch?

`git push origin --delete "name_of_the_remote_brach_to_delete"`

## Workflow to change the an existing origin address of git?

`git remote -v`
`git remote set-url origin "address_of_the_git_origin"`

## What is the workflow to add a new origin address to git?

`git remote -v`
`git remote add origin "address_of_the_git_origin"`

## How to pull the latest changes from the master to the local repository?

`git pull`

## How to cancel the changes you made to a local file, and get the version committed to the repo?

`git checkout "the_name_of_the_file"`

## What is the workflow to initialize a git repo?

`git init`

# Neovim

# Useful shell commands

## How to change the default shell for another user?

`chsh -s /bin/bash "user_name"`

## What is the command to show the current shell?

`echo $SHELL`

## How to find the location of a command in the command line?

`whereis "name_of_the_command"`
`whereis bash`
`whereis zsh`
