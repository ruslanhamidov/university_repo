# CONVENTIONS.md — Naming & Workflow Rules

This file covers how to name things and what commands to run. Follow these exactly.

---

## Part 1 — Branch Naming

Every branch name follows this pattern:

```
type/short-description
```

| Type | When to use |
|------|------------|
| `feat` | Adding something new |
| `fix` | Fixing a bug |
| `docs` | Documentation only |
| `refactor` | Restructuring code, no new feature |
| `chore` | Config, dependencies, tooling |
| `test` | Adding or updating tests |

**Examples:**
```
feat/user-login
fix/navbar-overflow
docs/update-readme
chore/update-dependencies
```

### Creating a branch

1. Run `git checkout main`
2. Run `git pull origin main`
3. Run `git checkout -b type/your-description`

---

## Part 2 — Commit Naming

Every commit message follows this pattern:

```
type(scope): short description
```

- `type` — same types as branch naming above
- `scope` — the part of the project affected (e.g. `auth`, `ui`, `api`)
- `short description` — lowercase, present tense, no period

**Examples:**
```
feat(auth): add Google OAuth login
fix(navbar): resolve dropdown overlap on mobile
docs: add setup instructions to README
chore: upgrade eslint to v9
```

### Making a commit

1. Run `git status` to see what changed.
2. Run `git add .` to stage all changes, or `git add filename` for a specific file.
3. Run `git commit -m "type(scope): your description"`

---

## Part 3 — Pushing Your Branch

1. Run `git push -u origin your-branch-name` on your first push.
2. Run `git push` for every push after that on the same branch.

---

## Part 4 — Creating a Pull Request

1. Go to the repository on GitHub.
2. Click **Compare & pull request** (appears after a recent push).
3. Set **base** to `main` and **compare** to your branch.
4. Write the PR title using the same convention as commits: `feat(auth): add Google OAuth login`
5. Fill in the description using this template:

```
## What does this PR do?


## Why?


## How to test?

```

6. Assign at least one teammate as a **Reviewer**.
7. Link the related Issue by writing `Closes #ISSUE_NUMBER` in the description.
8. Click **Create Pull Request**.
9. Move your Kanban card to **In Review**.

> Do not merge your own PR. Wait for a teammate to review and approve it.

---

## Part 5 — Syncing Your Branch When Main Changes

Run these commands whenever a teammate merges something into `main` while you are still on your branch:

1. Run `git fetch origin`
2. Run `git rebase origin/main`
3. If there are conflicts, open the conflicted file in your editor.
4. Find the conflict markers:

```
<<<<<<< HEAD
your version
=======
their version
>>>>>>> origin/main
```

5. Delete the markers and keep the correct version (yours, theirs, or a combination).
6. Run `git add filename` on each resolved file.
7. Run `git rebase --continue`
8. Run `git push --force-with-lease`

> If something goes wrong during rebase, run `git rebase --abort` to reset back to where you started.

---

## Part 6 — Daily Sync Habit

Run this every time you sit down to work:

1. Run `git checkout main`
2. Run `git pull origin main`
3. Run `git checkout your-branch-name`
4. Run `git rebase origin/main`
