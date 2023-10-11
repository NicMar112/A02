# A02
Installing Git, GitHub, and WebStorm

Installing Git
1. Go to the official Git website at [https://git-scm.com/](https://git-scm.com/).
2. Download the Git installer for your specific operating system (Windows, macOS, or Linux).
3. Run the installer and follow the on-screen instructions.
4. During the installation, you can choose the default options unless you have specific preferences.
5. Open your terminal or command prompt and verify the Git installation by running the command: `git --version`.

Setting up a GitHub Account
1. Open your web browser and go to [https://github.com/](https://github.com/).
2. Click on the "Sign up" button to create a new GitHub account.
3. Follow the registration process, providing your username, email address, and password.
4. Complete the email verification process to activate your GitHub account.

Installing WebStorm
1. Go to the JetBrains WebStorm download page at [https://www.jetbrains.com/webstorm/download/](https://www.jetbrains.com/webstorm/download/).
2. Download the WebStorm installer for your operating system.
3. Run the installer and follow the on-screen instructions.
4. During the installation, you can choose the default options unless you have specific preferences.
5. Launch WebStorm after installation.

Configuring Git in WebStorm
1. Open WebStorm and click "Configure" in the welcome window.
2. Select "Version Control" and then "Git."
3. Set your name and email address for Git. This information will be associated with your commits.
4. Click "Test" to ensure WebStorm can locate the Git executable.

Cloning a Repository from GitHub**
1. In WebStorm, select "File" > "New" > "Project from Version Control" > "Git."
2. Enter the URL of the GitHub repository you want to clone.
3. Choose a directory where you want to save the local copy of the repository.
4. Click "Clone."

Making Your First Commit
1. Open a file in your new project.
2. Make changes to the file.
3. In WebStorm, go to the "VCS" menu and select "Commit."
4. Stage the changes you want to commit.
5. Write a commit message that describes the changes.
6. Click "Commit."

Creating and Merging Branches**
1. To create a new branch in WebStorm, go to "VCS" > "Git" > "Branches" > "New Branch."
2. Name your branch and click "OK."
3. Make changes in this new branch.
4. To merge branches, go to "VCS" > "Git" > "Merge Changes."
5. Select the branch you want to merge into the current branch.

Handling Merge Conflicts
1. If a merge conflict occurs, WebStorm will highlight the conflicting lines in the affected files.
2. Manually resolve the conflict by editing the files.
3. Mark the conflicts as resolved in WebStorm.
4. Commit the resolved changes.

Pushing and Pulling from Remote Repositories
1. To push your changes to GitHub, go to "VCS" > "Git" > "Push."
2. To pull changes from a remote repository (e.g., from GitHub), go to "VCS" > "Git" > "Pull."

Part 2: Glossary 


Branch 
  - A separate line of development within a Git repository, used to work on specific features or fixes.

- Clone
  - The process of creating a local copy of a remote Git repository.

- Commit
  - A snapshot of changes in your code that is saved in a Git repository.

- Fetch
  - Downloading updates from a remote repository without integrating (merging) them.

- Git
  - A distributed version control system for tracking changes in source code.

- GitHub
  - A web-based platform for hosting and collaborating on Git repositories.

- Merge
  - Combining the changes from one branch into another to integrate new code.

- Merge Conflict
  - Occurs when Git cannot automatically merge changes from different branches, requiring manual resolution.

- Push
  - Uploading your local Git commits to a remote repository, typically on GitHub.

- Pull
  - Retrieving changes from a remote repository and merging them into your local branch.

- Remote
  - A reference to a Git repository hosted on a remote server, like GitHub.

- Repository
  - A location where you store and manage your Git projects, containing your code and its history.
