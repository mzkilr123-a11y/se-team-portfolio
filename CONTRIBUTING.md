# 🤝 Contributor Guide for Team Members

Welcome to our team repository! Follow these simple steps to upload your assignments and update your profile without running into git issues.

---

### Step 1: Clone the Repo
```bash
git clone https://github.com/mzkilr123-a11y/se-team-portfolio.git
cd se-team-portfolio
```

---

### Step 2: Set Up Your Student Folder (First Time Only)
1. Copy the `students/_template` folder.
2. Rename it to `students/your-name` (e.g., `students/omar-ali`).
3. Open `students/your-name/README.md` and update your full name, student ID, and info.
4. Add your row to the main table in `README.md`.

---

### Step 3: Add Your Tasks
Whenever a doctor assigns a task:
1. Create a folder inside `students/your-name/tasks/` (e.g. `task-01-html/`).
2. Add your code files (`index.html`, `main.cpp`, etc.).
3. Update your task table inside `students/your-name/README.md`.

---

### Step 4: Commit and Push
Always pull before pushing to get teammates' latest updates:

```bash
git pull origin main
git add .
git commit -m "Add Task 02: [Your Name]"
git push origin main
```

> ⚠️ **Golden Rule:** Only add/edit files inside your own `students/your-name/` directory! Never edit a teammate's directory.
