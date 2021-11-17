# Link a new project to Github repository

- Create new repo
- Create new folder
- Open folder in Vs Code
- Create a file

1. git init
2. git add .
3. git commit -m "first init"
4. git remote add origin https://github.com/ibnuhazar101/tes-new-repo.git // use your own repo link instead
5. git push --set-upstream origin master

# Push changes to master

1. git add file-name // or git add . (add all file)
2. fit commit -m "commit name"
3. git push

# Create a new branch

- git branch branch-name // branch name cannot have spaces

# Switch to a branch

- git checkout branch-name

# Create a new branch and immediately switch to that branch

- git checkout -b branch-name

# Push changes to a new branch

1. git add .
2. git commit -m "commit name"
3. git push --set-upstream origin branch-name // the next push we only need to type 'git push'

# Merge our branch into master

1. git checkout master
2. git merge branch-name
