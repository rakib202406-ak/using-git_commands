# 🚀 Ultimate Git & GitHub Command Guide

A comprehensive cheat sheet and guide containing all essential Git commands from your PDF, plus industry-standard best practices for GitHub.

---

## ⚙️ 1. Initial Configuration
Set up your identity before you start committing code. These settings are saved globally on your machine.

* **Set Username:** `git config --global user.name "Your Name"`
* **Set Email:** `git config --global user.email "yourname@email.com"`
* **Check Settings:** `git config --list`

---

## 📁 2. Basic Workflow (Local Repository)
Commands to initialize, track, and save changes in your project.

* **Initialize Repo:** `git init`
* **Check Status:** `git status`
* **Stage a File:** `git add <file_name>`
* **Stage All Files:** `git add .`
* **Commit Changes:** `git commit -m "Your descriptive message"`
* **View History:** `git log`
* **Compact History:** `git log --oneline`

---

## 🌿 3. Branching & Merging
Used for working on new features without breaking the main code.

* **List Branches:** `git branch`
* **Create New Branch:** `git branch <branch_name>`
* **Switch Branch:** `git checkout <branch_name>`
* **Create & Switch:** `git checkout -b <branch_name>`
* **Merge Branch:** `git merge <branch_name>`
* **Delete Branch:** `git branch -d <branch_name>`

---

## 🌐 4. Working with Remote (GitHub)
Connect your local code to the cloud.

* **Clone Repository:** `git clone <URL>`
* **Add Remote:** `git remote add origin <URL>`
* **Push Code:** `git push -u origin main`
* **Pull Updates:** `git pull`
* **Fetch Only:** `git fetch`

---

## ⏪ 5. Undoing & Fixing Mistakes
> ⚠️ **Warning:** Be careful with these commands as they can overwrite your work.

* **Discard Unstaged Changes:** `git restore <file_name>`
* **Unstage a File:** `git restore --staged <file_name>`
* **Soft Reset:** `git reset --soft HEAD^` (Deletes commit, keeps code)
* **Hard Reset:** `git reset --hard HEAD^` (Deletes commit AND code changes)
* **Clean Untracked Files:** `git clean -f`

---

## 🔥 6. Essential GitHub Best Practices
To make your GitHub profile look professional, follow these:

* **Use `.gitignore`:** Always exclude `node_modules/`, `.env`, or build folders.
* **Meaningful Commits:** Use the "Atomic Commit" rule. One commit per fix/feature.
    * *Example:* `feat: add user login`, `fix: resolve header alignment`.
* **Pull Requests (PRs):** In a professional environment, push to a feature branch and open a PR for review.
* **SSH Keys:** Set up SSH keys to avoid typing your password every time.
* **GitHub Pages:** Host static websites for free via **Settings > Pages**.

---
_Generated based on Git Training Documentation_
