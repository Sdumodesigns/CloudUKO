# Git Commit Guide

Follow these steps to save and upload your changes to GitHub.

### 1. Stage Changes
Prepare your modified files for a commit.
```powershell
git add .
```

### 2. Commit Changes
Save a snapshot of your work with a descriptive message.
```powershell
git commit -m "Your description of changes"
```

### 3. Push to GitHub
Upload your commit to the online repository.
```powershell
git push origin main
```

---

### Tips
- Use `git status` to check which files are modified. if commited it sould say nothing to commit, working tree clean
- If you get an error during push, run `git pull origin main` first to get any updates from GitHub.
