git init example

cd example

touch README.md

git status

git add README.md

git status

git commit -m 'add README.md'

git status

# go to github and create a repo with name 'example' and copy the url
# url name is: https://github.com/pranabsg/example.git

git remote add origin https://github.com/pranabsg/example.git

git branch -M main

git push -u origin main