



### Description  Some commands we learned it :
# Git and GitHub: Step-by-Step Guide

## 🔗 Part 1: Connecting a Local Repository to a Remote Repository on GitHub

### ✅ Step 1: Initialize or Navigate to Your Local Git Repository
```bash
git init
```

### ✅ Step 2: Rename the Default Branch (Optional but Recommended)
```bash
git branch -m main
```

### ✅ Step 3: Create a Repository on GitHub
- Go to [GitHub](https://github.com) and create a new repository.
- Copy the HTTPS or SSH URL of the remote repository.

### ✅ Step 4: Link Your Local Repository with the Remote
```bash
git remote add origin <REMOTE_REPO_URL>
```

### ✅ Step 5: Fetch, Pull, and Merge (if needed)
```bash
git fetch
git status
git pull origin main
git merge
```

### ✅ Step 6: Push Your Local Code to GitHub
```bash
git push -u origin main
```

---

## 📦 Part 2: Cloning and Collaborating with a Remote Repository

### ✅ Step 1: Clone the Remote Repository
```bash
git clone <REMOTE_REPO_URL>
```

### ✅ Step 2: Create and Switch to a New Branch (Optional)
```bash
git checkout  feature-branch
```

### ✅ Step 3: Make Changes and Commit Them
```bash
git add .
git commit -m "Describe your changes"
```

### ✅ Step 4: Push Changes to the Remote Repository
```bash
git push origin feature-branch
```

### ✅ Step 5: Sync with Remote Changes
```bash
git pull origin main
```

### ✅ Step 6: Merge Changes (if required)
```bash
git checkout main
git merge feature-branch
git push origin main
```

---

## 🔁 Common Git & GitHub Commands Recap

| Command                         | Purpose                                        |
|---------------------------------|------------------------------------------------|
| `git init`                      | Initialize a new Git repository                |
| `git remote add origin <url>`   | Link local repo with remote repo               |
| `git clone <url>`               | Clone a remote repo locally                    |
| `git pull`                      | Fetch and merge remote changes                 |
| `git push`                      | Upload local changes to remote                 |
| `git branch`                    | List branches                                  |
| `git checkout -b <branch>`      | Create and switch to a new branch              |
| `git merge`                     | Combine changes from one branch into another   |



| Student                | Assigned Task  | File/Branch Name       |
| ---------------------- | -------------- | ---------------------- |
| **Nour**               | Home Page      | `index/nour`           |
| **Mesk**               | Resources Page | `resources/mesk` |
| **Khalil**             | Science Page   | `science/khalil`   |
| **Mohammed Abed Nabi** | Math Page      | `math/mohmmed`      |
