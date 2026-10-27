# 🎓 Software Engineering Team Portfolio & Coursework Repository

Welcome to the collaborative portfolio repository for our academic team at **Suez Canal University** (Faculty of Computers & Informatics).

> **Program:** Software Engineering — Year 2  
> **Section:** Section 1  
> **Purpose:** Centralized showcase for instructors, doctors, and team members to track individual & collaborative assignments, lab submissions, and term projects.

---

## 👥 Team Directory & Member Portfolios

Each team member maintains a dedicated directory under [`students/`](students/) containing their personal bio, profile, and coursework submissions.

| Student Name | Academic Role / Focus | GitHub Username | Portfolio Directory |
| :--- | :--- | :--- | :--- |
| **Ahmad Mohamed Said Mansour** (Team Lead) | Software Engineering / Automation / LLMs | [@mzkilr123-a11y](https://github.com/mzkilr123-a11y) | [Ahmad Mansour's Portfolio](students/ahmad-mansour/) |
| **Ahmad Nashat** | Software Engineering | *Pending* | [Ahmad Nashat's Portfolio](students/ahmad-nashat/) |
| *Teammate 3* | Software Engineering | *Pending* | [students/teammate-3/](students/) |
| *Teammate 4* | Software Engineering | *Pending* | [students/teammate-4/](students/) |

---

## 📂 Repository Architecture

To prevent merge conflicts and keep everyone's tasks cleanly separated, this repository follows a clean folder structure:

```text
se-team-portfolio/
│
├── students/                     # Dedicated folders for each student
│   ├── ahmad-mansour/            # Student folder
│   │   ├── README.md             # Student bio, details & task table
│   │   └── tasks/                # Personal tasks & assignments
│   │       ├── web-development/
│   │       └── cplusplus/
│   │
│   ├── [teammate-name]/          # Teammates duplicate the template folder
│   │   ├── README.md
│   │   └── tasks/
│   │
│   └── _template/                # Copy-paste template for new teammates
│       ├── README.md
│       └── tasks/
│
├── shared-projects/              # Group/team projects submitted together
│   └── README.md
│
└── CONTRIBUTING.md               # Quick instructions for teammates on how to push
```

---

## 🚀 Guide for Team Members (How to Add Your Work)

1. **Clone this repository:**
   ```bash
   git clone https://github.com/mzkilr123-a11y/se-team-portfolio.git
   ```
2. **Create your folder:**
   Copy `students/_template` and rename it to `students/your-name/`.
3. **Add your tasks:**
   Place your code, markdown, or HTML task files inside `students/your-name/tasks/`.
4. **Push your changes:**
   ```bash
   git add .
   git commit -m "Add Task 01 for [Your Name]"
   git push origin main
   ```

---

## 📌 Access & Permissions

- **For Evaluators & Doctors:** The repository is **Public** — accessible anytime from any browser without requiring an account.
- **For Team Members:** Members invited as **Collaborators** have direct write/push access to submit their tasks.
- **Safety Rule:** Every student works inside their own `students/[name]/` folder to ensure nobody overwrites anyone else's code!
