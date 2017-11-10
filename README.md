# GitCheetsheet
This project is to practise Git and Git commands

```bash
sudo apt-get install -y nodejs // To install Node JS

# Git config
cat .git/config // To view Git config to check for Remote Repo

# To set-up Git line endings & color
git config --global core.autocrlf true
git config --global core.autocrlf input


# To set-up Git color
git config --global color.ui auto

# Git config Settings

git config -l //To list all the config in our local
git config --global user.name David // To set the User name Globally
git config --global user.email d7prasad@gmail.com //To set-up E-Mail globally

# Local-system-Global Config params - The closest will applicable always.(Local - in this case has high priority)

# To initialize a repository in our local

cd /<working directory>/
git init
(or)
git init <repo name> //More Disciplined way

# Git commit
git status //will tell the changes
git add - will add all the changes to the staging area
# To commit
git commit -m "Comments for commit"

# Git Diff
git diff - To see what changed locally, but not staged yet.
git diff --staged - To see what changes between our staging area and commit head
git diff HEAD - diff with local changes with HEAD
git diff --color-words
git diff --word-diff
git diff --stat - Diff will say the difference changed locally the file name alone

'''
