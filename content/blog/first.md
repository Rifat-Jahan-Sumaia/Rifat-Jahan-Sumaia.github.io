---
title: "Introduction to Git and GitHub"
date: 2024-11-19
draft: false
featured: true
summary: "Learn the basics of Git, a version control system, and GitHub, a platform for collaborating on code projects."
tags:
  - Git
  - GitHub
  - Version Control
featured: true
image:
  src: images/git-github-cover.png
  alt: "Git and GitHub logo"
---
**Git** is a distributed version control system designed to track changes in source code during software development. It helps developers collaborate effectively and maintain a history of changes.

**GitHub** is a cloud-based hosting service for Git repositories. It allows teams to collaborate on projects, review code, and manage issues.

### Key Features of Git:
1. **Branching and Merging**: Create separate branches for features or fixes and merge them when ready.
2. **Commit History**: Track every change with detailed messages.
3. **Distributed Development**: Every developer has a complete copy of the repository.

### Key Features of GitHub:
1. **Pull Requests**: Propose changes and discuss with your team.
2. **Issue Tracking**: Keep track of bugs and feature requests.
3. **Actions**: Automate workflows like CI/CD.

---

### Basic Git Commands
```bash
# Initialize a repository
git init

# Clone a repository
git clone <repository-url>

# Check status
git status

# Stage changes
git add <file>

# Commit changes
git commit -m "Message"

# Push changes to GitHub
git push
