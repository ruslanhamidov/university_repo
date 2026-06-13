# Contributing Guide

Thank you for contributing to this project. This guide explains how to work on tasks, make changes, and open pull requests.

## 1. Fork or Clone the Repository

If you do not have write access, fork the repository first and clone your fork:

```bash
git clone https://github.com/YOUR_USERNAME/REPO_NAME.git
```

If you are added as a collaborator, you can clone the shared repository directly.

## 2. Create a Branch

Always create a new branch for each task. Do not work directly on `main`.

```bash
git checkout main
git pull origin main
git checkout -b type/short-description
```

Use these branch types:

* `feat` — for new features
* `fix` — for bug fixes or corrections
* `docs` — for documentation changes
* `chore` — for structure, setup, or cleanup changes

Example:

```bash
git checkout -b docs/update-readme
```

## 3. Commit Rules

Use clear commit messages with this format:

```bash
type(scope): short description
```

Examples:

```bash
docs(readme): clarify branch instructions
fix(tasks): correct broken link
chore: move files into guides folder
```

Keep commits focused. One commit should explain one clear change.

## 4. Pull Request Rules

Push your branch:

```bash
git push -u origin your-branch-name
```

Then open a pull request on GitHub.

Your PR should include:

* A clear title
* A short explanation of what changed
* Why the change was needed
* How reviewers can check it
* A linked issue if the task has one

Do not merge your own pull request.

## 5. Getting a Review

After opening your pull request:

1. Assign at least one teammate as a reviewer.
2. Move the task card to **In Review**.
3. Wait for feedback.
4. If changes are requested, update your branch and push again.
5. Merge only after the pull request is approved.
