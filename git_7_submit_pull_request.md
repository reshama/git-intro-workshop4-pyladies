# Submit Pull Request

### Step 1:  fork the repo
https://github.com/WiMLDS/python_advanced

### Step 2:  clone the forked repo
>Syntax:  `git clone <url>`  

```bash
git clone https://github.com/reshama/python_advanced.git
```
### Step 3:  `cd` into this forked repo

>Syntax:  `cd <directory>`

```bash
cd python_advanced
```

### Step 4:  Display branch names
>Syntax:  `git branch`

### Step 5:  create a working branch 
>Syntax:  `git branch <branch_name>`  

```bash
git branch reshama_wip
```

### Step 6:  switch to working branch (optional)
>Syntax:  `git checkout <branch_name>`  

```bash
git checkout reshama_wip
```

### Step 7:  Display remote names
>Syntax:  `git remote -v`  

```bash
git remote -v
```

### Step 8:  Add remote `upstream`
>Syntax:  `git remote add upstream <url>`  

```bash
git remote add upstream https://github.com/WiMLDS/python_advanced.git
```

### Step 9:  create a directory and add a file
* create a folder with your name here:  https://github.com/reshama/python_advanced/tree/master/submissions
* `cd` into this folder, create a Python file.  (Example:  `print_name.py`)

```bash
cd submissions
mkdir reshama
cd reshama
```

>Syntax:  `touch <file_name>`  
```bash
touch print_name.py
```

### Step 10:  add a file
>Syntax:  `git add <filename>`  

```bash
git add print_name.py
```

### Step 11:  commit a file
>Syntax:  `git commit -m 'message'`    

`git commit -m 'adding my python name file'`

### Step 12:  Push changes to your 'working branch'
>Syntax:  `git push <remote_name> <branch_name>`   

```bash
git push origin reshama_wip
```
