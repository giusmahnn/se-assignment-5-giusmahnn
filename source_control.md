### Using Source Control in VS Code

#### Integrating Git with VS Code

1. **Install Git:**
   - Ensure Git is installed on your local machine. Download and install it from [Git's official website](https://git-scm.com/downloads).

2. **Open VS Code and Install Git Extension:**
   - Open VS Code and install the Git extension if it’s not already installed. This extension is usually bundled with VS Code by default.

3. **Initialize a Git Repository:**
   - Open the project folder in VS Code.
   - Open the Source Control view by clicking the Source Control icon in the Activity Bar or using the shortcut `Ctrl+Shift+G`.

     ![Source Control Icon](![alt text](image-17.png))

   - Click on "Initialize Repository" button to create a new Git repository in your project folder.

     ![Initialize Repository](https://code.visualstudio.com/assets/docs/sourcecontrol/overview/initialize-repository.png)

4. **Staging Changes:**
   - Make changes to your project files.
   - In the Source Control view, you will see the list of changed files. Click the `+` icon next to each file to stage the changes, or click on the `+` next to Changes to stage all changes.

     ![Stage Changes](https://code.visualstudio.com/assets/docs/sourcecontrol/overview/stage-changes.png)

5. **Committing Changes:**
   - After staging your changes, enter a commit message in the message box at the top of the Source Control view.
   - Click on the checkmark icon (✓) to commit the changes.

     ![Commit Changes](https://code.visualstudio.com/assets/docs/sourcecontrol/overview/scm-git-editor.gif)

6. **Connecting to GitHub:**
   - Create a GitHub account if you don’t already have one at [GitHub](https://github.com).
   - On GitHub, create a new repository by clicking the `+` icon in the top right corner and selecting "New repository."

     ![New Repository](https://docs.github.com/assets/images/help/repository/repo-create-quick-setup.png)

   - Copy the repository URL (e.g., `https://github.com/username/repository.git`).

7. **Adding a Remote Repository:**
   - In VS Code, open the integrated terminal by selecting `View` > `Terminal` or using the shortcut `` Ctrl+` ``.
   - Add the GitHub repository as a remote by running:
     ```sh
     git remote add origin https://github.com/username/repository.git
     ```

8. **Pushing Changes to GitHub:**
   - Push your committed changes to GitHub using the command:
     ```sh
     git push -u origin master
     ```

     ![Push to GitHub](![alt text](image-18.png))

9. **Pulling Changes from GitHub:**
   - To pull changes from the GitHub repository, use:
     ```sh
     git pull origin master
     ```

#### Advantages of Using Source Control with VS Code
- **Integrated Workflow:** Manage your Git repositories directly within VS Code without needing to switch to an external Git client.
- **Visual Diff and Merge Tools:** Easily view and resolve merge conflicts using the built-in diff and merge tools.
- **Source Control Integration:** Seamlessly integrate with other VS Code features, like the integrated terminal, extensions, and debugging tools.

---

**References:**
- [VS Code Documentation: Version Control](https://code.visualstudio.com/docs/editor/versioncontrol)
- [GitHub Docs: Connecting to GitHub](https://docs.github.com/en/github/using-git/connecting-to-github)