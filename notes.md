# General Commands
## pull from remote
- How to pull from remote in such a way that all the remote branches are pulled,
- there is a local branch tracking for each of the remote branches,
- the local branch has the same name as the remote branch

## push to remote
`git push -u --all` will push the current branch and all the others to remote and set up the local tracking branch names same as the remote.

## rebase
https://robots.thoughtbot.com/git-interactive-rebase-squash-amend-rewriting-history

`git rebase -i HEAD~14`
* leave the first commit as it is (i.e. keep the oldest commit as it is) or reword it
* squash all the other commits
* if the commits were already pushed to remote, use `git push -u --all --force`

# Windows Setup
