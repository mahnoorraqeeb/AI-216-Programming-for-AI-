# Lab 01 – GitHub Setup & First Push

## Course
AI-216: Programming for Artificial Intelligence  
**Week 01**

---

## What this lab does

This lab focuses on setting up the core development toolchain used throughout the course.  
I created the official course GitHub repository, organized the required folder structure, added my first Python script, and practiced using Git for version control with meaningful commits and branches.

---

## Folder contents

- `hello_ai216.py`  
  A simple Python script that prints:
  - My name and student ID
  - The Python version being used
  - A short reflection on what Programming for AI means to me

- `README.md`  
  Documentation describing the lab tasks, learning outcomes, and Git workflow.

---

## Key Git commands used

- `git init`
- `git add .`
- `git commit -m "message"`
- `git push`
- `git branch`
- `git checkout -b week01-readme-improve`
- `git merge week01-readme-improve`
- `git remote add origin <repo-url>`

---

## What I learned

- How to initialize a Git repository and push it to GitHub
- How to create and merge branches using a basic feature-branch workflow
- How to structure a project repository in a clean and professional way
- Why writing clear README files is important for collaboration

---

## AI / ML relevance

Version control is essential in AI and ML workflows because:
- It ensures **reproducibility** of experiments and code
- It allows **safe experimentation** without breaking working models
- It supports **collaboration** when working in teams
- It provides **traceability** for model and code changes over time

---

## AI Usage Log

### 1. What does `.gitignore` do and why do we need it?

A `.gitignore` file tells Git which files or folders should not be tracked or committed to the repository.  
It is important because it prevents unnecessary or system-generated files (such as Python cache files, virtual environments, and editor settings) from cluttering the repository and causing conflicts.

---

### 2. README clarity review (AI suggestion summary)

Suggestions received:
- Add clear sections with headings
- Explicitly list learning outcomes
- Clearly connect Git usage to AI/ML workflows

These suggestions were applied in this README.

---

### 3. Script formatting & docstring suggestions

Suggestions received:
- Add a module-level docstring describing the script purpose
- Use clean labels for printed output
- Maintain consistent spacing and readable formatting

These improvements were applied to `hello_ai216.py`.

---

## Conclusion

This lab helped establish strong foundational habits for version control and documentation.  
These practices will be used throughout the course for labs, assignments, and the final AI project.
