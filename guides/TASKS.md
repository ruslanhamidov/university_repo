# TASKS.md — Sprint Tasks

You are a contributor to this repository. Your job is to improve it, fix it, and extend it — the same way developers contribute to real open source projects.

Each task below is a GitHub Issue. Create all of them in the Issues tab, add them to the Kanban board under **Backlog**, and assign them to team members before you start.

---

## How Kanban works here

- Pick a task from **Backlog** → move it to **To Do**
- Start working → move it to **In Progress**
- Open a PR → move it to **In Review**
- PR gets merged → move it to **Done**

---

## Tasks

---

### `feat: add a "Common Mistakes" section to the README`

A section that lists the most frequent Git mistakes beginners make and how to fix them.
Things like committing directly to main, using `git push --force` instead of `--force-with-lease`, or writing bad commit messages.

**Your job:**
1. Create a branch `feat/common-mistakes`
2. Add a new section `## Common Mistakes` at the bottom of `README.md`
3. List at least 4 mistakes with a short explanation for each
4. Open a PR titled `feat(readme): add common mistakes section`
5. Link this Issue in the PR description

---

### `fix: audit the README for unclear or missing steps`

Read through the entire `README.md` as if you are a student seeing it for the first time.
Find any step that is confusing, missing, or wrong.

**Your job:**
1. Create a branch `fix/readme-audit`
2. Fix every unclear or incomplete step you find
3. Commit each fix separately with a descriptive message
4. Open a PR titled `fix(readme): clarify steps in [section name]`
5. In the PR description, list everything you changed and why

---

### `feat: create a GLOSSARY.md`

New contributors get confused by terms like `upstream`, `rebase`, `staging area`, `HEAD`.
This file gives them a quick reference.

**Your job:**
1. Create a branch `feat/glossary`
2. Create a new file `GLOSSARY.md` at the root of the repo
3. Define at least 10 Git/GitHub terms in plain language
4. Each term should have: the word, a one-sentence definition, and a short example
5. Open a PR titled `feat: add GLOSSARY.md`

---

### `chore: reorganize the repo folder structure`

The repo has no folders. As it grows this will get messy.
Propose and implement a cleaner structure.

**Your job:**
1. Create a branch `chore/folder-structure`
2. Create a `/guides` folder and move relevant `.md` files into it
3. Update any internal links in `README.md` that break after the move
4. Open a PR titled `chore: reorganize files into /guides folder`
5. In the PR description, explain why you structured it this way

---

### `docs: add a CONTRIBUTING.md`

Real open source repos have a `CONTRIBUTING.md` that tells new contributors exactly how to work on the project.

**Your job:**
1. Create a branch `docs/contributing`
2. Create `CONTRIBUTING.md` at the root of the repo
3. Include: how to fork, how to branch, commit rules, PR rules, and how to get a review
4. Keep it short — a new person should be able to read it in under 3 minutes
5. Open a PR titled `docs: add CONTRIBUTING.md`

---

### `fix: simulate and resolve a merge conflict`

> This task requires two people working together.

Both of you will edit the same line in `README.md`. One PR merges first. The other person has to resolve the conflict before their PR can merge.

**Your job:**
1. Person A and Person B each create a branch from the same point on `main`
2. Both edit the opening paragraph of `README.md` — differently
3. Person A opens a PR and merges it first
4. Person B fetches, rebases, and resolves the conflict
5. Person B pushes and opens their PR
6. Person B adds a comment to this Issue describing what the conflict was and how they resolved it

---

### `feat: add a "What We Built" section to the README`

At the end of the project, the README should summarize what the team actually produced.

**Your job:**
1. Create a branch `feat/what-we-built`
2. Add a `## What We Built` section at the end of `README.md`
3. List every file in the repo with a one-sentence description of what it contains
4. Add each contributor's GitHub username with a link to their profile
5. Open a PR titled `feat(readme): add what we built section`

> This task should be done last, after all other PRs are merged.
