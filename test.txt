📌 Introduction to Git & GitHub
🔹 What is Git?
Git is a distributed version control system (VCS) that tracks changes in source code, helps in collaboration, and enables software development with multiple contributors.
✅ Why Use Git?
•	Tracks every change in your project
•	Allows multiple developers to work on the same codebase
•	Provides backup and version control
•	Helps in collaborating on open-source projects
________________________________________
🔹 What is GitHub?
GitHub is a cloud-based Git repository hosting service that stores Git repositories, enables team collaboration, and provides tools like Pull Requests, Issues, CI/CD, and GitHub Actions.
✅ Why Use GitHub?
•	Store and manage repositories
•	Collaborate with teams on projects
•	Track changes & review code
•	Host websites using GitHub Pages
•	Automate workflows with GitHub Actions
________________________________________
📌 Git Setup & Configuration
🔹 Step 1: Install Git
✅ Windows
Download & install Git from: https://git-scm.com/downloads
✅ Linux (Ubuntu/Debian)
bash
CopyEdit
sudo apt update && sudo apt install git -y
✅ MacOS
bash
CopyEdit
brew install git
🔹 Check if Git is installed
bash
CopyEdit
git --version
________________________________________
🔹 Step 2: Configure Git (First-Time Setup)
Before using Git, set up your name and email:
bash
CopyEdit
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
✅ Check your configuration
bash
CopyEdit
git config --list
________________________________________
📌 Git Basics: Essential Commands
📝 Step 1: Initialize a Git Repository
Create a new Git project:
bash
CopyEdit
git init
This creates a hidden .git folder where Git stores all changes.
________________________________________
📝 Step 2: Add Files to Staging
Before committing, add files to the staging area:
bash
CopyEdit
git add <file>        # Add a specific file
git add .             # Add all files
✅ Check status of files
bash
CopyEdit
git status
________________________________________
📝 Step 3: Commit Changes
A commit saves changes with a message:
bash
CopyEdit
git commit -m "Initial commit"
✅ View commit history
bash
CopyEdit
git log
________________________________________
📝 Step 4: Connect Local Repository to GitHub
1️⃣ Create a repository on GitHub
2️⃣ Add GitHub as a remote repository
bash
CopyEdit
git remote add origin https://github.com/yourusername/repository.git
3️⃣ Push changes to GitHub
bash
CopyEdit
git push -u origin main
________________________________________
📝 Step 5: Clone an Existing Repository
To copy a repository from GitHub to your local system:
bash
CopyEdit
git clone <repo_url>
________________________________________
📝 Step 6: Branching & Merging
Branches allow multiple developers to work independently.
✅ Create a new branch
bash
CopyEdit
git branch new-feature
✅ Switch to a branch
bash
CopyEdit
git checkout new-feature
✅ Merge a branch into main
bash
CopyEdit
git checkout main
git merge new-feature
✅ Delete a branch after merging
bash
CopyEdit
git branch -d new-feature
________________________________________
📝 Step 7: Pushing & Pulling Changes
✅ Push changes to GitHub
bash
CopyEdit
git push origin main
✅ Pull latest changes from GitHub
bash
CopyEdit
git pull origin main
✅ Fetch latest changes without merging
bash
CopyEdit
git fetch origin
________________________________________
📌 Hands-On Projects: Practical Exercises
📌 Project 1: Personal Notes Repository
Objective: Create a GitHub repository for personal notes and practice Git commands.
✅ Steps:
1️⃣ Create a repository on GitHub (e.g., my-notes).
2️⃣ Clone it to your system:
bash
CopyEdit
git clone https://github.com/yourusername/my-notes.git
3️⃣ Add notes as text files:
bash
CopyEdit
echo "Git is awesome!" > git-notes.txt
git add git-notes.txt
4️⃣ Commit and push:
bash
CopyEdit
git commit -m "Added Git notes"
git push origin main
________________________________________
📌 Project 2: Build & Deploy a Portfolio Website
Objective: Use GitHub Pages to host a personal portfolio.
✅ Steps:
1️⃣ Create a new repository on GitHub (e.g., my-portfolio).
2️⃣ Clone the repository:
bash
CopyEdit
git clone https://github.com/yourusername/my-portfolio.git
3️⃣ Create a basic index.html file and track it with Git:
html
CopyEdit
<html>
  <head><title>My Portfolio</title></head>
  <body>
    <h1>Welcome to My Portfolio</h1>
  </body>
</html>
4️⃣ Add, commit, and push changes:
bash
CopyEdit
git add .
git commit -m "Added portfolio website"
git push origin main
5️⃣ Enable GitHub Pages:
•	Go to Repository → Settings → Pages
•	Select main branch and save
•	Access your site at https://yourusername.github.io/my-portfolio/
________________________________________
📌 Project 3: Collaborative Teamwork (Pull Requests & Forking)
Objective: Learn to contribute to open-source projects.
✅ Steps:
1️⃣ Fork an open-source repository on GitHub.
2️⃣ Clone the forked repo:
bash
CopyEdit
git clone https://github.com/yourusername/project.git
3️⃣ Create a feature branch:
bash
CopyEdit
git checkout -b new-feature
4️⃣ Make changes, commit, and push:
bash
CopyEdit
git add .
git commit -m "Added new feature"
git push origin new-feature
5️⃣ Open a Pull Request on GitHub.
________________________________________
📌 Advanced Git & GitHub Concepts
🔹 Git Rebase – Rewrite commit history
🔹 Git Cherry-Pick – Apply specific commits
🔹 Git Hooks – Automate tasks before commit
🔹 GitHub Actions – Automate workflows
________________________________________
🔥 Summary: Steps to Master Git & GitHub
✅ Step 1: Learn basic commands (init, add, commit, push).
✅ Step 2: Work on personal projects (Notes, Portfolio).
✅ Step 3: Learn branching (checkout, merge, pull requests).
✅ Step 4: Contribute to open source.
✅ Step 5: Explore advanced topics (Rebase, GitHub Actions).

