# GitHub-Cheatsheet
Github cheatsheet for your help

    <title>Git/GitHub Cheat Sheet</title>

    <h2>Git Basics:</h2>
    <ul>
        <li><code>git init</code> - Initialize a new Git repository.</li>
        <li><code>git clone [repository URL]</code> - Clone a remote repository.</li>
        <li><code>git status</code> - Check the status of your working directory.</li>
        <li><code>git add [file(s)]</code> - Stage changes for commit.</li>
        <li><code>git commit -m "Your commit message"</code> - Commit changes with a message.</li>
        <li><code>git log</code> - View the commit history.</li>
    </ul>

    <h2>Branching and Merging:</h2>
    <ul>
        <li><code>git branch</code> - List all branches in the repository.</li>
        <li><code>git branch [branch name]</code> - Create a new branch.</li>
        <li><code>git checkout [branch name]</code> - Switch to a different branch.</li>
        <li><code>git merge [branch name]</code> - Merge changes from one branch into another.</li>
    </ul>

    <h2>Remote Repositories (GitHub):</h2>
    <ul>
        <li><code>git remote add [name] [repository URL]</code> - Add a remote repository.</li>
        <li><code>git remote -v</code> - List all remote repositories.</li>
        <li><code>git fetch [remote]</code> - Fetch changes from a remote repository.</li>
        <li><code>git push [remote] [branch]</code> - Push commits to a remote repository.</li>
        <li><code>git pull [remote] [branch]</code> - Pull changes from a remote repository.</li>
    </ul>

    <h2>Undoing Changes:</h2>
    <ul>
        <li><code>git checkout -- [file]</code> - Discard changes in the working directory.</li>
        <li><code>git reset [file]</code> - Unstage changes but keep them in the working directory.</li>
        <li><code>git reset --hard [commit]</code> - Reset the branch to a previous commit (discard changes).</li>
        <li><code>git branch [new branch name] HEAD</code> - Create a new branch at the current commit.</li>
    </ul>

    <h2>GitHub-Specific Commands:</h2>
    <ul>
        <li>Create a new repository on GitHub: Go to GitHub > New repository</li>
        <li><code>git remote add origin [repository URL]</code> - Push an existing repository to GitHub.</li>
        <li>Create a pull request on GitHub: Go to your repository > Pull requests > New pull request</li>
        <li>Fork a repository on GitHub: Click the "Fork" button on the repository's page</li>
        <li><code>git remote add upstream [original repository URL]</code> - Sync a forked repository with the original (upstream) repository.</li>
        <li>Add a collaborator to a GitHub repository: Go to your repository > Settings > Collaborators</li>
    </ul>

