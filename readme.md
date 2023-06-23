git init example

cd example

touch README.md

git status

git add README.md

git status

git commit -m 'add README.md'

git status

-- go to github and create a repo with name 'example' and copy the url

-- url name is: https://github.com/pranabsg/example.git

git remote add origin https://github.com/pranabsg/example.git

git branch -M main

git push -u origin main

# Branching

git branch branch-1

git branch branch-1

git branch

git status

# Move the branch to branch-1

git checkout branch-1

# Operations in branch-1

git add branch-1.txt

git commit -m "added branch-1.txt"

git push origin branch-1

# Merge

git checkout main

git merge branch-1