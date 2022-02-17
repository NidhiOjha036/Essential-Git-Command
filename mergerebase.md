# Megre vs Rebase
* The first thing to understand about git rebase is that it solves the same problem as git merge.
* Both of commands are designed to integrate changes from one branch into another branch --- the just do it in very different ways.
# The Merge Option
* the easiest option is to merge the master branch into the feature branch.

 `$git checkout feature`
 
 `$git merge master`
 
 Or, you can condese this to a one-liner
 
 `$git merge feature master`
 
 As an alternative to merging, you can rebase the feature branch onto master branch.
 
 `$git checkout feature`
 
 `$git rebase master`
 
 
 # key Points
 + git merge apply all commits from branch A into branch B in one commit with final result.
 + git merge doesn't rewrite commit history, just adds one new commit.
 + git rebase gets all commits from both branch and applies them one by one.
 + git rebase rewrites commit history but doesn't create extra commit for merging.
