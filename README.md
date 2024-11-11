# Introduction to Git

## Create a new Git Repo

```
git init
```
## Check status of your repo
```
git status
```
## To add files to git
```
git <filename1> <filename2>
```
## To commit a file
```
git commit -m'<Message>'
```
## Check git remote
```
git remote show origin
```
## Check branch
```
git branch
```
## Check git history
```
git log
```
## Push local branch to remote
```
git push <remote name><branch name>

git push origin main/master
```
## Fist time Upload
```
git init

git remote add origin <repository-url>

git add .

git commit -m "First time upload"

git push -u origin main/master
```
## Update Coding
```
git pull origin main/master

git add .

git commit -m "Update commit"

git push origin main/master
```