1. Setup & Configuration
Command	Description
git --version	Check Git version
git config --global user.name "Your Name"	Set username
git config --global user.email "you@example.com"	Set email
git config --list	View all configurations
git init	Initialize a Git repository
git clone <url>	Clone a remote repository

REVIEWED SETUP AND CONFIG COMMANDS

2. Basic Workflow
Command	Description
git status	Check repository status
git add <file>	Stage a specific file
git add .	Stage all changes
git commit -m "message"	Commit staged changes
git push	Upload commits to remote
git pull	Fetch and merge changes
git fetch	Download remote updates
git log	View commit history
git diff	View unstaged changes

3. Viewing Changes
Command	Description
git status	Show modified and staged files
git diff	Show unstaged changes
git diff --staged	Show staged changes
git log --oneline	Show compact commit history
git log --oneline --graph	View graphical commit history
git show	Display details of the latest commit
git show <commit-id>	View a specific commit

REVIEWED BASIC WORK FLOW AND VIEWING CHANGES COMMANDS

4. Branching & Merging
Command	Description
git branch	List branches
git branch <name>	Create a branch
git switch <name>	Switch branches
git switch -c <name>	Create and switch branch
git merge <branch>	Merge a branch
git branch -d <name>	Delete a branch
git branch -a	List all local and remote branches


5. Undoing Changes
Command	Description
git restore <file>	Discard unstaged changes
git restore --staged <file>	Unstage a file
git reset --soft HEAD~1	Undo last commit, keep staged changes
git reset --hard HEAD~1	Remove last commit and changes
git revert <commit-id>	Create a commit that reverses another commit

6. Remote Repository
Command	Description
git remote -v	View remote repositories
git remote add origin <url>	Add remote repository
git remote remove origin	Remove remote
git push -u origin main	Push and set upstream
git push origin <branch>	Push a specific branch

Reviewed Branching & Merging,undoing and remote repo commands

7. Stashing
Command	Description
git stash	Temporarily save changes
git stash list	View stashes
git stash pop	Restore and remove latest stash
git stash apply	Restore latest stash without removing it
git stash drop	Delete latest stash 
