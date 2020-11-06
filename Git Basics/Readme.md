## Basic Git commands

### Clone a repo
> #### ` git clone ` + ` link to SSH or CLI `

### Get details about some git command
> #### ` git help ` + ` your command `

### Create a new file in git bash (basics)
> #### ` touch ` + ` file name `

### Files not to be included while uploading(pushing) files inot github repo
> #### create ` .gitignore ` and add ` filename.extension ` or ` \folder name `

### Staging changes made in files 
> #### ` git add filename ` or ` git add . ` 

### Checking status
> #### ` git status `

### Commit changes made to the files
> #### ` git commit -a -m 'Commit message' `

### Push commited changes
> #### ` git push `

### To unstage changes (roll back to unstaged state)
> #### ` git reset HEAD ` + ` File Name `

### Git History
> #### ` git log `

### Git History in a good format
> #### ` git log --oneline --graph --decorate -all `
> ##### ` oneline ` to display only commmit ID and commit message
> ##### ` graph ` to show branch connections 
> ##### ` decorate ` which commits are mapped to which branch
> ##### ` all ` to display all logs

### Alisases to customise large commands to custom git command
> #### ` git config --global alias.` + ` your custom command name ` + ` original git command/s `
> #### Example : ` git config --global alias.myhistory 'log --oneline --graph --decorate -all `

### Rename a file on both gtihub repo and locally
> #### ` git mv current_filename new_filename ` + commit and push

### Override existing folder or file name in github repo
> #### ` git mv -f current_filename new_filename` + commit and push

### Delete a file on both github repo and locally
> #### ` git rm filename` + commit and push

### Get difference between to commits
> #### ` git diff commit_id1 commit_id2`

### For More Information  click [here](https://git-scm.com/docs)

### Official [git cheat sheet](https://training.github.com/downloads/github-git-cheat-sheet.pdf)