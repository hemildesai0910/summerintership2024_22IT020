# summerintership2024_22IT020
# 4th Sem Summer Internship
# 🌞 Summer Internship 2024 Weekly Reports
# 📅 Week 1: 13/05/2024 - 17/05/2024
# 📝 Summary of Work Done
# 📅 Day 1: 13/05/2024 (Monday)
# Git and GitHub Basics:
  📚 Introduction to Git and GitHub
  🔄 Differences between Git and GitHub
  📋 Overview of Version Control Systems
  🛠️ Installing Git
# 📅 Day 2: 14/05/2024 (Tuesday)
# Understanding Git Terminology:
  🗣️ Git Terminology
  📂 Repository Setup
  ⚙️ Config Settings
  💾 Commit Changes
# 📅 Day 3: 15/05/2024 (Wednesday)
# Git Workflow and Commands:
  🔄 Complete Git Flow
  📝 Stage and Commit
  📜 Logs and Gitignore
  🏁 Conclusion
# 📅 Day 4: 16/05/2024 (Thursday)
# Git Internals:
  🔍 Git Behind the Scenes
  📸 Git Snapshots
  ⚔️ The Three Musketeers of Git: Commit, Tree, Blob Object
  🛠️ Helpful Commands
# 📅 Day 5: 17/05/2024 (Friday)
# Advanced Git Concepts:
  🌿 Branches in Git
  🌱 Creating New Branches
  🔀 Merging Branches
  🏁 Conclusion
# 📅 Day 1: 13/05/2024 (Monday)
# Git and GitHub Basics:
 - Introduction to Git and GitHub:
    - Git is a version control system that tracks changes to your files.
    - GitHub is an online platform for hosting Git repositories and collaborating with others.
  - Differences between Git and GitHub:
    - Git is installed locally on your computer.
    - GitHub is a web-based service for hosting repositories.
  - Version Control Systems:
    - Track changes and manage code history, similar to checkpoints in a game.
  - Installing Git:
    - Download and install Git from the official [website](https://git-scm.com/downloads).
  - Conclusion:
    - Learned basics of Git and GitHub, their importance, and how to install Git.
# 📅 Day 2: 14/05/2024 (Tuesday)
# Understanding Git Terminology:
  Terminology:
  Key terms: repository, branch, commit, etc.
  Repository Setup:
  Creating and initializing a Git repository.
  Config Settings:
  Setting up username and email:
  sh
  ![image](https://github.com/hemildesai0910/summerintership2024_22IT020/assets/147586274/533ad0ad-2255-40cf-8686-2b686681cd7e)

  Commit Changes:
  Using git commit to save changes with a message.
# 📅 Day 3: 15/05/2024 (Wednesday)
# Git Workflow and Commands:
  Complete Git Flow:
  Basic commands: init, add, commit, push.
  Stage and Commit:
  Commands to stage and commit files:
  sh
  Copy code
  git init
  git add <file>
  git commit -m "message"
  Logs and Gitignore:
  Using git log to view commit history.
  Creating a .gitignore file to exclude specific files or folders.
# 📅 Day 4: 16/05/2024 (Thursday)
# Git Internals:
  Git Behind the Scenes:
  How Git stores information as snapshots.
  Git Snapshots:
  Representations of code at specific points in time.
  The Three Musketeers of Git:
  Commit Object: Contains commit information.
  Tree Object: Contains the directory structure and file metadata.
  Blob Object: Contains the actual file contents.
  Helpful Commands:
  Explore Git internals with commands:
  sh
  Copy code
  git show -s --pretty=raw <commit-hash>
  git ls-tree <tree-id>
  git show <blob-id>
  git cat-file -p <commit-id>
# 📅 Day 5: 17/05/2024 (Friday)
# Advanced Git Concepts:
  Branches in Git:
  Creating and switching branches:
  sh
  Copy code
  git branch
  git branch <branch-name>
  git switch <branch-name>
  git log
  git switch master
  git switch -c <new-branch>
  git checkout <branch-name>
  Merging Branches:
  Fast-forward and not fast-forward merges:
  sh
  Copy code
  git checkout main
  git merge <branch-name>
  Managing Conflicts:
  Resolving merge conflicts manually or with tools like VSCode.
  Additional Commands:
  Rename, delete, list branches:
  sh
  Copy code
  git branch -m <old-branch-name> <new-branch-name>
  git branch -d <branch-name>
  git branch
  Conclusion:
  Learned about branching, merging, and conflict resolution in Git.
