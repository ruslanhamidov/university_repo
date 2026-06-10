# 🧑‍💻 GitHub Collaboration Guide

This is your complete reference for working with Git and GitHub as a team.
Read it top to bottom once, then use it as a reference while you work.

The actual tasks you need to complete are in `TASKS.md`.

---

## 📚 Start Here — Recommended Resources

Go through at least one of these before you begin:

1. [**GitHub Skills**](https://skills.github.com/) — Hands-on exercises directly inside GitHub. Best starting point.
2. [**Atlassian Git Tutorials**](https://www.atlassian.com/git/tutorials) — Visual explanations of every Git concept.
3. [**Pro Git Book**](https://git-scm.com/book/en/v2) — The full official reference. Chapters 1–3 are enough.
4. [**Oh My Git!**](https://ohmygit.org/) — A game that teaches Git visually.

---

## 1. How to Fork the Repository

> Do this once at the start of the project.

1. Open the repository page on GitHub.
2. Click **Fork** in the top-right corner.
3. Select your personal account as the destination.
4. Open your terminal.
5. Run `git clone https://github.com/YOUR_USERNAME/REPO_NAME.git`
6. Run `cd REPO_NAME`
7. Run `git remote add upstream https://github.com/ORIGINAL_OWNER/REPO_NAME.git`
8. Run `git remote -v` — confirm you see both `origin` and `upstream`.

> `origin` points to your fork. `upstream` points to the original repo.

---

## 2. How to Add Collaborators

> Only the repository owner does this.

1. Go to the repository on GitHub.
2. Click **Settings**.
3. Click **Collaborators** in the left sidebar.
4. Click **Add people**.
5. Search for your teammate's GitHub username.
6. Click **Add [username] to this repository**.
7. Repeat steps 4–6 for every teammate.
8. Ask teammates to check their email and accept the invitation.

---

## 3. How to Set Up the Kanban Board

1. Go to the repository on GitHub.
2. Click the **Projects** tab.
3. Click **New project**.
4. Select the **Board** template.
5. Name it `Sprint 1`.
6. Click **Create project**.
7. Set the columns to: `Backlog` → `To Do` → `In Progress` → `In Review` → `Done`.
8. Go to `TASKS.md` and create a GitHub Issue for each task.
9. Open the board and add each issue as a card under **Backlog**.
10. Assign each card to a team member.

### How the board moves

- When you start a task → move card to **To Do**
- When you are actively working → move to **In Progress**
- When your PR is open → move to **In Review**
- When the PR is merged → move to **Done**

---

## 4. How to Create and Name a Branch

> Do this every time you start a new task.

1. Run `git checkout main`
2. Run `git pull origin main`
3. Run `git checkout -b type/short-description`

### Branch naming pattern
