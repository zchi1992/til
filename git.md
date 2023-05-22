# Git and Github

## Git global configurations 
`git config --global user.name [username]`
`git config --global user.email [email]`  

A preferred way is to open git config file as below. 
`git config --global --edit`

## Git config for a single repository
Change the current working directory to the local repository where you want to configure the name that is associated with your Git commits. run. 
`git config --edit`

## Basic commands to review
`git init`: initilize a new git working direction  
`git add .` or `git add [file1] [file2] ...`: add all files to the staging area or git index  
`git commit [message]`: commit all files that permanently store content of the index into the repository  
`git status`: show status of staging  
`git diff --cached`  
`git push origin`: push local branches to remote repository (origin)

## config git proxy
Add below socks depending on VPN setup  
`
[http]
	proxy = socks5://127.0.0.1:1086
[https]
	proxy = socks5://127.0.0.1:1086
`

## GitHub credential management
install GitHub CLI based on (Installation)[https://github.com/cli/cli#installation]  
follow (this page)[https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git] to set up credentials. Save token in a `mytoken.txt` file  
`gh auth login --with-token < mytoken.txt`
