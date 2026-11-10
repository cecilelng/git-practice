
# Core Git concepts

- **Working directory**: The folder where I edit my files. Changes here are not yet recorded by Git.
- **Staging area**: Where I collect the changes I've chosen to include in my next commit, using `git add`.
- **Repository**: My project plus its full history of commits, stored in the hidden `.git` folder.
- **Commit**: A saved snapshot of my staged changes, with a message, stored on my computer.
- **Branch**: A movable label pointing to a commit, which lets me work on changes separately from `main`.
- **Remote**: A copy of my repository on another computer, like GitHub, that I push commits to and pull others' commits from.
- **Conflict markers**: Conflict markers show the two competing versions of the same lines. Between <<<<<<< HEAD and ======= is the version on the branch I’m on (current), and between ======= and >>>>>>> branch-name is the version coming in from the other branch. To resolve it, I edit the file to keep the wording I want, delete the three marker lines, then run git add and git commit.