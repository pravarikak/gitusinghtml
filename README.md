Initialize the Local Repository

git init


Add Files to the Repository

git add .

Commit Your Changes

git commit -m "Initial commit" # Use an appropriate commit message


Set Up the Remote Repository

git remote add origin https://github.com/<your-username>/<repository-name>.git

git remote add origin https://pravarikak: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@github.com/pravarikak/testing.git


Push the Changes to GitHub

git push -u origin master # Use 'main' if your default branch is 'main'

Create a New Branch

git checkout master # Switch to master if you're not already on it

git pull origin master # Make sure you have the latest changes from the remote master

git checkout -b new-branch-name # Create and switch to a new branch

Make Changes and Commit Them
Now that you're on the new branch, make your changes (edit files, create new files, etc.). After making the changes, add the changes to the staging area:

git add . # Stage all modified and new files 

git commit -m "Commit message describing changes" # Commit your changes


Push the New Branch to GitHub

git push -u origin new-branch-name # Push the new branch to GitHub

Switch to the master Branch

git checkout master # Switch to master branch 

git pull origin master # Pull the latest changes from the remote master

Merge the New Branch into master

git merge new-branch-name # Merge your new branch into master

Push the Merged Changes to master

git push origin master # Push changes to the master branch on GitHub
