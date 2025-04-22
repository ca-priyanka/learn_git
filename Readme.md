# How to set up a new working env in python.

### step 1 : Set up virtual env in current directory
python3 -m venv .venv

### step 2: Activate
source .venv/bin/activate

# Git and Github
### Start using Git
install git to your local computer, make a github account via web browser, register your SSH key.

# How to add a new Git Repository - linux
create a new repository in GitHub

### 1. Create a new directory on laptop for your project:
mkdir <project name> to create the project directory

### 2. Initialize the Git repository:
Navigate to the newly created project directory using cd <project_name>.
git init to initialize a Git repository. This creates a hidden .git directory within your project folder. 

### 3. Add files to the staging area:
git add . to add all files or git add <file name>

### 4. Commit the changes
git commit -m "Initial commit"

### 5 . Push to remote repository:
git remote add origin <remote_repo_url>, then
git push -u origin main

# Everyday jobs:
git status
git add
git commit -m " "
git push

# History
git log
git diff

# To pull someones latest work:
git pull





