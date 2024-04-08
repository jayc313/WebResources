
## Branching Strategy
- **Master Branch:** Contains production-ready code.
- **Develop Branch:** For ongoing development.
- **Feature Branches:** Each developer creates a feature branch for individual tasks.

## Pull Requests
- Create pull requests from feature branches to the develop branch.
- GitHub notifies about conflicts during the pull request process.

1. **Initialize a Git repository:**
   - Open GitHub Desktop.
   - Click on "File" in the menu bar.
   - Select "Add Local Repository" and choose your WordPress theme directory.
   - Click on "Add Repository".

2. **Create a new branch:**
   - In GitHub Desktop, click on the "Current Branch" dropdown menu.
   - Type a name for your new branch (e.g., "feature/new-feature") and press Enter.
   - Click on "Create Branch".

3. **Make changes to your theme:**
   - Use your preferred code editor to make changes to your theme files.

4. **Stage your changes:**
   - In GitHub Desktop, you'll see your modified files listed under "Changes".
   - Check the box next to the files you want to include in the commit to stage them.

5. **Commit your changes:**
   - Enter a descriptive summary and optional description of your changes in the "Summary" and "Description" fields.
   - Click on "Commit to <branch name>".

6. **Push changes to a remote repository:**
   - After committing your changes, click on "Push origin" to push your branch and changes to the remote repository.

7. **Review and merge changes:**
   - If you're working with a team, navigate to your repository on GitHub's website.
   - Click on "Pull Requests" and then "New Pull Request".
   - Choose your branch and the branch you want to merge your changes into.
   - Click on "Create Pull Request" and follow the prompts to review and merge your changes.

8. **Update your local repository:**
   - In GitHub Desktop, click on "Fetch origin" to fetch any changes from the remote repository.
   - Click on "Pull origin" to update your local branch with the latest changes from the remote repository.

9. **Delete your feature branch:**
   - After merging your changes on GitHub's website, you can delete your feature branch in GitHub Desktop by clicking on "Branch" > "Delete" and selecting your feature branch.