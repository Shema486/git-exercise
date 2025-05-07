# Git-exercises project

this project will be used for a series of git exercise

## Bundle 1 ------------- exercise 1

```bash
git init: to initialize.
git status : to checkout commits.
git branch -m: changing branches.
git commit -m: committing and stage
git checkout -b dev: creating new branch name
git checkout branch name : back to exist branch
git remote add origin link
git push
git push --set-upstream origin main OR git push origin main
git branch -d test : delete
git push origin --delete test: deleting branch from github
```

## Bundle 1 ------------- exercise 2

```bash
here we are going to create home.html and some change before commit.....

.git stash : takes your uncommitted changes (both staged and unstaged), saves them away for later use, and then reverts them from your working copy

.git stash list : to list all stashed filed
.git stash pop (then index) : to bring back stashed file
.git reset --hard :takes a way latest changes
```

## Bundle 2 ---------------exercises 1

```bash
A pull request is a proposal to merge a set of changes from one branch into another. In a pull request, collaborators can review and discuss the proposed set of changes before they integrate the changes into the main codebase.

git pull origin dev : to bring files from dev to main when i was in the main branch like =======
git merge dev.
```

## Bundle 2 ---------------exercises 2

```bash
git merge branch name : it combines to branches with new commit like it create new commit from one branch to another

Use git merge when you want to maintain a clear record of when branches were created and merged, and when working collaboratively on a branch that has been shared with others.
```

## Bundle 3 ---------------exercises 1

```bash
git log : it gives all commite and their hash index like unique indentifier

git cherry-pich + hash index of commit of another branch: it give a copy of files/changes from one branch to another

You use Git cherry-pick to selectively apply individual commits from one branch to another. This is useful when you need to backport a specific fix or feature from a newer branch to an older one, or to isolate a particular change for testing.

git revert + hash index of commit of another branch : it remove out the file/changes
```

## Bundle 3 ---------------exercises 2

```bash
git rebase branch name: it combines two branches without new commit it copies directly

Use git rebase when you want a cleaner, more linear history, and when working on a feature branch that hasn't been shared. Avoid rebasing public branches to prevent issues for collaborators.

```

## Bundle 4 ---------------exercises 1

```bash
git remote : it always has origin as default but can create new one
git remote add git-copy:as new remote
git remote rm : removing remote
git remote add <name> <url>
git remote lists all your defined remotes, and git remote -v shows their associated URLs.

You use git push <remote-name> <branch> to push your local changes to the remote repository, and git pull <remote-name> <branch> to fetch and integrate changes from the remote
```

## Bundle 4 ---------------exercises 2

```bash
git merge squash : it brings copy of commit but staged

git merge --squash in Git means combining all the changes from a branch into a single commit when merging it into another branch. Instead of creating a merge commit that preserves the history of both branches, a squash merge creates a new commit containing all the changes from the merged branch, effectively rewriting the history
```

# Bundle 5 -------------- Exercises

```bash
cd .. is a command used to navigate up one directory level in the file system. It's short for "change directory to the parent directory".

clone url link
```
