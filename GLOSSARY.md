# Git/GitHub Glossary

A quick reference for common Git and GitHub terms.

---

## Repository (Repo)
A folder that Git tracks. It contains all your project files and the full history of changes.
**Example:** `git clone https://github.com/user/repo.git`

---

## Clone
Copying a remote repository to your local machine.
**Example:** `git clone https://github.com/user/repo.git`

---

## Branch
An independent line of development. You create a branch to work on a feature without affecting the main code.
**Example:** `git checkout -b feat/login-page`

---

## Commit
A saved snapshot of your changes with a message describing what you did.
**Example:** `git commit -m "feat(auth): add login form"`

---

## Push
Sending your local commits to the remote repository on GitHub.
**Example:** `git push origin feat/login-page`

---

## Pull
Fetching and merging the latest changes from the remote repository into your local branch.
**Example:** `git pull origin main`

---

## Merge
Combining changes from one branch into another.
**Example:** `git merge feat/login-page`

---

## Rebase
Moving your branch commits on top of another branch to keep a clean history.
**Example:** `git rebase origin/main`

---

## Upstream
The original repository that a fork was created from.
**Example:** `git remote add upstream https://github.com/original/repo.git`

---

## Staging Area
A place where you prepare changes before committing them.
**Example:**