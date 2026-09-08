# GitHub Workflow Notes

- I connected the local repository to GitHub with `git remote add origin`.
- I checked the remote connection with `git remote -v`.
- I pushed local commits to GitHub with `git push`.
- I fetched remote changes with `git fetch origin`.
- I integrated remote changes locally with `git merge origin/main`.
- I recognized the merge conflict in the Pull Request on GitHub.
- GitHub displayed: "This branch has conflicts that must be resolved."
- The conflict occurred because both branches changed the same line in README.md.

## Reflection Answers

### How do I recognize that the local repository is connected to GitHub?
The command `git remote -v` shows the GitHub address for fetch and push.
### How did I see that a push was successful?
The terminal displayed `main -> main`, and the new files and commits appeared on GitHub.
### How did I recognize that new GitHub changes arrived locally?
After `git fetch origin`, Git showed that my local branch was behind by one commit. After the merge, the new content appeared in the local file.
### What is the benefit of a Pull Request when working alone?
A Pull Request allows me to review changes before merging them and helps me notice mistakes.
### What causes a simple merge conflict?
A conflict occurs when two branches change the same line differently.
### What README information is most useful?
The project description, purpose, prerequisites, file structure, and next steps are the most useful information.