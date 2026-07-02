# Version Control with Git — Mini Project

**Student Name:** [Your Name]
**Roll Number:** [Your Roll Number]
**Course:** B.Tech, Information Technology — 4th Semester
**College:** [Your College Name]
**Subject:** [Subject Name, e.g., Software Engineering / IT Workshop]
**Guide/Faculty:** [Faculty Name]

---

## 1. Objective

The objective of this project is to understand and practically demonstrate the fundamentals of **Version Control Systems (VCS)** using **Git**, a distributed version control tool, along with **GitHub** as a remote repository hosting platform. The project covers repository creation, tracking changes, branching, merging, and collaborating through a remote repository.

## 2. Introduction

Version control is a system that records changes to a file or set of files over time so that specific versions can be recalled later. It allows multiple developers to work on a project simultaneously without overwriting each other's changes, and it maintains a complete history of who changed what and when.

**Git** is a free, open-source, distributed version control system created by Linus Torvalds in 2005. Unlike centralized systems, every developer's working copy of the code is also a repository that contains the full history of all changes.

**GitHub** is a cloud-based hosting service for Git repositories, enabling remote storage, collaboration, and sharing of code.

## 3. Tools Used

| Tool | Purpose |
|------|---------|
| Git | Local version control |
| GitHub | Remote repository hosting |
| Git Bash / Terminal | Command-line interface for Git operations |

## 4. Key Concepts Demonstrated

- **Repository** — a folder tracked by Git that stores project files and their complete history.
- **Staging Area** — an intermediate area where changes are placed before committing.
- **Commit** — a snapshot of changes saved to the repository history.
- **Branch** — an independent line of development, allowing work without affecting the main codebase.
- **Merge** — combining changes from one branch into another.
- **Remote Repository** — a version of the project hosted on GitHub, allowing sharing and collaboration.

## 5. Steps Performed

### Step 1: Initialize the repository
```bash
git init
```
Initializes a new, empty Git repository in the project folder.

### Step 2: Add project files
```bash
git add notes.txt
git add README.md
```
Stages the files, marking them to be included in the next commit.

### Step 3: Commit the changes
```bash
git commit -m "Initial commit: added notes.txt and README.md"
```
Saves a snapshot of the staged changes to the repository's history.

### Step 4: Create a new branch
```bash
git branch feature-update
git checkout feature-update
```
Creates and switches to a new branch called `feature-update`, used to work on changes independently of the main branch.

### Step 5: Make changes on the feature branch
Edited `README.md` on the `feature-update` branch to reflect new content, then committed the change:
```bash
git add README.md
git commit -m "Updated README from feature branch"
```

### Step 6: Merge the feature branch into master
```bash
git checkout master
git merge feature-update
```
Merges the changes made in `feature-update` back into the `master` branch.

### Step 7: Connect to a remote repository (GitHub)
```bash
git remote add origin https://github.com/akhi-mohammmed-o7/DevOps_prj.git
```

### Step 8: Push changes to GitHub
```bash
git push -u origin master
```
Uploads the local commit history to the remote GitHub repository.

## 6. Repository Link

[https://github.com/akhi-mohammmed-o7/DevOps_prj](https://github.com/akhi-mohammmed-o7/DevOps_prj)

## 7. Screenshots

*(Insert screenshots here: terminal output of `git log`, `git branch`, GitHub commit history/network graph, and the repository page.)*

- Screenshot 1: `git init` and `git commit` output
- Screenshot 2: `git branch` and `git checkout` output
- Screenshot 3: `git merge` output
- Screenshot 4: GitHub repository page showing commit history

## 8. Conclusion

Through this project, the fundamentals of Git and GitHub were understood and practically implemented. Key operations such as initializing a repository, staging and committing files, creating and switching branches, merging branches, and pushing to a remote repository were performed successfully. This project demonstrates the importance of version control in maintaining organized, traceable, and collaborative software development workflows.

## 9. References

- Git Official Documentation — https://git-scm.com/doc
- GitHub Docs — https://docs.github.com