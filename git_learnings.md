# 1. Configuring GIT
*git config --global user.name "user name"*     
*git config --global user.email "email@email.com"*  
*git config --list*

## 1.1 Ideal flow of working on GIT and with GITHUB
GITHUB  ---> Clone to local repo ---> Do the changes ---> Stage the files   ---> Commit with comments ---> Push that again to GITHUB

# 2. GIT + GITHUB + VSCODE
## 2.1 GIT Status Messages
`git status`
### 2.1.1 untracked 
> new file or never committed, git doesn't know abything about it.   
### 2.1.2 modified  
> changed at some time but not committed so far  
### 2.1.3 staged
> file is ready to be committed
### 2.1.4 unmodified
> committed recently e.g. git commit -m "some message"

## 2.2 GIT Push
`git push origin main`  
> here "origin" is the remote original copy and we can name it anything we prefer to name, and  
> "main" is the name of branch


## 2.3 Create a folder on your computer
`git init`
> initializing the git into the folder and check if the .git hidden folder is created in the folder.    
> do the changes as you may require e.g. index.html, style.css

`git status`
> it should show the untracked files as index.html and style.css

`git add`  
`git commit -m "add initial files"`
> now go to git hub
> create a new repo e.g. studen-apnacollege/localrepo   --> create repository
> before publishing the local changes    
`git remote add origin <--repository-link--->` 

### 2.3.1 Verify Remote 
`git remote -v`
### 2.3.2 Verify branch
`git branch`
### 2.3.3 Rename the branch to main
`git branch -M "main"`
### 2.3.4 Checking out a particular branch
`git checkot <---branch name--->`
### 2.3.5 Create a new branch
`git checkout -b <--new branch name-->`
### 2.3.6 Delete a branch 
`git branch -d <---branch name--->`
### 2.3.7 Push the branch 
`git push origin main`    
or  
`git push -u origin main`
> this will set the upstream to keep working on this branch so that next time need to "git push"


### 2.3.8 Merge in git 
`git diff <---branch--->`
> to compare commits branches files and more 

`git merge <--destination branch name-->`

### 2.3.9 Undoing Changes
#### 2.3.9.1    Staged Changes  
> added but not yet committed   

`git reset <--file name-->`     
or  
`git reset` # to reset all the changes in all of the files

#### 2.3.9.2  Committed Changes (for one file)
`git reset HEAD~1`  
> here ~1 means remove the last change and   
> HEAD means the lastest

> to get more information about the changes use     
`git log`


#### 2.3.9.3 Committed Changes (for many commits)
`git reset <--commit hash--->`  
> the commit hash can be derived from git log output, we can use first 7-8 digit of commit hash  
or  
`git reset  --hard <---commit hash--->`





























