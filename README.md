# GitGithubLearning

Started learning git/github. Below is the list of commands learned with some details

## 1) Git Config
git config is the command used to configure Git settings.

These settings can apply locally (just one repo), globally (all repos for your user), or system-wide (all users on a machine).

For using this command we don't need any git repository. 
Please rememober there are two types of git command
- Commands which required git repository
- Commands which do not required git repository

#### System (--system)
- Applies to all users on the machine.
- Stored in: /etc/gitconfig
- git config --system user.name "John Doe"

#### Global (--global)
- Applies to your user account.
- Stored in: ~/.gitconfig (Linux/Mac) or C:\Users\<User>\.gitconfig (Windows).
- git config --global user.name "John Doe"
- git config --global user.email "john@example.com"
- git config --global user.name // shows current user name
- git config --global user.email // shows current user email

#### Local (default, no flag)
- Applies only to the current repo.
- Stored in: .git/config inside that repo.
- git config user.name "John Repo"
- git config user.email "repo@example.com"

## 2) Git init
- git init command create new repostiry on local machine

git add .  commit add the changes in local repo to staging area

git add --all

git add file1 file 2

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

git diff // used to check the difference between two commits, different between local repo & remote repo.





