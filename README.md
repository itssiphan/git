🔝 Commands you provided (unchanged, stay on top):
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/itssiphan/layout_dynamicRoutes_and_404anderrorpage.git
git push -u origin main

👇 All Git Commands in English with step-by-step comments
📌 Basic Git Commands
git status          # Shows which files are modified or staged
git log             # Shows commit history
git clone <url>     # Downloads a project from GitHub to your system

📌 Adding & Committing Files
git add .                  # Add all files to staging area
git add filename           # Add only one specific file
git commit -m "message"    # Commit your staged changes
git commit -am "message"   # Add + commit tracked files together

📌 Remote Commands
git remote -v                     # Show current connected remotes
git remote remove origin          # Remove the existing remote
git remote add origin <url>       # Add a new remote
git push -u origin main           # Push your branch for the first time
git push                          # Push new updates

📌 Branch Commands
git branch                   # List all branches
git branch new-branch        # Create a new branch
git checkout new-branch      # Switch to a branch
git checkout -b new-branch   # Create + switch to a new branch
git merge new-branch         # Merge a branch into the current one
git branch -d new-branch     # Delete a branch

📌 Pull & Fetch
git pull origin main     # Pull latest code from GitHub + auto merge
git fetch                # Fetch changes without merging

📌 Undo / Fix / Reset Commands
git restore filename                # Restore file to last committed state
git restore .                       # Restore all files
git reset --soft HEAD~1             # Undo last commit but keep changes
git reset --hard HEAD~1             # Undo last commit AND remove changes
git checkout -- filename            # Old way: discard changes to a file

📌 Stash (temporary save your work)
git stash            # Temporarily save your current changes
git stash pop        # Apply stashed changes back
git stash list       # See all stashes

📌 Push a New Branch to GitHub
git push -u origin branchname     # Upload a new branch to GitHub
