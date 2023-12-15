## Git practice
## U means untracked file
## to track we need to git add filename

## right now no branch added

## all the files added but not committed are inside a staging environment where they are waiting to get pushed into our repository altogether.

## git commit -m "First commit"

## here the flow through which it should work just fine

## 1. First authenticate and connect to your github account by executing git config --global user.email "your email here" 
## 2. Also provide your username by executing git config --global user.name "your username here"
## NOTE: the above steps are first time steps to execute after installing fresh git
## 3. Go to the project directory and initialise a local repo by executing 'git init'
## 4. All the required files are added into the local respository by executing git add filename.ext
## 5. Folders can also be added by executing git add folder_path
## 6. We can check status by executing git status
## 7. We can also check for branches by executing git branch
## 8. Commit the added files into local repository's staging environment using git commit -m "commit message here"
## 9. Change the branch to main by git branch -M main
##    this is optional as we can work in master branch, which is the default branch too 
## 10. Connect your github repository to this local staging environment by executing git remote add origin github-repo-url
## 11. Finally push the files on staging env to github repository by executing git push origin main

## 12. To pull from repository, make sure you are in same local repo and execute git pull origin main and all the new changes will be reflected in local environment as well.

## THIS SUMS UP 