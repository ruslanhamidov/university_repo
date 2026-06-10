# 📖 Git and GitHub Glossary

This glossary defines the core terms used in Git version control and GitHub collaboration.

---

## Core Terms

### 1. Repository (Repo)
- **Definition:** A folder or storage space where your project's files and the entire history of their changes are kept by Git.
- **Analogy:** Think of it as a digital project folder with a built-in time machine.

### 2. Commit
- **Definition:** A snapshot of your changes recorded in the repository history. Every commit has a unique ID (SHA-1 hash) and a commit message describing what changed.
- **Analogy:** Like saving your progress in a video game.

### 3. Branch
- **Definition:** An independent line of development. The default branch is usually named `main`. Creating a new branch allows you to work on features or fixes without affecting the stable code.
- **Analogy:** A parallel universe where you can experiment safely.

### 4. Clone
- **Definition:** Downloading a complete copy of a remote GitHub repository onto your local computer.
- **Command:** `git clone <repository-url>`

### 5. Fork
- **Definition:** A personal copy of someone else's repository created on your GitHub account. It allows you to freely experiment and make changes without affecting the original project.

### 6. Push
- **Definition:** Sending your local commits from your computer up to a remote repository on GitHub.
- **Command:** `git push origin <branch-name>`

### 7. Pull
- **Definition:** Fetching and downloading the latest changes from the remote repository on GitHub directly into your local working branch.
- **Command:** `git pull origin <branch-name>`

### 8. Pull Request (PR)
- **Definition:** A submission on GitHub where you ask the project maintainers or teammates to review the changes you made on a branch and merge them into the main repository.

### 9. Merge
- **Definition:** Combining the histories and changes from one branch (e.g., a feature branch) into another branch (e.g., `main`).

### 10. Merge Conflict
- **Definition:** A situation where Git cannot automatically combine changes because two or more people edited the exact same line of code in the same file. It must be resolved manually.
EOF
