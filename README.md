# Add-project-on-github
This mini-guide will help you to add a project on Github:

1. Create a new repository on GitHub.
2. Open a command prompt and set the path where you want to save the folder.
3. To clone your GitHub repository on the local device, first copy the HTTPS URL of your newly created repo
   ```
   "git clone URL"
   ```
4. make changes in your project 
5. To update your changes on GitHub first Initialize the local directory as a Git repository.
   ```
   "git init"
   ```
6. Add the files to your new local repository. This stages them for the first commit.
   ```
   "git add ."
   ```
7. Commit the files that you’ve staged in your local repository.
   ```
   "git commit -m "commit message" "
   ```
8. Copy the HTTPS URL of your newly created repository
9. In the Command prompt, add the URL for the remote repository where your local repository will be pushed.
   ```
   "git remote add origin remote repository URL"
   ```
   ```
   "git remote -v"
   ```
10. Push the changes in your local repository to GitHub.
   ```
   "git push"
   ```
   OR

   "git push YOUR PERSONAL ACCESS TOKEN"

11. To generate personal access token
   -- Git Setting >> developer option >> Personal access token
