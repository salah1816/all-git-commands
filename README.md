# All git commands
## ..show the current status
* git status
## ..create a new repository on the command line
* echo "a new message" >> README.md
* git init
## remove git
* rm -rf .git
## add git
* git add README.md
* git reset. 
* git commit -m "first commit"
* git branch -M main
* git remote add origin git@github.com:user/repo.git
* git push -u origin main
## ..push an existing repository from the command line
* git remote add origin git@github.com:user/repo.git
* git branch -M main
* git push -u origin main
## ..clone an repository
* git clone git@github.com:user/repo.git 

## .. remove origin repository
* git remote remove origin

## ..show all commits
* git log

## ..merge a branch
* git checkout master
* git pull origin master
* git merge branch_name
* git push origin master

 ## ..delete branch
 // delete branch locally
* git branch -d localBranchName

// delete local branch that is unmerged
* git branch -D localBranchName

// delete branch remotely
* git push origin --delete remoteBranchName
