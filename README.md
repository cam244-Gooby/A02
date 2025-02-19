# A02

Part 1: Directions on Using WebStorm

Step 1: Install WebStorm

Download WebStorm from JetBrains: https://www.jetbrains.com/webstorm/download/

Install WebStorm by following the installation prompts for your operating system.

Step 2: Install Git

Download Git from https://git-scm.com/downloads

Follow the installation process and configure Git with the following commands:

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

Step 3: Set Up Git in WebStorm

Open WebStorm and navigate to File > Settings > Version Control > Git.

Click Test to ensure WebStorm recognizes Git.

If necessary, set the path to the Git executable (git.exe on Windows, /usr/bin/git on macOS/Linux).

Step 4: Create a New Project and Initialize Git

Open WebStorm and select New Project.

Choose a template or start with an empty project.

Open the terminal in WebStorm and initialize Git:

git init

Create a .gitignore file to exclude unnecessary files from version control.

Step 5: Connect to GitHub

Create a GitHub account at https://github.com.

Generate a personal access token (PAT) from GitHub under Settings > Developer settings > Personal access tokens.

In WebStorm, navigate to File > Settings > Version Control > GitHub.

Add your GitHub account using your username and the generated token.

Step 6: Create a Repository and Make First Commit

On GitHub, create a new repository.

In WebStorm’s terminal, add the remote repository:

git remote add origin https://github.com/yourusername/yourrepository.git

Stage and commit your files:
Ex.
git add .
git commit -m "Initial commit"

Push changes to GitHub:

git push -u origin main

Step 7: Working with Branches and Merging

Create a new branch:

git branch new-feature
git checkout new-feature

Make changes, commit, and push:
Ex.
git add .
git commit -m "Feature: Added new functionality"
git push origin new-feature

Merge the branch into the main branch:
Ex.
git checkout main
git merge new-feature

Resolve any Merge Conflict manually if needed.

Push the merged changes:
Ex.
git push origin main

Step 8: Cloning a Repository

In WebStorm, select Get from VCS.

Enter the GitHub repository URL and clone it.

Use git pull to fetch the latest changes:

git pull origin main

Step 9: Fetching and Pulling Changes

To fetch the latest changes without merging:

git fetch origin

To fetch and merge changes:

git pull origin main

Part 2: Glossary

Branch: A separate line of development within a repository.

Clone: A copy of a Git repository stored on a local machine.

Commit: A recorded snapshot of changes in a repository.

Fetch: The process of retrieving changes from a remote repository without merging them.

GIT: A distributed version control system for tracking changes in source code.

GitHub: A web-based platform for hosting and managing Git repositories.

Merge: The process of combining changes from different branches.

Merge Conflict: A conflict that occurs when changes from different branches affect the same file in incompatible ways.

Push: Sending committed changes to a remote repository.

Pull: Fetching changes from a remote repository and merging them into the local branch.

Remote: A version of a repository stored on a server, like GitHub.

Repository: A storage location for a project's files and version history.

References

JetBrains WebStorm Documentation: https://www.jetbrains.com/webstorm/documentation/

Git Documentation: https://git-scm.com/doc

GitHub Docs: https://docs.github.com

PowerPoints: IS117-Version5-AllSlides.pdf
