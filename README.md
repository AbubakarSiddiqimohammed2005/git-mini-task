# Git Mini Task

## 📌 Overview
This project demonstrates the complete workflow of Git and GitHub collaboration. It includes:

- Repository initialization
- Branch creation
- Commits and pushes
- Pull requests and merging
- Git reset
- Git revert

---

# 🚀 Step 1: Repository Setup

Initialized an empty Git repository and created the files:

- `orders.txt`
- `products.txt`

Added the files to staging and committed them as the initial commit.

## 📷 Output

<img width="856" height="447" alt="Capture" src="https://github.com/user-attachments/assets/7dd9e8ea-3b30-4b5b-90b7-520161d7d25d" />

## 💻 Commands Used

```bash
git init
git add .
git commit -m "Initial commit"
```

---

# ⚙️ Step 2: Configure Git & Push to GitHub

Configured Git username and email, renamed the branch to `main`, connected the repository to GitHub, and pushed the project successfully.

## 📷 Output

<img width="759" height="437" alt="image" src="https://github.com/user-attachments/assets/1b15a178-5a0b-4d88-a276-6b4d7ee01fbc" />

## 💻 Commands Used

```bash
git config --global user.name "Your Name"
git config --global user.email "yourmail@example.com"

git branch -M main

git remote add origin <repository-url>

git push -u origin main
```

---

# 🌿 Step 3: Branch Creation & File Updates

Created two branches:

- `addProduct`
- `addOrder`

Updated files in their respective branches and pushed them to GitHub.

## 📷 Output

<img width="849" height="288" alt="image" src="https://github.com/user-attachments/assets/085a2223-e1b3-4d4d-a053-babbb561aa33" />

## 💻 Commands Used

### Add Product Branch

```bash
git checkout -b addProduct
git add .
git commit -m "Updated products"
git push origin addProduct
```

### Add Order Branch

```bash
git checkout -b addOrder
git add .
git commit -m "Updated orders"
git push origin addOrder
```

---

# 🔍 Step 4: View Branches on GitHub

Verified the branches on GitHub:

- `main`
- `addProduct`
- `addOrder`

## 📷 Output

<img width="979" height="1236" alt="image" src="https://github.com/user-attachments/assets/32462827-747e-4bda-9f5d-5860ac133fd0" />

---

# 🔀 Step 5: Pull Requests & Merge Operations

Created pull requests and merged both branches into the `main` branch.

The commit history clearly shows:
- Merge commits
- Branch updates
- Complete history

## 📷 Output

<img width="979" height="1136" alt="image" src="https://github.com/user-attachments/assets/912f0020-8a03-499f-9fd0-3be231b62cda" />

---

# 📄 Step 6: Products File Before Reset

Before performing the reset operation, the `products.txt` file contained additional products such as:

- Pens
- Lens

## 📷 Output

<img width="979" height="742" alt="image" src="https://github.com/user-attachments/assets/9edb4359-b66d-44a1-ada6-24c3edd682cb" />

---

# ⏪ Step 7: Git Reset Operation

Executed the reset command to move `HEAD` back to the previous commit.

This temporarily removed the latest updates from the branch.

## 📷 Output

<img width="880" height="526" alt="image" src="https://github.com/user-attachments/assets/9bae3fde-ee02-4edc-a47a-ca18daa0e8ec" />

## 💻 Command Used

```bash
git reset --hard HEAD~1
```

---

# ↩️ Step 8: Git Revert Operation

Performed a revert operation on the previous commit.

Git created a new commit without deleting the existing commit history.

## 📷 Output

<img width="979" height="821" alt="image" src="https://github.com/user-attachments/assets/fd258113-e154-4f4c-8567-15e4788bbc24" />

## 💻 Command Used

```bash
git revert <commit-id>
```

Example:

```bash
git revert a1b2c3d
```

---

# ✅ Conclusion

This Git Mini Task successfully demonstrated:

- Git repository initialization
- Branch creation and management
- Commit and push operations
- Pull requests and merge operations
- Git reset command
- Git revert command

This project helped in understanding version control concepts and collaborative development practices using Git and GitHub.
