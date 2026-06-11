Markdown
# 🤝 Contributing to University Repo

Welcome! We are thrilled that you want to contribute to our project. To keep everything organized and running smoothly, please follow these simple guidelines.

---

## 🚀 1. Getting Started (Fork & Clone)

1. **Fork** this repository to your own GitHub account.
2. **Clone** your forked repository to your local computer:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/university_repo.git](https://github.com/YOUR_USERNAME/university_repo.git)
Add the original repository as your upstream remote to keep your code updated:

Bash
git remote add upstream [https://github.com/ORIGINAL_OWNER/university_repo.git](https://github.com/ORIGINAL_OWNER/university_repo.git)
🌿 2. Branching Strategy
Never work directly on the main branch. Always create a new branch for every task using the following pattern:

Plaintext
type/short-description
feat/ — for adding a new feature (e.g., feat/add-glossary)

fix/ — for fixing an error or bug (e.g., fix/readme-typos)

docs/ — for documentation updates only (e.g., docs/contributing)

Create your branch locally:

Bash
git checkout -b type/short-description
✍️ 3. Commit Message Rules
We follow strict commit message guidelines to maintain a clean project history:

Plaintext
type(scope): short description in present tense
Good Examples:

feat(glossary): add 10 essential git terms

fix(readme): update broken kanban rule description

docs(contributing): create absolute guide for newcomers

📥 4. Pull Request (PR) & Review Process
Push your branch to your remote fork (origin):

Bash
git push -u origin your-branch-name
Go to your repository on GitHub and click Compare & pull request.

Set the base to main and make sure you fill in the PR description template.

Request a Review: Tag at least one teammate as a reviewer in the sidebar.

Get Merged: Once your code is reviewed, approved, and passes checks, it will be merged into main. Do not merge your own PR!


---
