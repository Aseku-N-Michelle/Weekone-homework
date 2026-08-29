# Git Commands Explained

- **git status** — Shows which files have been changed, staged, or are untracked in your working directory.
- **git add** — Stages changes so they are ready to be included in the next commit.
- **git commit** — Saves the staged changes as a permanent snapshot in your repository's history.
- **git push** — Uploads your local commits to the remote repository on GitHub.
- **git pull** — Downloads and merges changes from the remote repository into your local copy.

# Tool Installation Notes

**Tool installed:** Git 2.51.0 (via Git for Windows)

**Problem 1:** Pasting the repository URL into Git Bash inserted extra characters (`^[[200~...~`), causing the `git clone` command to fail.
**Solution:** Typed the URL manually instead of pasting, which resolved the issue.

**Problem 2:** When running `git push` for the first time, I got the error:
`fatal: unable to access 'https://github.com/...': Could not resolve host: github.com`
**Solution:** This happened because my computer had lost its Wi-Fi connection. I reconnected to Wi-Fi and ran `git push` again, and it completed successfully.