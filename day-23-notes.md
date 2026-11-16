1. CLONE WILL CREATE A COPY OF THE PROJECT FROM THE MAIN REPO
FORK WILL CREATE A COPY IN THE PERSONAL GITHUB ACCOUNT

2.When to use which?

Clone: Use this when you are part of a team and already have write/push access to the repository, or when you simply want to download the code to run or inspect it locally.

Fork: Use this when you want to contribute to a repository where you do not have write access (like open-source projects). You fork the repo to your account, clone your fork locally, make your changes, and submit a "Pull Request" to the original project.

3.Keeping a Fork in Sync

After forking and cloning your fork locally, you will eventually need to pull in new updates that were made to the original repository.

Command

Description

git remote add upstream <original-repo-url>

Link the original repository (name it 'upstream')

git fetch upstream

Download the latest changes from the original repository

git checkout main

Ensure you are on your local main branch

git merge upstream/main

Merge the original repository's changes into your local branch

git push origin main

Push the newly synced code up to your remote fork
