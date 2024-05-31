# Git and GitHub Basics

## Introduction
There are two ways you can start using git repository, either you can start a local git repo on your local machine and later add this to any remote repo like github/gitlab, or you can directly start a remote repo in github/gitlab and clone it to local machine and work on it.


## Getting Started

**Install Git ** - Ubuntu usually comes with git. incase if you dont have, install it by using the following command,

1. To check whether git is installed on the system, this will show the current git version.
```bash
git --version
```
2. To install git using apt 
```bash
sudo apt install git
```
3. **Set Up Git**: Configure your Git username and email using the following commands:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
4. Initialize git in a directory/folder
```bash
git init
```
5. Stage the changes
```bash
git add <file name> #use this to add by file name
git add . # use this for adding all the changes to staging area
```
6. Commit the changes
```bash
git commit -m "<add your commit message here>"
```
7. Adding remote
```bash
git add remote <name of the remote repo> <url of remote repo>
```
8. push to the remote repo
```bash
git init
```
9. pull from the remote repo
```bash
git pull --rebase <name of the remote repo> <name of branch>
```
10. 
