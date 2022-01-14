touch index.html

git init

git config --global user.name 'haitn'

git config --global user.email 'haitnhe61@gmail.com'

git add index.html

git status 

git rm --cached index.html -> unstage index file

git add *.html -> add any html file

git add . -> add everything

if change content of index.html

git status -> 

git checkout --<file> to discard changes in working directory (error)

git commit

git status -> nothing to commit, working tree plan

git commit -m "add app.js" -> skip editing

clear

touch .gitignore

mkdir dir1 dir2

inside gitignore 
-> log.txt
-> /dir2
-> *.txt

git add .
git status -> only have gitignore and dir2