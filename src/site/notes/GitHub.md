---
{"dg-publish":true,"permalink":"/git-hub/","dg-note-properties":{}}
---

see[[Agentic AI\|Agentic AI]]

What is GitHub? 
GitHub is a cloud-based platform that helps developers store, manage, track, and collaborate on software projects using Git, a version control system.
Think of it like Google Drive for source code, but with powerful features for tracking changes, collaborating with teams, and managing software development.

**GitHub Workflow Diagram**

```text
                 Developer A
                      │
              Create/Edit Code
                      │
                  Git Commit
                      │
                   Git Push
                      │
          ┌─────────────────────┐
          │       GitHub        │
          │  Online Repository  │
          └─────────────────────┘
              ▲             │
              │             │
          Git Pull      Pull Request
              │             │
         Developer B    Code Review
                            │
                          Merge
                            │
                     Updated Project
```

**How GitHub Works**

1. **Create a Repository**  
- A repository (repo) is a folder that contains your project files and their history.

2. **Write Code**
- You develop your application on your computer.

3. **Commit Changes**
- Save a snapshot of your work with a message.
- Example:
   Added Login Screen
   
4. **Push to GitHub**
- Upload your latest commits to GitHub.

5. **Collaborate**
- Other developers can download (pull) the project, make changes, and contribute.

6. **Pull Request (PR)**
- Request that your changes be reviewed before they are merged into the main project.

7. **Merge**
- After approval, the changes become part of the main codebase.

---

**Main Components of GitHub**

|Component|Purpose|
|---|---|
|Repository|Stores project files and history|
|Commit|Saves a snapshot of changes|
|Branch|Separate workspace for new features or fixes|
|Pull Request|Requests review before merging changes|
|Merge|Combines approved changes into the main branch|
|Issues|Tracks bugs, tasks, and feature requests|
|Actions|Automates tasks such as testing and deployment|
|Wiki|Project documentation|

---

**Git vs GitHub**

| Git                        | GitHub                                          |
| -------------------------- | ----------------------------------------------- |
| Version control software   | Cloud hosting platform                          |
| Installed on your computer | Accessed through a web browser or Git client    |
| Tracks file changes        | Stores Git repositories online                  |
| Works offline              | Requires internet for syncing and collaboration |
| Created by Linus Torvalds  | Owned by Microsoft                              |

---

**Why Developers Use GitHub**

- ✔ Backup code securely in the cloud.

- ✔ Work with teams on the same project.

- ✔ Track every change and restore older versions.

- ✔ Review code before merging.

- ✔ Automate testing and deployment.

- ✔ Showcase projects as a portfolio.

**Example**

Suppose you are building your **BusyApp ERP** project.

```
BusyApp ERP
│
├── Login Module
├── Sales Module
├── Purchase Module
├── Inventory Module
├── Reports
└── Database
```

Using GitHub, you can:
- Save every version of your ERP.
- Create a separate branch for each module.
- Merge completed modules into the main project.
- Revert to an earlier version if a bug is introduced.
- Collaborate with other developers if needed.

---
**Summary**

- **GitHub** is a cloud-based platform for **hosting and managing code**.
- It uses **Git**, a version control system, to track changes in files.
- Developers use GitHub to **store projects, collaborate, review code, and maintain version history**.
- It supports features such as **Repositories**, **Commits**, **Branches**, **Pull Requests**, and **GitHub Actions**.
- GitHub makes teamwork easier by allowing multiple developers to work on the same project without overwriting each other's changes.

**Simple Diagram**
```text
Developer
    │
Write Code
    │
 Git Commit
    │
 Git Push
    │
 ┌──────────────┐
 │    GitHub    │
 │ Repository   │
 └──────────────┘
    │
 Git Pull
    │
Other Developers
```

