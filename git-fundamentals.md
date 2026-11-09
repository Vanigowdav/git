# Day 1 – Git Fundamentals

**Course:** 15 Days of Git & GitHub  
**Day:** 01  
**Duration:** 30 Minutes  
**Tools:** VS Code, Git, VS Code Terminal

---

## 1. What is Git?

Git is a **Distributed Version Control System (DVCS)** used to track changes in source code and files.

It helps developers:
- Track changes in a project.
- Restore previous versions of code.
- Work with multiple developers.
- Manage different versions of a project.
- Collaborate using GitHub.

**Kannada Explanation:**

Git andre namma project alli aguva changes annu track maduva system.

Example: Nivu Python project create madtidira. Ondu dina code change madi mistake madidre, Git use madi previous version ge hogabahudu.

## 2. What is Version Control?

Version Control means keeping track of changes made to files over time.

Example:

```text
calculator.py
calculator_v1.py
calculator_v2.py
calculator_final.py
```

Instead of manually creating multiple copies, Git manages the versions for you.

## 3. What is a Repository?

A repository (repo) is a location where Git tracks and manages your project.

There are two important repository types:

1. **Local Repository:** Git repository stored on your computer.
2. **Remote Repository:** Repository hosted on a platform such as GitHub.

## 4. What is Git Workflow?

Git has three important areas:

### A. Working Directory

The place where you create, modify and delete files.

Example:

```text
git-15-days/
    main.py
```

Kannada: Nivu code bareyuva mattu changes maduva place.

### B. Staging Area

The place where you select changes that you want to include in your next commit.

Command:

```bash
git add main.py
```

Kannada: Commit maduva munche yav changes save madbeku anta select maduva step.

### C. Local Repository

The place where Git stores committed snapshots of your project.

Command:

```bash
git commit -m "Add main file"
```

Kannada: Staging area alli select madida changes annu commit moolaka repository ge save madutte.

## 5. Important Git Commands – Day 1

| Command | Purpose |
|---|---|
| `git --version` | Check installed Git version |
| `git init` | Initialize a new Git repository |
| `git status` | Check repository status |
| `git add filename` | Stage a particular file |
| `git commit -m "message"` | Create a commit |

**Note:** Day 1 primarily covers Git installation verification, repository initialization and understanding the workflow. Staging and committing will be practiced in detail on Day 3.

## 6. Practical – VS Code

### Step 1: Create a folder

```text
git-15-days
```

### Step 2: Open the folder in VS Code.

### Step 3: Open Terminal

Go to:

Terminal → New Terminal

### Step 4: Check Git installation

```bash
git --version
```

### Step 5: Initialize Git

```bash
git init
```

Expected result:

```text
Initialized empty Git repository
```

### Step 6: Check repository status

```bash
git status
```

This displays the current state of your repository.

## 7. Understand the Git Workflow

```text
Working Directory
       |
       | git add
       v
  Staging Area
       |
       | git commit
       v
 Local Repository
```

Remember:

- `git add` → Select changes.
- `git commit` → Save a snapshot.
- `git status` → Check current status.

## 8. Day 1 Interview Questions

**Q1. What is Git?**

Git is a distributed version control system used to track changes in source code.

**Q2. Why do developers use Git?**

To track code changes, manage versions, restore previous versions and collaborate with other developers.

**Q3. What is a repository?**

A repository is a storage location where Git tracks project files and their history.

**Q4. What is the difference between Git and GitHub?**

- Git is a version control tool.
- GitHub is a cloud-based platform used to host Git repositories and collaborate.

**Q5. What is `git init`?**

It initializes a new Git repository in the current directory.

**Q6. What is the difference between Working Directory and Staging Area?**

- Working Directory: Contains files you are editing.
- Staging Area: Contains selected changes ready for the next commit.

## 9. Day 1 Practice Checklist

- [ ] Verify Git installation.
- [ ] Create a project folder.
- [ ] Open the folder in VS Code.
- [ ] Open VS Code Terminal.
- [ ] Initialize a Git repository.
- [ ] Check repository status.
- [ ] Understand Working Directory.
- [ ] Understand Staging Area.
- [ ] Understand Local Repository.

---

## Day 1 Summary

Today we learned:

1. What Git is.
2. What Version Control means.
3. What a Git repository is.
4. Difference between Local and Remote repositories.
5. Three stages of Git workflow.
6. Basic Git commands.
7. How to initialize a repository using VS Code.

**Next Lesson: Day 2 – Git Configuration and Repository Management**