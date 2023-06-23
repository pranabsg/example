`git init example`

`cd example`

`touch README.md`

`git status`

`git add README.md`

`git status`

`git commit -m 'add README.md'`

`git status`

go to github and create a repo with name 'example' and copy the url

url name is: https://github.com/pranabsg/example.git

`git remote add origin https://github.com/pranabsg/example.git`

`git branch -M main`

`git push -u origin main`

# Branching

`git branch branch-1`

`git branch`

`git status`

# Move the branch to branch-1

`git checkout branch-1`

# Operations in branch-1

`git add branch-1.txt`

`git commit -m "added branch-1.txt"`

`git push origin branch-1`

# Merge

`git checkout main`

`git merge branch-1`

# Clone

`git clone https://github.com/pranabsg/example.git [<renamed_name>]`

# Remote

from cloned repo, use:

`git remote -v`

# If want to set cloned repo to make own repo in order to make modification

`git remote set-url origin`

## Then run below command, this should show as own repo

`git remote -v`

## Then push to own repo in Github

`git remote add origin https://github.com/pranabsg/example.git`

`git push -u origin main`

# Fork

Fork can be done on someone else's repo and then it shows as own's repor

then clone it in local

## Clone vs Form

Clone when no need to keep track of origin, only wanted to play with the code.

Fork is when want to keep track of origin and for collaborative work.

# Log

`git log`

`git log --pretty=short`

`git log --pretty=full`

`git log --pretty=fuller`

`git log --since=1.month`

`git log --since="yyyy-mm-dd"`