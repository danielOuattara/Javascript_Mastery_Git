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
```

## stopped @ 18:27
