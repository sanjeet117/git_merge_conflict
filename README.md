# Git Merge Conflict Assignment

## Project Overview

This project demonstrates how Git handles a merge conflict when two branches modify the same line of the same file differently.

Two feature branches were created from the same base commit. Each branch modified the same line with different content. The first branch was merged successfully into `main`. When the second branch was merged, Git produced a merge conflict.

The conflict was manually resolved, tested, committed, and the complete Git history was pushed to GitHub.

---

## Assignment Objective

The objectives of this assignment are:

- Create two branches from the same base.
- Modify the same line of the same file differently in both branches.
- Merge the first branch into `main`.
- Attempt to merge the second branch and create a merge conflict.
- Inspect Git conflict markers.
- Understand why the conflict occurred.
- Resolve the conflict manually.
- Test the resolved code.
- Commit the conflict resolution.
- Push all branches to GitHub.
- Display the final Git history.

---

## Project Structure

```text
git_merge_conflict/
│
├── course.py
├── README.md
├── requirements.txt
└── .gitignore
