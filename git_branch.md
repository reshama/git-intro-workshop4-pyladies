# Git:  Branch
 
 
 * **List branches**  
    `$ git branch`
 * **Create a new branch**  
    `$ git branch reshama_wip`
 * **Navigate between branches**  
    `$ git checkout branchname`
 * **Create and switch to branch** (2 steps in 1 line)  
    `$ git checkout -b testbranch`

 * **Delete a branch** (safe delete; won't delete if there are unmerged changes)  
    `$ git branch -d reshama_wip`
 * **Delete a branch** (force delete; will delete even if branch has unmerged changes)  
    `$ git branch -D reshama_wip`


 * **Rename a branch** (whichever is the current one, be careful)  
    `$ git branch -m newone_wip`
 * **Rename a branch** (can specify oldname and newname)  
    `$ git branch -m <oldname> <newname>`


 * **Back to main branch**  
    `$ git checkout master`
 * **Merge branches** (will merge specified <branchname> into current branch)  
    `$ git merge <branchname>`

### Copy file/folder from one branch to current branch (`master`)

Run this from the branch where you want the file to end up:  
on:  `master` branch
```
git checkout branch_wip myfile.txt
```

### Copy directory from one branch to current branch (`master`)
on:  `master` branch
```
git checkout branch_wip myfolder/** 
```
