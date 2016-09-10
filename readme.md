# git details

create origin 

1. git branch

# clone url
git clone url folder_name
# check remote
git remote -v
#rename remote name
git remote rename origin branchName
#add remote
git remote add upstream url
# create new branch from parent/current branch
git checkout -b unstable
#pull the branch
git pull upstream
git pull upstream branchName
# create branch from remote
git checkout -b branchName --track origin/branchName
## rebasing code
#for stashing
git stash
#move to other branch
git checkout unstable
# take latest
git pull/push
#back to previous branch
git checkout branch
#rebase with branch 
git rebase unstable
#apply previous changes
git stash apply

git merge commits
git reset --hard HEAD~2

git rebase -i Head~2

#rebase
git checkout sql_injection
git pull origin sql_injection
git checkout branch
git rebase sql_injection
