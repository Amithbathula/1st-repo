Hi 

Myself Amithbathula, and I am learning GitHub as a part of DevOps



To set your account identity  --> git config --global user.email  "youremail@gamil.com"

     					          git config --global user.name "yourname@gmail.com"



**IACP**

Working directory - > git init - Red colour(untracked file)

staged area            -> git add . - green colour  - Tracked file (Staged area)

local repo              -> git commit -> stores in local repo

remote repo           -> git push - > stores in github


Optional(.git)
1.COMMIT_EDITMSG
2.HEAD
3.config
4.description
5.hooks
6.index
7.info
8.logs
9.objects
10.refs


imp - If the working tree and staging area and local repo has the same data then only in git status it will show clean 
imp - if you need to see on which branch you are then use -> git branch (but only shows if you have atleast one commit in that working directory)

				Command
To see our name -> git config user.name
To see our email -> git config user.email
To check our commit history -> git log
To see the trimmed history -> git log --online 
To see the trimmed history with a limit -> git log --oneline -* (* = number)
To check the one last commit -> git show
To check the complete info of one particular commit - > git show * (* = commit number and get by git log)
To see the status -> git status
To see the complete summary of the changes -> git log -- stat
To check the difference between two commits -> git log -p -2 (in place of two you can specify number, checks from head to master) 
To see the changes in one particular file in staged phase-> git diff --staged * (* = file name)

To see the changes in one particular file in working directory not staged/untracked -> git diff  * (* = file name)
To see the changes in one particular file in working directory not staged/untracked -> git diff -- *(* = file name)

To check the difference between two commits -> git log -p -2 (in place of two you can specify number, checks from head to master) 
To check commit messages only -> git shortlog 
To see which person changed which line -> git blame * (* = file name)
To see the changes from one commit to another commit(master -> head) - > git diff -- *..* (1st * = commit id..2nd * = commit id)
To check the changes from working tree to staging area -> git diff 
To check the changes from staged area to local repo -> git diff --staged
To check the changes from working area to local repo -> git diff --HEAD
To see all the commits made by one particular person -> git log --online --author=*(*=name of that person)
To move all the untracked files to tracked files -> git add .
To move all the tracked files to local repo -> git commit -m "some msg here" .
To edit the last commit message -> git commit --amend -m "enter the message here"

