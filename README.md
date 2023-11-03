# GitHub Commands
This repository provides an overview of essential Git commands for interacting with GitHub repositories.

## Clone repository
To clone a repository, use the following commands:
````
git clone https://github.com/...
````

## Commit and Push
To make a commit, use the following commands:
````
git add .
git commit -m "Name Commit"
git push -u origin main
````

## Upload local proyect to GitHub
To upload a local project to GitHub, follow these steps:
````
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/...
git push -u origin main
````


# Handling "Error fetch first"
Encountering the error message "error: failed to push some refs" can be resolved by executing these commands:
```
git pull
git branch --set-upstream-to=origin/main main
git pull --allow-unrelated-histories
git push -u origin main
```
