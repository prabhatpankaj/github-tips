# git config

* Utility : To set your user name and email in the main configuration file.
* How to : To check your name and email type 

```
git config — global user.name
git config — global user.email
```

* And to set your new email or name

```
git config — global user.name = "Prabhat Pankaj"
git config — global user.email = "prabhatiitbhu@gmail.com"

```

# git init

* Utility : To initialise a git repository for a new or existing project.
* How to : in the root of your project directory.

```
git init
```

# git clone

* Utility : To copy a git repository from remote source, also sets the remote to original source so that you can pull again.
* How to : 

```
git clone <clone git url>

# example git clone https://github.com/prabhatpankaj/github-tips.git

```

# git status

* Utility : To check the status of files you’ve changed in your working directory, i.e, what all has changed since your last commit.
* How to : in your working directory. lists out all the files that have been changed.

```
git status
```

# git add
* Utility : adds changes to stage/index in your working directory.
* How to :

```
# to add particular file change
git add filepath/filename

# to add all changes
git add .

```
# git commit

* Utility : commits your changes and sets it to new commit object for your remote.
* How to :

```
git commit -m "any commit message for change information"
```

# git push/git pull

* Utility : Push or Pull your changes to remote. If you have added and committed your changes and you want to push them. Or if your remote has updated and you want those latest changes.
* How to : 

```
git pull <remote> <branch>
git push <remote> <branch>

# exapple 
git pull origin master
git pull origin development

```

# git branch
* Utility : Lists out all the branches.
* How to :list all the remote branches as well

```
git branch
git branch -a
```
# git checkout
* Utility : Switch to different branches
* How to : 

```
# if you want to switch to a new branch.
git checkout <branch>

# if you want to create and switch to a new branch.
git checkout -b <branch> 

```

# git stash
* Utility : Save changes that you don’t want to commit immediately.
* How to :

```
git stash
#if you want to bring your saved changes back.
git stash apply 
```

# git merge
* Utility : Merge two branches you were working on.
* How to : Switch to branch you want to merge everything in.

```
git merge <branch_you_want_to_merge>

```

# git reset
* Utility : You know when you commit changes that are not complete, this sets your index to the latest commit that you want to work on with.
* How to:

```
git reset <mode> <COMMIT>

# example
# to last commit
git reset --hard

# to speciffice commit ( commit id)
git reset --hard c90f8b2ce61ce41dcc56dfd985271c8fcf1157ea

```
# git remote
* Utility : To check what remote/source you have or add a new remote.
* How to : git remote to check and list.

```
git remote add <remote_name> <remote_url>

# example
git remore add origin https://github.com/prabhatpankaj/github-tips.git
```
