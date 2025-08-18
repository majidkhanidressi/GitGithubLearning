# GitGithubLearning

Started learning git/github

git init command create new repostiry on local machine

git add .  commit add the changes in local repo to staging area

git commit -m "test message"  commit the changes from staginging to local 
git repositry that it'll start to track the changes

git remote add origin "remote repo url"  it'll add the remote repostiroy 

git remote set-url origin "remote repo url" it'll update the remote repo url

.gitignore file understanding

git restore command used to restore the changes before commit

git restore --staged used to restore staged files

git revert command used to revert the changes after commit the changes. It keeps the histoy
of committs.

git log --online 

git reset --soft Head~1 undo the last commit and also stage the all the changes of last commit.

git reset --mixed Head~1 Undo the last commit and also unstage all the changes of last commit.

git reset --hard Head~1   Undo the last commit and also removed all the changes of last commit from working dir. 

Create local & global alias, Open the .gitconfig file in user home directory using vi/nano editor and 
add alias for any command like [alias] st = status, here we created alias for git status command
Can also create it using git config --global alias.b branch

For creating alias for current repo use it without --global git config alias.b branch

Branch used to work in teams

Git branch shows current branches

We can create branches in 3 different ways
Git branch second created the new branch with “second” name
To switch branch git checkout second 
Git switch main switch to main branch 

Git checkout -b third used create branch and checkout the repo
Git switch -c fourth create fourth branch and also switch it.

To delete a branch use git branch -D second remove the second branch
To merge a branch use git merge third it’ll merge third branch in main

Amend in git use the amend the last commit

git commit --amend -m "sdasf" will amend the last commit message.

git clone command used to download the copy of remote repository.

git clone remote repository url. it'll clone the main branch

git clone --branch first remote repository url it'll clone the specific branch

git fetch // fetch the changes from remote repository but did not mege it with current changes
usually we used it check the current changes then merge it. 

git pull // pull the changes from remote repositoyr and merge it with current changes.





