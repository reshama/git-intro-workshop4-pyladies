# Submit Pull Request

### Step 1:  fork the repo
https://github.com/WiMLDS/python_advanced

### Step 2:  clone the repo
Syntax:  `git clone <url>`  

### Step 3:  create a working branch (optional)
Syntax:  `git branch <branch_name>`  
`git branch reshama_wip`

### Step 4:  switch to working branch (optional)
Syntax:  `git checkout <branch_name>`  


### Step 5:  Add remote `upstream`
```
 7429  git remote -v
 7430  git add remote upstream https://github.com/WiMLDS/python_advanced.git
 7431  git remote add upstream https://github.com/WiMLDS/python_advanced.git
 7432  git remote -v
 7433  ls
 7434  cd submissions
 7435  ls
 7436  mkdir reshama
 7437  cd reshama
 7438  touch roses.txt
 7439  git status
 7440  git add roses.txt
 7441  git status
 7442  git commit -m 'adding first flower file'
 7443  git push origin master
```

### Step 5:  create a file
* create a folder with your name here:  https://github.com/WiMLDS/python_advanced/tree/master/submissions
* `cd` into this folder, create a Python file with your name.  (Example:  `reshama.py`)

### Step 6:  add a file
Syntax:  `git add <filename>`  

### Step 7:  commit a file
Syntax:  `git commit -m 'message'`    
<br>
`git commit -m 'adding my python name file'`

### Step 8:  Push changes to your 'working branch'
Syntax:  `git push <remote_name> <branch_name>`   
<br>
`git push origin reshama_wip`
