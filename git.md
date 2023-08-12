[https://github.com/joshnh/Git-Commands]
# make directory a git repository
$ git init
# To add all files not staged:
$ git add .
# To stage a specific file:
$ git add index.html
# Adding a commit with message
$ git commit -m "Commit message in quotes"
# Message when all files have been staged and committed 
$ git status
# Running git config globally
$ git config --global user.email "name@name.com"
$ git config --global user.name "name"
# List all remote or local branches
$ git branch -a
# Delete a branch
$ git branch -d <branch_name>
# Checkout an existing branch
$ git checkout <branch_name>
# Merge changes into current branch
$ git merge <branch_name>
# Add remote repository
$ git remote <command> <remote_name> <remote_URL>
# List named remote repositories
$ git remote -v

$ git clone <remote_URL>
# Pull from named remote
$ git pull origin staging
# Push all local branches to remote repository
$ git push —all
# Show entire git log
$ git log
#Viewing branches:
git branch or git branch --list
#should update your local dev branch
git fetch
#Remove a file (or folder)
git rm -r [file-name.txt]	
#Get global config
git config --global --list