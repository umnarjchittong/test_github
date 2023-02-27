# test_github

## first commit

**echo "# test_github" >> README.md**

**git init**

**git add README.md**

**git commit -m "first commit"**

**git branch -M main**

**git remote add origin https://github.com/umnarjchittong/test_github.git**

**git push -u origin main**


## second commit, third commit

**git add README.md**

**git commit -m "second commit"**

**git push**


## new branch

**git checkout -b branch_2**

**git remote add branch2 https://github.com/umnarjchittong/test_github.git**

**git push origin branch_2**

## pull

## Merge Branchs
###Merging via command line


Step 1: Clone the repository or update your local repository with the latest changes.

**git pull origin main**

Step 2: Switch to the base branch of the pull request.

**git checkout main**

Step 3: Merge the head branch into the base branch.

**git merge branch_2**

Step 4: Push the changes.

**git push -u origin main**

