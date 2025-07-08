## **Quick Reference**

### Essential Git Commands
```bash
# Setup
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Repository operations
git init                    # Initialize new repository
git clone <url>            # Clone existing repository
git status                 # Check repository status
git log                    # View commit history

# File operations
git add <file>             # Stage specific file
git add .                  # Stage all changes
git commit -m "message"    # Commit staged changes
git diff                   # Show unstaged changes

# Branch operations
git branch                 # List branches
git branch <name>          # Create new branch
git checkout <branch>      # Switch to branch
git checkout -b <branch>   # Create and switch to branch
git merge <branch>         # Merge branch into current branch
git branch -d <branch>     # Delete merged branch

# Remote operations
git remote add origin <url>  # Add remote repository
git push origin <branch>     # Push branch to remote
git pull origin <branch>     # Pull changes from remote
git fetch                    # Download remote changes
```
---

### Glossary of Terms
- **Repository:** Storage location for project files and history
- **Commit:** Snapshot of project at specific point in time
- **Branch:** Parallel line of development
- **Merge:** Combining changes from different branches
- **Clone:** Creating local copy of remote repository
- **Fork:** Creating personal copy of someone else's repository
- **Pull Request:** Proposing changes to be merged into project
- **Staging Area:** Holding area for changes before committing
- **HEAD:** Pointer to current branch and commit
- **Origin:** Default name for primary remote repository

### Resources for Continued Learning

#### **Official Documentation**
- **Git Official Documentation** - git-scm.com/doc
- **GitHub Guides** - guides.github.com
- **Pro Git Book** - Free online book covering Git comprehensively

#### **Interactive Learning**
- **GitHub Learning Lab** - Hands-on tutorials
- **Git Immersion** - Step-by-step Git tutorial
- **Learn Git Branching** - Visual and interactive Git learning
---
