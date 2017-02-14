# How to use Cherry-Pick on Git

Practice repo to learn how to use Cherry-Pick in Git

## Problem

You checked out `issue-1` branch to check out the work in progress feature.

Later you pushed a commit on `issue-2` and realized that you created a branch off of `issue-1` instead of `master` branch.

You definitely don't want to 're-do' the work or patch around changes from copied files.

## Challenge

Use Cherry-pick feature in the Git so that `issue-2` branch and it's commit directly on top of `master` branch.

Do not bring in any changes made in `issue-1` and you will clearly see if you violate this rule.

Make sure to *Fork* this repo so you can write to the origin

## Example Algorithm

* *Checkout* `master` branch
* Create and checkout a local branch called `temp`
* *Cherry-Pick* a commit on `origin/issue-2`
* Rename `temp` branch to `issue-2` (delete old local branch if exists)
* Force push `issue-2` to the origin

## Resources

* https://git-scm.com/docs/git-cherry-pick