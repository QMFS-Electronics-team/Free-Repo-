# Git guide

## Checking your git bash current configured email and username

-You need to change you global email address:

git config --global user.email [your email address here]

-To change you global user.username


## If your repository is empty, follow these steps:

Steps taken by penguin-bot

Check your previous username and email address by entering the following
git config user.name
git config user.email
Ensure this is correct for your github account 
follow these commands:
Git init
git remote add origin https://github.com/QMFS-Electronics-team/Free-Repo-.git
git add -A
git commit -m "Commit made by [yourname]"
git push -u origin master


## Updating and pushing commit

Later steps to update and push a commit
type:

git status
git pull
git add -A
git commit -m "[Commit message]"
git push