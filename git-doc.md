# Link a new project to Github repository

- Create new repo
- Create new folder
- Open folder in Vs Code
- Create a file

1. git init
2. git add .
3. git commit -m "first init"
4. git remote add origin https://github.com/ibnuhazar101/tes-new-repo.git <!-- use your own repo link instead -->
5. git push --set-upstream origin master

# Push changes to master

1. git add file-name or git add . (adding all files) <!-- adding which files to commit -->
2. git commit -m "commit name" <!-- store to our local git repository, ready to push -->
3. git push <!-- push commits to remote github repository branch. git will remember all the commits (like nodes in a string), so we can revert back to previous nodes -->

# Clone an existing repository to our local folder

- Create new folder
- open folder in cmd
- git clone https://github.com/ibnuhazar101/tes-new-repo.git <!-- use your own repo link instead -->

# Create a new branch

- git branch branch-name <!-- branch name cannot have spaces -->

# Switch to a branch

- git checkout branch-name

# Create a new branch and immediately switch to that branch

- git checkout -b branch-name

# Push changes to a new branch

1. git add .
2. git commit -m "commit name"
3. git push --set-upstream origin branch-name <!-- the next push we only need to type 'git push' -->

# Merge our branch into master

1. git checkout master
2. git merge branch-name
