[TOC]

# Git使用方法

## Installation

### linux

`apt install git`

### Mac

### windows
## config git globally

`git config —-global user.name "RyanRen"`

`git config —global user.email "yan.r@163.com"`

## create a repository on github

## initialize a local repository

`git init`

## fetch latest from remote repository

`git pull —all`

`git fetch origin master`

### move a file to staging area for committing

`git add XXXX` or `git add -A` for all files

### remove files from staging area

`git reset XXX`

### check status

`git status`

## create a local branch

`git branch name-of-branch`

`git branch -a`

## switch working on a branch

`git checkout name-of-branch`

## push local branch to remote repository

`git push -u origin name-of-branch`

## delete a local branch & delete a remote branch

`git branch -d name-of-branch`

`git push origin --delete name-of-branch`



### 问题

1. 本地创建一个空目录，`git init` 初始化为repository. 通过`git remote add`添加远程仓库路径，然后`git fetch origin`获取远程仓库。可是结果为空。必须运行`git merge` 才能看到文件。***原因：*** 
2. 
