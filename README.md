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

Create local & global alias, Open the .gitconfig file in user home directory using vi/nano editor and add alias 
for any command like [alias] st = status, here we created alias for git status command

