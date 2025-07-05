# 🚀 Git Best Practices – Start to Finish

Welcome to the ultimate guide on Git best practices! This repository is designed to be an **educational resource** and **reference manual** for anyone looking to use Git professionally — whether you're working solo, contributing to open source, or collaborating within a team.

You'll learn **how to set up a Git project**, create clean and structured workflows, write meaningful commits, manage branches, push code safely, and tag production-ready releases — all using **industry-approved standards**.

---

## 📌 Quick Setup Cheat Sheet

Here's a complete Git flow for starting and managing a new project:

```bash
# 🛠️ Initialize project
git init
echo "*.env" > .gitignore
git add .
git commit -m "chore: initial project setup"

# 🌐 Connect to remote repository
git remote add origin https://github.com/username/project.git
git branch -M main
git push -u origin main

# 🌱 Create a feature branch
git checkout -b feature/user-auth
# Work and commit
git add .
git commit -m "feat: implement JWT-based login"
# Push and open a PR
git push -u origin feature/user-auth

# 🧪 Review & merge, then tag release
git tag -a v1.0.0 -m "Add authentication module"
git push origin v1.0.0
```
