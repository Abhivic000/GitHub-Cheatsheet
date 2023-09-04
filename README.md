# GitHub-Cheatsheet
Github cheatsheet for your help

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Git/GitHub Cheat Sheet</title>
  <style>
    table {
      width: 100%;
      border-collapse: collapse;
    }

    th, td {
      border: 1px solid #ddd;
      padding: 8px;
      text-align: left;
    }

    th {
      background-color: #f2f2f2;
    }
  </style>
</head>
<body>
  <h1>Git/GitHub Cheat Sheet</h1>

  <h2>Git Basics:</h2>
  <table>
    <thead>
      <tr>
        <th>Command</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><code>git init</code></td>
        <td>Initialize a new Git repository.</td>
      </tr>
      <tr>
        <td><code>git clone [repository URL]</code></td>
        <td>Clone a remote repository.</td>
      </tr>
      <tr>
        <td><code>git status</code></td>
        <td>Check the status of your working directory.</td>
      </tr>
      <tr>
        <td><code>git add [file(s)]</code></td>
        <td>Stage changes for commit.</td>
      </tr>
      <tr>
        <td><code>git commit -m "Your commit message"</code></td>
        <td>Commit changes with a message.</td>
      </tr>
      <tr>
        <td><code>git log</code></td>
        <td>View the commit history.</td>
      </tr>
    </tbody>
  </table>

  <h2>Branching and Merging:</h2>
  <table>
    <thead>
      <tr>
        <th>Command</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><code>git branch</code></td>
        <td>List all branches in the repository.</td>
      </tr>
      <tr>
        <td><code>git branch [branch name]</code></td>
        <td>Create a new branch.</td>
      </tr>
      <tr>
        <td><code>git checkout [branch name]</code></td>
        <td>Switch to a different branch.</td>
      </tr>
      <tr>
        <td><code>git merge [branch name]</code></td>
        <td>Merge changes from one branch into another.</td>
      </tr>
    </tbody>
  </table>

  <h2>Remote Repositories (GitHub):</h2>
  <table>
    <thead>
      <tr>
        <th>Command</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><code>git remote add [name] [repository URL]</code></td>
        <td>Add a remote repository.</td>
      </tr>
      <tr>
        <td><code>git remote -v</code></td>
        <td>List all remote repositories.</td>
      </tr>
      <tr>
        <td><code>git fetch [remote]</code></td>
        <td>Fetch changes from a remote repository.</td>
      </tr>
      <tr>
        <td><code>git push [remote] [branch]</code></td>
        <td>Push commits to a remote repository.</td>
      </tr>
      <tr>
        <td><code>git pull [remote] [branch]</code></td>
        <td>Pull changes from a remote repository.</td>
      </tr>
    </tbody>
  </table>

  <h2>Undoing Changes:</h2>
  <table>
    <thead>
      <tr>
        <th>Command</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><code>git checkout -- [file]</code></td>
        <td>Discard changes in the working directory.</td>
      </tr>
      <tr>
        <td><code>git reset [file]</code></td>
        <td>Unstage changes but keep them in the working directory.</td>
      </tr>
      <tr>
        <td><code>git reset --hard [commit]</code></td>
        <td>Reset the branch to a previous commit (discard changes).</td>
      </tr>
      <tr>
        <td><code>git branch [new branch name] HEAD</code></td>
        <td>Create a new branch at the current commit.</td>
      </tr>
    </tbody>
  </table>

  <h2>GitHub-Specific Commands:</h2>
  <ul>
    <li>Create a new repository on GitHub: Go to GitHub > New repository</li>
    <li><code>git remote add origin [repository URL]</code> - Push an existing repository to GitHub.</li>
    <li>Create a pull request on GitHub: Go to your repository > Pull requests > New pull request</li>
    <li>Fork a repository on GitHub: Click the "Fork" button on the repository's page</li>
    <li><code>git remote add upstream [original repository URL]</code> - Sync a forked repository with the original (upstream) repository.</li>
    <li>Add a collaborator to a GitHub repository: Go to your repository > Settings > Collaborators</li>
  </ul>
</body>
</html>




