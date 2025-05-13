# 🚀 GitHub Commands 

### 🔍 `git status`  
Check the current state of your working directory (what’s modified, staged, etc.).

### ➕ `git add`  
Add changes to the staging area.

### 💬 `git commit -m "Your message"`  
Record your changes with a message explaining what you did.

### ⬆️ `git push`  
Send your local commits to GitHub.

### ⬇️ `git pull`  
Update your local repository (equivalent to `git fetch` + `git merge`).

### 📜 `git log`  
View the commit history of your current branch.

### 🏷️ `git tag -a v1.0 -m "Version 1.0"`  
Create a version tag for your project.

### 🌿 `git checkout -b feature/add-title`  
Create and switch to a new branch (e.g., to add a title in `index.html`).

### 📝 `git add index.html` + `git commit -m "Add title to index.html"`  
Stage and commit changes made to `index.html`.

### 🔁 `git checkout branch-name`  
Switch to an existing branch.

### 🧹 `Delete a branch` 
- Local: `git branch -d branch-name`  
- Remote: `git push origin --delete branch-name`

### 🔀 `Merge a branch into `main`
bash
git checkout main  
git merge branch-name

### 🧠 `Why use git rebase instead of git merge?`  
Rebase creates a cleaner and more linear history by placing your changes on top of the main branch.  
This avoids extra merge commits and keeps the log simpler.  
Use it when collaborating to maintain a tidy commit history.

### 🍒 `git cherry-pick commit-hash`  
Use this command to apply a specific commit from one branch into your current branch.  
Great for grabbing only the needed change without merging the full branch.

### ⏪ `git reset --hard commit-hash`  
Resets your project to a previous commit using its hash.  
⚠️ WARNING: This erases all changes made after that commit. Use with caution!

### 🧾 `Save a temporary file in stash`  
  echo "File content" > file.txt  
  git add file.txt  
  git stash push -m "Stash file.txt"

### 🔃 `How to create a Pull Request (PR) on GitHub`  
1. Go to your GitHub repository  
2. Click on "Pull Requests"  
3. Click on "New Pull Request"  
4. Select base and compare branches  
5. Review the changes and confirm

### 👥 `How to add Reviewers to your PR`  
1. While creating or editing a Pull Request  
2. Look to the right-hand sidebar  
3. Find the "Reviewers" section  
4. Click and select users to request their review
```
