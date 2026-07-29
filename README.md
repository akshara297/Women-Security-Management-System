# 🚀 Mini-Project Repository Guide

Welcome to our project repository! This document outlines the standard workflow and guidelines for all 4 team members to collaborate smoothly without breaking the code.

---

## 🛠️ 1. Initial Setup (Do this once)

If you haven't cloned the repository to your local machine yet:

1. Open your terminal or command prompt.
2. Clone the repository:
   ```bash
   git clone <repository-link>
## 2.Move into the project directory:
Move into the project directory: 

    cd mini-project
    
## 3.Daily Coding Workflow
To prevent losing work or creating messy conflicts, always follow this exact sequence every time you sit down to code:

Step A: Pull the latest updates FIRST
Before writing any code, make sure you have the most up-to-date version of the project from your teammates:

    git pull origin main
    
Step B: Write your code
Make your changes, add new files, or fix bugs in your local code editor (e.g., VS Code). Try to coordinate with the team so you aren't all editing the exact same file at the same time.

Step C: Stage your changes
Check which files you modified (git status), then stage them for saving:  

    git add .

Step D: Commit your changes
Save your staged changes locally with a clear message describing what you did:

    git commit -m "Short description of what you changed (e.g., Added footer component)"

Step E: Push your code to GitHub
Upload your saved changes so the rest of the team can access them:


   git push origin main

   
## 4.Best Practices to Avoid Merge Conflicts
Communicate: Let the group know in your chat what section or file you are currently working on (e.g., "Hey, I'm working on styles.css right now").

Pull Often: Run git pull frequently, especially right before you start working and right before you try to push your code.

Keep Commits Small: Push your code often in small, working chunks rather than saving a massive block of changes all at once.
