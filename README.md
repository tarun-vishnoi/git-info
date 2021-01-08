# git-info

Git commands : 
 
 git init ==>> To make a repo

 git status ==>> To check repo status

 git add filename / git add . ==>> add to stage area

 git commit -m "commit message" ==>> commit into local repo

 git log ==>> will print all commit logs 

 git log --oneline ==>> will print one line logs of all commits

 git diff commitId commitId ==>> will print differences between commit IDs

 git checkout filename ==> When we want to replace our modified file(corrupted) with the latest repo file before stage(add) or commit.

 git reset HEAD filename ==>> When we want to replace our modified file(corrupted) with the latest repo file after the stage(git add filename / git add .). It will only unstage the changes.

 git checkout filename ==>> But to get latest on local we have to hit this command as well.

 git branch ==>> list all available branches (highlighted current working branch)

 git branch dev ==>> TO craete a new branch

 git checkout branchName ==>> to switch between branches

 git merge dev ==>> merge dev branch code into current branch

 git branch -d branchName ==>> to delete a branch

 git remote add origin https://github.com/tarun-vishnoi/git-info.git ==>> to create a remote git repo 

 git remote -v ==>> Shows all available remote repo

 git push -u origin branchName ==>> to push the branch to repo

 git pull ==>> to pull the changes from the upstream to local before pushing the code to remote

 git push -u origin master ==>> ot push the changes to remote repo

 git fetch ==>> It only shows the changes. It will not pull the changes directly.

 git reset --hard commitId ==>> hard reset to any previous commit version {latest commits will be gone.}

 git push -f ==>> force upadate to the remote repo

 git revert head ==> It won't remove the ealier commit histoy. It will only undo them.

 git push ==>> After revert we don't need to force update the remote repo

 git stash ==>> When you have worked locally but not ready to commit yet  but you want to work on something else so you will stash it, complete 
 your work and then start it again from stash using git stash pop

 git stash pop ==>> see above
