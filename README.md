# python_work
## create a new repository on the command line   
```
git init
git add README.md 
git commit -m "first commit"  
git branch -M main  
git remote add origin git@github.com:Pisceshub/- python_work.git  
git push -u origin main  
```
 
## push an existing repository from the command line   

```
git remote add origin git@github.com:Pisceshub/- python_work.git  
git branch -M main  
git push -u origin main  
```

## git study command :


### 0. Frequently used：
```
git add .
git commit -m 'first commit'
git push -u origin main 
git clone  git@github.com:Pisceshub/- python_work.git  python_pro 
 
```


### 1. git create repository
```
git init  # will create a new .git
git init  newrepo # will create a new newrepo,which include data and resources of the repository
```
### 2. git add file
``` 
git add .
git add *.c  # .c files
git add README # README files
...
```

### 3. git commit 
```
git commit -m 'first commit' # '__' that need to notes commit information

```

### 4. git clone repository
```dotnetcli
git clone <repo>  <directory> 
```


### 5. git info
```
git config --list 
# change information :
git config -e    # for the current repository
git config -e --global   # for the global repository

git config --global user.name "your github name "
git config --global user.email your_github_email@runoob.com
```

more information reference to [git base operate](https://www.runoob.com/git/git-basic-operations.html)
