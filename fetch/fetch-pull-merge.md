**$ git pull [remote]**

Fetch changes from the remote and merge current branch with its upstream.

` git fetch --all --prune `

`git push hard upstream/main`

git fetch
On its own, git fetch updates all the remote tracking branches in local repository. No changes are actually reflected on any of the local working branches.

git merge
Without any arguments, git merge will merge the corresponding remote tracking branch to the local working branch.

git pull
git fetch updates remote tracking branches. git merge updates the current branch with the corresponding remote tracking branch. Using git pull,
you get both parts of these updates. But, this means that if you are checked out to feature branch and you execute git pull, when you checkout to master, 
any new updates will not be included. Whenever you checkout to another branch that may have new changes, it’s always a good idea to execute git pull.

`  git pull upstream main  `

