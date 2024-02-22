#create git repo 
git init

do not touch .gitrepo folder

# changed the name of the branch
git branch -M main

#To show branch name

#dir lists directory in powershell

# add file to git 
git add .\file.md

#commits the code
git commit
# commits the changes to local git repo
git commit -m "added file.md"

# make sure to add your username and email if asked
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
~/.gitconfig

# to see if everything was successfull
git staus

git log
#go back a commit
git checkout 173593c75b1a
#will point the head to the main branch again
git checkout main 



cd ~
start.


# make sure that the default branch for any repo is main instead of master
git config --global unit.defaultbranch main

git add .
get status
git commit -m "my next commit"
git log

# git graph extenstion
ctl shift p type

# create and switch to new branch
git checkout -b branch1
git branch (see two branches)
git add .
git status
git commit -m "added to new branch"

# one more change to show new branch path
#to switch branches
git checkout branchname (main)

# merge branches to main
ensure we are on the main branch
git merge branchname that we want to merge on to main
(git merge branch1)

# Go to gtthub create new repo - public -uncheck read me- follow steps
# follow the link the cl gives you to your new repo

# to copy from remote repo
<>code copy link
git clone paste url

#making a chnage so I can push, fail show login with tokens
making change to see if I have to log back in
to avoid usernames being asked all the time
#caching credentials in file.md
git config --global credential.helper store

git add .
git commit -m "make changes"
git push

on terminal
git status
git push
username: 
password:

in github-settings  under profile - dev settings- tokens clasic - check all boxes- experiation- gnerate token