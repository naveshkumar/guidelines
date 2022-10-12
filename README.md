# guidelines
a guideline to setting up new repo and syncing R with github
follow link in below instructions website

pasting the content if at all its gone for some reason

https://jennybc.github.io/2014-05-12-ubc/ubc-r/session2.4_github.html

Getting Started with GitHub
Register an educational GitHub account if you qualify, and a regular account otherwise
A GitHub educational account gives you five private repositories for free
Public repositories are always free
Upload a photo of your self to Gravatar if you're comfortable with that
GitHub Documentation
GitHub has great documentation on both git and GitHub.

GitHub Help
Set Up Git
Create a Repository
Fetching a Remote
Set up git
Configure your name and email address if you haven't already.

Open a terminal and run…

git config --global user.name "Your Name Here"
git config --global user.email "your_email@example.com"
On a Mac, also run…

git config --global credential.helper osxkeychain
GitHub has more detailed instructions on setting up git.

Create a new RStudio project on GitHub
Open GitHub in your web browser
Create a new repository
Enter a name and description
Check Initialize this repository with a README
Click Create repository
Copy the repository URL of your project to the clipboard by clicking the Copy to clipboard icon next to HTTPS clone URL on the right-hand side of the project page
Open RStudio
Create a new project
Click File -> New Project -> Version Control -> Git
Paste the repository URL from the clipboard into Repository URL
Click Create Project
Stage the files .gitignore and project.Rproj
Commit these files and push them to GitHub
Click Commit
Click Pull and it should respond Already up to date
Enter a log message and click Commit
Click Push
Get in the habit of always clicking Pull before commit
It will prevent conflicts and save you grief
Reload this repository in your web browser and look for these two files
Edit README.md and add an informative title and description
Commit README.md
Push this commit to GitHub (remember to pull first!)
Reload this repository in your web browser and appreciate your beautifully rendered README.md


Push an existing RStudio project to GitHub
Open GitHub in your web browser
Create a new repository
Give the repository the same name as your RStudio project
Do not check Initialize this repository with a README
Click Create Project
Copy the two lines of code from the box labeled Push an existing repository from the command line
Open an existing project in RStudio
Look for the Git tab to ensure it's already using git
Open a shell by clicking Tools -> Shell
Paste the two lines of code that you copied into the shell

git remote add origin https://github.com/USERNAME/PROJECT.git
git push -u origin master
Reload this repository in your web browser and browse through your handiwork

Click on individual files to see their content
Click on commits to see your history of commits
Push your project to GitHub

Click More -> Push Branch
Edit README.md and commit the change

Remember the mantra: pull, commit, push
Reload this repository in your web browser and look for your recent change

In your GitHub web browser, edit the file README.md

Click on README.md
Click Edit and make a change
Click Commit changes
In RStudio, pull this change from GitHub

Click More -> Pull Branches
Look for your recent change in RStudio
