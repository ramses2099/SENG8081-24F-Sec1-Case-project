# SENG8081-24F-Sec1-Case-project
Assignment # 1 - Repository Collaboration and Preparation Assignment

# Steps for assignment
1. clone the repository
```
git clone https://github.com/AsimInamdar/SENG8081-24F-Sec1-Case-project
```
1. check the list of branch
```
git branch -r
```
1. use the branch development 
```
 git checkout development
```
1. make some changes or add one file e.g.
```
test_name_student_number.txt
```
1. push the file to the remote branch.
```
git status
git add .
git commit -m "add new file test_name_student_number.txt the branch development"
git push -u origin development
```


## create branch

git checkout -b <name>

## creating remote branches

git push -u origin <name>

## deleting branches

git branch -d <name>

## Git allows users to use several methods for listing remote branches:

1. git branch
1. git branch -r. Lists all the remote branches.
1. git branch -r -v. Lists all the remote branches with the latest commit hash and commit message.
1. git ls-remote. Lists all the references in the remote repository, including the branches.
1. git remote show [remote_name]. Shows information about the specified remote, including the remote branches.
1. git branch -a. Shows all the local and remote branches.

### My Name- Neha Bhatia
