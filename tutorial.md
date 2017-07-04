# Initialize

* git init
* git remote add origin <"clone">
* git status // shows tracked/untracked files
* 1. git config credential.helper 'cache --timeout 7200' // to avoid entering password repeatedly
  2. git push https://github.com/repo.git

# Branching

* git branch // shows all branches
* git checkout abc // will take you to branch abc
* git merge branch_name // will merge branchname to current branch
* git branch -d the_local_branch // deletes local branch

# Pushing Files

* git add . // untracked files added
* git commit -am '...' // tracked files modified
* git push

# Deleting Files

* git rm filename (from repo and filesystem) or git rm --cached filename (not from filesystem)
* git commit -m '...'
* git push
