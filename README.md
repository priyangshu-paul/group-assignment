
# creating latex repo on GitHub

Step 1: Set Up a GitHub Repository

1. Create a New Repository:
i. Go to GitHub.
ii. Click on the New button in the top-right corner of the page.
iii. Enter a repository name, e.g., my-latex-project.
iv. Add a description if desired.
v. Choose whether the repository will be public or private.
vi. Optionally, initialize the repository with a README.md file and a .gitignore file (you can choose the LaTeX template for the .gitignore).
vi. Click Create repository.


Step 2: Set Up Your Local Environment

1. Install Git:
i. If you haven't already, install Git on your local machine. You can download it from Git's official website.

2. Install LaTeX:
ii. Ensure you have a LaTeX distribution installed, such as TeX Live or MiKTeX.


Step 3: Clone the Repository Locally

1. Clone the Repository:
i. Open a terminal (Command Prompt, Git Bash, etc.).
ii. Clone the repository to your local machine: git clone https://github.com/your-username/my-latex-project.git
iii. Navigate into your project directory: cd my-latex-project


Step 5: Commit and Push Changes

1. Add Files to Git:
i. After creating or modifying your LaTeX files, add them to your Git repository: git add .

2. Commit Your Changes:
i. Commit the changes with a message: git commit -m "Initial commit with LaTeX files"

3. Push to GitHub:
i. Push the changes to your GitHub repository: git push origin main


Step 6: Collaborate and Update

1. Collaborate:
i. Share the repository link with collaborators. They can clone the repo, make changes, and push updates.

2. Pull Updates:
i. Regularly pull updates to keep your local repository in sync: git pull origin main

