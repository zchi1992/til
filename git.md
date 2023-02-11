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
`git commit`: commit all files that permanently store content of the index into the repository  