# test_github

## first commit

echo "# test_github" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/umnarjchittong/test_github.git

git push -u origin main


## second commit, third commit

git add README.md

git commit -m "second commit"

git push


## new branch

git add README.md

git commit -m "new branch commit"

git checkout -b branch_2

git remote add branch2 https://github.com/umnarjchittong/test_github.git

git push origin branch_2

## pull

