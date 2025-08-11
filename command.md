My commands content goes here

# Git commands and Uses

## Set username
``` git config  --global user.name "username"```  
## Set email
```git config --global user.email "email"```  

## check configurations
``` git config```

## Alias your commands name
``` git config --global alias.i init ```
## create a new folder
``` mkdir name```
## create a file  
``` touch name.md ```
##  checking your changes 
``` git status```
##  Start tacking files in staging area
```git add <file-name> OR  git add . all files```

### What is Remote ?
ANS :  
* your local repo is on your machine.
* A remote is another copy of the repo, typically hosted on Github or another server.
* git uses short names (like origin) instead of typing the full URL every time.

## Common git remote commands
``` git remote -v  List all remotes with their fetch/push URLs

git remote add <name><url> Add a new remote connection

git remote remove <name> Remove a remote

git remote rename <old><new> Rename a remote 

git remote set-url <name><new-url> Change the URL of a remote
```
