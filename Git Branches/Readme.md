> ## Branches are like pointer which point to the main branch (master, where all the code to be relased is stored) where we can change code before releasing it into main branch without affecting it

### Create a branch
> #### ` git branch ` + ` your branch name `

### List all branches 
> #### ` git branch`

### Navigate to some branch
> #### ` git checkout `+ ` branch name ` (default is ` master `)

### If created on github.com to make it available locally
> #### pull request from github : ` git pull `
> #### Then move to your branch

### Push changes to particular branch
> #### add + commit + ` git push origin your_branchName `
> #### by default ` git push ` is ` git push origin master `

### Merging branches 
> #### !!! If same line in file is different in both branches then we should change the codes to final codes . If not changes then ` CONFLICT ` arises and we cannot push changes
> #### First navigate to branch you want to merge and then merge other branch you want to merge
> #### I have navogated to branch-1 and then ` git merge branch-2 ` merges branch-1 and branch-2

### Deleting branches locally
> #### ` git branch -d branch_Name `

### Deleting branches both locally and on github repo
> #### ` git push origin --delete branch_Name`   

### For More Information  click [here](https://git-scm.com/docs/git-branch)