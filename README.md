🔝 Your original commands (unchanged):
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/itssiphan/layout_dynamicRoutes_and_404anderrorpage.git
git push -u origin main

👇 Git Commands (comment first → commands below it)
Basic Git Commands
❗ Check file status
git status

❗ View commit history
git log

❗ Clone a project
git clone <url>

Add & Commit
❗ Add all files to staging
git add .

❗ Add a single file
git add filename

❗ Commit changes
git commit -m "message"

❗ Add + commit tracked files together
git commit -am "message"

Remote Commands
❗ Show connected remotes
git remote -v

❗ Remove a remote
git remote remove origin

❗ Add a new remote
git remote add origin <url>

❗ First-time push of a branch
git push -u origin main

❗ Push new updates
git push

Branch Commands
❗ List branches
git branch

❗ Create a new branch
git branch new-branch

❗ Switch to a branch
git checkout new-branch

❗ Create + switch
git checkout -b new-branch

❗ Merge a branch into current
git merge new-branch

❗ Delete a branch
git branch -d new-branch

Pull & Fetch
❗ Pull latest updates
git pull origin main

❗ Fetch updates without merging
git fetch

Undo / Restore / Reset
❗ Restore a specific file
git restore filename

❗ Restore all files
git restore .

❗ Undo last commit but keep changes
git reset --soft HEAD~1

❗ Undo last commit + delete changes
git reset --hard HEAD~1

❗ Old way to discard file changes
git checkout -- filename

Stash Commands
❗ Temporarily save your work
git stash

❗ Apply stashed work
git stash pop

❗ List all stashes
git stash list

Push New Branch
❗ Push a new branch to GitHub
git push -u origin branchname
