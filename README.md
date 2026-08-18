# Learning Git and GitHub 🚀

This repository serves as a personal log and reference guide for everything I learned today about version control with Git and hosting on GitHub.

## 📌 Concepts Covered

* **Version Control**: Tracking changes in code files over time.
* **Git vs GitHub**: Git is the local tool on my computer; GitHub is the online platform to share and host code.
* **The 3 Git States**:
  * **Working Directory**: Where I modify files.
  * **Staging Area**: Where I prepare files for a save.
  * **Local Repository**: Where Git permanently saves snapshots (commits).
* **Branching**: Creating isolated environments to work on new features without breaking the main code.
* **Merge Conflicts**: Learning how Git stops when changes overlap, and how to manually clean up conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`).

---

## 🛠️ Essential Commands Reference

### 1. File & Directory Navigation (Linux/Bash)
* `pwd` - Print working directory (see where you are).
* `ls` - List files in the current folder.
* `cd <folder>` - Change directory to enter a folder.
* `mkdir <folder>` - Create a new directory.
* `touch <file>` - Create a new empty file.

### 2. Basic Git Workflow
* `git init` - Initialize a brand new local repository.
* `git status` - Check the state of your working directory and staging area.
* `git add <file>` - Add a specific file to the staging area.
* `git commit -m "your message"` - Save your staged snapshot to the local history.

### 3. Branching & Switching
* `git branch <name>` - Create a new branch.
* `git switch <name>` (or `git checkout <name>`) - Switch to an existing branch.
* `git switch -c <name>` (or `git checkout -b <name>`) - Create a new branch and switch to it instantly.

### 4. Merging & Conflicts
* `git merge <branch>` - Combine changes from another branch into your current branch.
* `git merge --abort` - Stop the merge process and completely reset if a conflict gets too messy.

---

## 💡 Key Takeaways
* Always check `git status` frequently to know exactly what state your files are in.
* Press `q` to exit out of the terminal when stuck in a long file reader log screen (like `git log`).
* Never commit code with raw conflict markers left inside the file.
