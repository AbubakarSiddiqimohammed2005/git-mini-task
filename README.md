# Git Mini Task

This project demonstrates the implementation of Git and GitHub operations such as repository initialization, commits, branch creation, push operations, pull requests, merge operations, reset commands, and revert commands.

---

# 📌 Project Objective

The objective of this project is to understand and practice:

- Git repository setup
- Git commits
- Branch creation and switching
- Push operations
- Pull requests
- Merge operations
- Git reset
- Git revert
- GitHub workflow

---

# 🛠️ Technologies Used

- Git
- GitHub
- VS Code
- PowerShell / Command Prompt

---

# 📂 Repository Structure

```bash
git-mini-task/
│
├── orders.txt
├── products.txt
└── README.md
```

---

# 🚀 Step-by-Step Implementation

## 1️⃣ Creating Initial Repository

Initialized an empty Git repository:

```bash
git init
```

Added files to staging:

```bash
git add .
```

Created the initial commit:

```bash
git commit -m "initial commit"
```

---

## 2️⃣ Configuring Git and Connecting to GitHub

Configured Git username and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

Renamed branch to main:

```bash
git branch -M main
```

Connected local repository to GitHub:

```bash
git remote add origin <repository-url>
```

Pushed the project to GitHub:

```bash
git push -u origin main
```

---

## 3️⃣ Creating Branches

Created two branches:

```bash
git branch addProduct
git branch addOrder
```

Switched branches:

```bash
git switch addProduct
git switch addOrder
```

---

## 4️⃣ Updating Files in Branches

### addProduct Branch

Updated `products.txt` and committed changes:

```bash
git add products.txt
git commit -m "products updated"
git push origin addProduct
```

### addOrder Branch

Updated `orders.txt` and committed changes:

```bash
git add orders.txt
git commit -m "orders updated by pavan"
git push origin addOrder
```

---

## 5️⃣ Pull Requests and Merge Operations

- Created Pull Requests for:
  - addProduct
  - addOrder

- Merged both branches into the `main` branch successfully.

---

## 6️⃣ Git Reset Operation

Performed reset operation:

```bash
git reset <commit-id> --hard
```

### Purpose

- Moves HEAD to a previous commit
- Removes recent changes temporarily

---

## 7️⃣ Git Revert Operation

Performed revert operation:

```bash
git revert <commit-id>
```

### Purpose

- Reverses previous commit changes
- Maintains Git history safely

---

# 📸 Screenshots Included

The documentation contains screenshots for:

- Initial repository setup
- Git configuration
- Branch creation
- Push operations
- GitHub branches
- Pull requests
- Merge history
- Reset operation
- Revert operation

---

# ✅ Learning Outcomes

Through this project, I learned:

- Git repository management
- Git branching workflow
- Pull request handling
- Merge operations
- Reset and revert commands
- GitHub collaboration process

---

# 👨‍💻 Author

**Pavan Kumar**

GitHub Profile:  
https://github.com/mamidipakapavan02-blip

---
