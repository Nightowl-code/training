# Git Collaboration Game – 2 Person Activity

This repository is a **hands-on Git learning activity** designed for **2 participants** to practice real-world Git collaboration concepts such as branching, merging, conflicts, pull requests, and git stash.

---

## 👥 Roles

- **Person A** → Developer  
- **Person B** → Team Lead / Repository Owner  

---

## 📌 Assumptions

- Repository name: `fintech-app`
- Default branch: `main`
- Both users have:
  - Git installed
  - GitHub / GitLab accounts

---

## 🧩 Phase 1 — Project Birth

### Step 1: Developer A creates project locally
```bash
mkdir fintech-app
cd fintech-app
echo "FinTech App - Initial Version" > README.md
echo "console.log('Hello FinTech');" > app.js
git init
git add .
git commit -m "Initial local project setup"
```

### Step 2: Team Lead B creates remote repository