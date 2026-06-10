# Contributing

Thank you for contributing to this project.

## Fork the Repository

1. Fork the repository to your GitHub account.
2. Clone your fork locally.
3. Add the original repository as `upstream`.

## Create a Branch

Always create a branch from the latest `main`:

```bash
git checkout main
git pull origin main
git checkout -b type/short-description
```

Examples:

* feat/add-glossary
* fix/readme-links
* docs/contributing

## Commit Rules

Use this format:

```text
type(scope): short description
```

Examples:

```text
feat(auth): add login feature
fix(ui): resolve mobile layout issue
docs(readme): update setup instructions
```

## Pull Request Rules

1. Push your branch to GitHub.
2. Open a Pull Request against `main`.
3. Use a descriptive PR title.
4. Link the related issue:

```text
Closes #ISSUE_NUMBER
```

5. Request a review from at least one teammate.

## Getting a Review

* Wait for reviewer feedback.
* Make requested changes if needed.
* Move the task to **In Review** while the PR is open.
* Do not merge your own Pull Request unless instructed by the team.

