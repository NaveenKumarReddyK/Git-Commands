## Commits

### Commit your changes
> ### ` stage your changes ` + ` git commit -m 'Commit Message `

### Stash your changes ( save your current changes for making any changes that affects the current wotk )
> ### ` git stash `

### Apply the stashed changes
> ### ` git stash apply ` ( the stashed changes are present and can be used again )
> ### ` git stash pop` ( stashed changes are applied and deleted ) 

### Reset your commit to some point in working directory 
> ### ` git reset --soft HEAD~commitNumber `

### Change your recently pushed commit message
> ### ` git commit --amend -m " new commit message " ` + ` push your changes `

### Add new changes to recent commit without any new message 
> ### ` git commit --amend --no-edit ` + ` push your changes `

### Add new changes to recent commit without any new message 
> ### ` git commit --amend -m " new commit message " ` + ` push your changes `


## Modify a commit in hisorty other then the recent commit ( HEAD~1 )
> #### ` git stash ` ( Stash the changes )
> #### ` git rebase -i HEAD~commitNumber ` ( Rebase to the commit which you want to chnage )
> #### ` git log -g ` ( Get the commit number to be modified )
> #### ` Change the word ` pick ` in intercative editor to `edit` beside the commit which you want to change `
> #### ` Close the editor `
> #### ` git stash pop / apply ` ( Pop the stashed changes )
> #### ` git add filePath / git add . ` ( Stage the files which you want to commit )
> #### ` If you did not add all files then stash the changes after staging the required file `
> #### ` git commit ` + ` —-amend -—no-edit / -m “New commit message”  `
> #### ` git rebase —-continue `
> #### ` git push / git push -f  `



