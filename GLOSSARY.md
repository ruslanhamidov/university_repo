# Git Glossary

A reference guide to essential Git terminology used in this project.

---

## 1. Branch
A lightweight, movable pointer to a specific commit that allows parallel development without affecting the main codebase.

**Example:**
```bash
git checkout -b feat/new-feature
# Creates and switches to a new branch called "feat/new-feature"
```

---

## 2. Clone
Copying a remote repository to your local machine, including all files, history, and branches.

**Example:**
```bash
git clone https://github.com/fatimehuseynli19/university_repo.git
# Creates a local copy of the remote repository
```

---

## 3. Commit
A snapshot of staged changes saved permanently to the repository's history with a descriptive message.

**Example:**
```bash
git commit -m "feat: add GLOSSARY.md"
# Saves staged changes with a meaningful message
```

---

## 4. Fork
A personal copy of someone else's repository on GitHub, allowing you to experiment freely without affecting the original project.

**Example:**
> Click **Fork** on any GitHub repository → it appears under your own account as `your-username/university_repo`

---

## 5. HEAD
A special pointer that indicates the current position in the repository — usually pointing to the latest commit on the active branch.

**Example:**
```bash
git log --oneline
# The topmost commit marked with HEAD is where you currently are
```

---

## 6. Merge
Integrating changes from one branch into another, combining their histories into a single unified branch.

**Example:**
```bash
git checkout main
git merge feat/glossary
# Brings changes from "feat/glossary" into the "main" branch
```

---

## 7. Pull Request (PR)
A GitHub feature to propose merging your branch into another, allowing teammates to review, comment, and approve changes before they are merged.

**Example:**
> After pushing `feat/glossary`, open a PR on GitHub:
> `feat/glossary → main` with title `feat: add GLOSSARY.md`

---

## 8. Rebase
Moving or replaying commits from one branch on top of another to create a cleaner, linear commit history.

**Example:**
```bash
git checkout feat/glossary
git rebase main
# Replays your commits on top of the latest main branch
```

---

## 9. Staging Area
An intermediate zone (also called the index) where changes are prepared and reviewed before being committed to the repository.

**Example:**
```bash
git add GLOSSARY.md
# GLOSSARY.md is now in the staging area, ready to be committed
```

---

## 10. Upstream
The original remote repository that a fork was created from, typically used as a reference to pull in the latest changes from the source project.

**Example:**
```bash
git remote add upstream https://github.com/fatimehuseynli19/university_repo.git
git pull upstream main
# Fetches and merges the latest changes from the original repo
```

---

*Glossary created as part of Task 3 — Holberton Group Project*
