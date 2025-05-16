```markdown
🧩 DevOps Task 04 - Git Version Control

 📌 Objective
This project demonstrates how to manage a DevOps project using **Git best practices**, including branching, pull requests, version tagging, and documentation.

---

 🛠 Tools Used
- **Git** – Distributed version control system
- **GitHub** – Remote repository hosting

---

 📁 Project Structure
```

devops-task-04/
├── .gitignore     # Ignored files and directories
├── README.md      # Project documentation
├── TASKS.md       # Task progress and summary
└── app.py         # Sample application file

````

---

 🚀 How to Run the Project
1. Make sure Python is installed.
2. Run the script:
   ```bash
   python app.py
````

Expected output:

```
Hello DevOps!
```

---

🔁 Git Workflow Summary
    ✅ Branches Used

* `main` – Production-ready branch
* `dev` – Development and testing branch
* `feature/add-login` – Example feature branch

    ✅ Git Commands Used

* `git init` – Initialize repo
* `git add .` / `git commit -m ""` – Track and commit changes
* `git branch` – Manage branches
* `git push` / `git pull` – Sync with GitHub
* `git tag` – Mark version releases

---

   🔀 Pull Request Process

1. Create a feature branch.
2. Push to GitHub.
3. Open a Pull Request from `feature/add-login` → `dev`.
4. Review and merge.
5. Later, merge `dev` → `main`.

---

 🏷 Versioning

* **v1.0** – Initial release with login feature added.

---

🧾 Task Summary

See [`TASKS.md`](TASKS.md) for a step-by-step breakdown of how the task was completed.

---
