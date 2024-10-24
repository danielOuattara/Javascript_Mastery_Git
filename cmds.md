# Commands

```bash
git config --list
git config --global --list
git config --local --list

mkdir mastery-git
cd mastery-git

touch cmd.txt

touch hello.js
echo echo console.log\("Hello, Git!"\)>> hello.js

touch readme.md

git add readme.md
git commit -m "Add read.me file"

git status

git add . # to add all modifications in staging area

git commit -m "add cmd.txt, hello.js and test.js files"

git log  # to see the logs details


git checkout b5203da4808 # checkout to another previous commit; no modifications are made


git checkout main  # go back to normal position HEAD state

# create a remote repo on github

# https://github.com/danielOuattara/Javascript_Mastery_Git.git

# now link the remote repo (origin) 
git remote add origin git@github.com:danielOuattara/Javascript_Mastery_Git.git

# branching & merging

# - Projects branches: `main`, `develop`, `bug-fix`, `feature`

# branch `main` is the default in git

git branch branch-name` : # create a new branch named branch-name
git checkout branch-name` : # to switch to the newly created branch
git checkout main` : # to switch back to the main branch

# shortcut
git checkout -b branch-name` : # to create & switch to the newly created branch

# Note: 
# 1. when creating a new branch, it will be based on the current branch you are on now
# 2. the created branch inherits all the code from the base branch

git branch branch-two branch-one # will create branch-two based on branch-one
```
