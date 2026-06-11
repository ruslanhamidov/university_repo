# University Repo Collaboration Guide

This repository is a team project reference.

## Getting Started
1. **Fork the repo:** Click the "Fork" button on GitHub.
2. **Clone it:** `git clone https://github.com/Aysel-Bayramova/university_repo.git`
   > **Note:** Replace `Aysel-Bayramova` with your actual GitHub username if you cloned your own fork.
3. **Set Up:** `cd university_repo` then `git remote add upstream https://github.com/ruslanhamidov/university_repo.git`

## How to Work
1. **Sync:** `git checkout main` then `git pull origin main`
2. **Branch:** `git checkout -b type/short-description` (e.g., `feat/add-login`)
3. **Commit:** `git add .` then `git commit -m "type(scope): description"`
4. **Push:** `git push -u origin your-branch-name`
5. **PR:** Create a Pull Request on GitHub and link the issue with `Closes #ISSUE_NUMBER`

## Common Mistakes
1. **Committing to main:** Never commit directly to `main`. Always use feature branches to keep the codebase clean.
2. **Force Pushing:** Never use `git push --force`. Use `--force-with-lease` to prevent overwriting someone else's work.
3. **Bad Messages:** Follow the `type(scope): description` format.
4. **Not Syncing:** Always `pull` main or `rebase` before starting a new task to avoid conflicts.
5. **Handling Conflicts:** Stay calm! If a conflict occurs, `git rebase` is your friend. Follow the markers in your editor, save, `git add`, and `git rebase --continue`.
