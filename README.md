# GitCertificate
<img src="https://github.com/Pavanreddyl/5215315_Levaku-Pavan-Kumar-Reddy/blob/main/351275CA-0D7B-4FEE-B9AB-BA2FCB8D37C0_1_201_a.jpeg" alt="My Image" />

<img src="https://github.com/Pavanreddyl/5215315_Levaku-Pavan-Kumar-Reddy/blob/main/Git%20Certificate%20by%20Simply%20Learn.jpeg" alt="My Image"/>
🔧 What is Git and GitHub?
Git: A version control system to track changes in your code.

GitHub: A cloud-based platform to store your Git repositories and collaborate with others.

📁 Uploading a Project to GitHub: Step-by-Step Guide
🧰 1. Prerequisites
You must have:

A GitHub account → github.com

Git installed on your system → git-scm.com

Your project folder ready

🖥️ 2. Initialize Git in Your Project
Open your terminal (or Git Bash), navigate to your project folder:

bash
Copy
Edit
cd path/to/your/project
Initialize Git:

bash
Copy
Edit
git init

📝 3. Add Your Files to Git
Check the status:

bash
Copy
Edit
git status
Add all files to staging:

bash
Copy
Edit
git add .
✅ 4. Commit Your Changes
Commit with a message:

bash
Copy
Edit
git commit -m "Initial commit"
🌐 5. Create a GitHub Repository
Go to https://github.com

Click + → New repository

Give it a name (e.g., my-project)

Do not initialize with README (since we already have files locally)

Click Create repository

🔗 6. Link Local Git Repo with GitHub Repo
Copy the repository URL (HTTPS or SSH). Example (HTTPS):

bash
Copy
Edit
git remote add origin https://github.com/your-username/my-project.git
To verify:

bash
Copy
Edit
git remote -v
🚀 7. Push Code to GitHub
Push your changes to the main (or master) branch:

bash
Copy
Edit
git push -u origin main
If it says branch not found, you might need to rename your local branch:

bash
Copy
Edit
git branch -M main
Then push again:

bash
Copy
Edit
git push -u origin main
🪄 Quick Commands Summary
Task	Command
Initialize Git	git init
Add files	git add .
Commit files	git commit -m "message"
Connect to GitHub	git remote add origin <repo-url>
Push to GitHub	git push -u origin main

📌 Tips for Better Git Usage
.gitignore: Create this file to ignore unwanted files/folders (e.g., .env, node_modules/)

README.md: Add documentation for your project

Branching: Use git branch <name> and git checkout for new features

GitHub Desktop: GUI-based Git client for beginners

📁 Example Directory Structure
perl
Copy
Edit
my-project/
├── index.html
├── style.css
├── script.js
├── README.md
└── .gitignore
