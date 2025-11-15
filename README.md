# Initialize git repo

git init


# Add all files to staging

git add .


# Commit your first changes

git commit -m "first commit"


# Rename current branch to main

git branch -M main


# Add GitHub remote

git remote add origin https://github.com/itssiphan/layout_dynamicRoutes_and_404anderrorpage.git


# First time push to GitHub

git push -u origin main



# ---------- BASIC COMMANDS ----------

# Check which files are modified / staged

git status


# View commit history

git log


# Clone a project from GitHub

git clone <url>



# ---------- ADD & COMMIT ----------

# Add a single file

git add filename


# Commit changes

git commit -m "message"


# Add + commit tracked files together

git commit -am "message"



# ---------- REMOTE COMMANDS ----------

# Show current remotes

git remote -v


# Remove remote

git remote remove origin


# Add new remote

git remote add origin <url>


# Push updates

git push



# ---------- BRANCH COMMANDS ----------

# List branches

git branch


# Create new branch

git branch new-branch


# Switch to a branch

git checkout new-branch


# Create + switch to a branch

git checkout -b new-branch


# Merge a branch into current

git merge new-branch


# Delete a branch

git branch -d new-branch



# ---------- PULL / FETCH ----------

# Pull latest updates

git pull origin main


# Fetch updates without merge

git fetch



# ---------- UNDO / RESET ----------

# Restore a specific file

git restore filename


# Restore all files

git restore .


# Undo last commit but keep changes

git reset --soft HEAD~1


# Undo last commit + remove changes

git reset --hard HEAD~1


# Old method to discard file changes

git checkout -- filename



# ---------- STASH ----------

# Temporarily save uncommitted changes

git stash


# Apply stashed work

git stash pop


# Show stash list

git stash list



# ---------- PUSH NEW BRANCH ----------

# Push new branch to GitHub

git push -u origin branchname
