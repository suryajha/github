## First Step 1:

Git for windows - https://git-scm.com/download/win
GitHub Desktop - https://github-windows.s3.amazonaws.com/GitHubSetup.exe (https://desktop.github.com)

# Step 2:

Create Master Repository
Give access to all Memebers whow will work on this repository
  Setting->Invite Member

# Step 3:

Get Clone of the repository
 git clone <URL>
  
# Step 4

# # Commit Process


Check out a repository

Create a working copy of a local repository:

`git clone /path/to/repository`

git init

git add <filename>

git add . (For all files add)

git commit -m "Commit message"

git commit -a

git push origin master

git status

git checkout -b <branchname>

git checkout <branchname>

git branch -d <branchname>

git push origin <branchname>

git push --all origin

git push origin :<branchname>

git pull

git log

git push --tags origin

git fetch origin

---------git pull force-----------------

git fetch --all

git reset --hard origin/master

git reset --hard origin/<branch_name>

or create a new repository on the command line
echo "# elearning" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/sarveshhome/elearning.git

git push -u origin master

or push an existing repository from the command line
git remote add origin https://github.com/sarveshhome/elearning.git

git push -u origin master
