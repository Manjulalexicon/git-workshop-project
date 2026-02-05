# Git Workshop Commands by Manjula

This README.md file contains all the Git commands I used in my workshop along with explanations.  
It demonstrates both basic and advanced Git skills.

---

## My Project Files

- README.md    This file, contains all commands and explanations.  
- notes.txt    Notes created during the workshop.  
- .gitignore   Git ignore file to exclude unnecessary,configuration files.  

---

## Basic Git Commands

1. `git init`  
   Initializes a new Git repository in the current folder.

2. `git status`  
   Shows which files are staged, unstaged, or untracked.

3. `git add <file>`  
   Stage changes in a file for the next commit. Example: `git add README.md`.

4. `git add .`  
   Stage all changes in the current directory.

5. `git commit -m "message"`  
   Commit staged changes with a descriptive message. Example: `git commit -m "Initial commit"`.

6. `git log`  
   Shows the commit history for the repository.

7. `git log --oneline`  
   Shows the commit history in a short form (one line per commit).

8. `git blame <file>`  
   Shows line-by-line history of a file, including who changed each line.

9. `git show <commit-hash>`  
   Shows details of a specific commit, including changes.

10. `git remote add origin <url>`  
    Adds a remote repository URL.

11. `git branch -M main`  
    Renames the current branch to `main`.

12. `git push -u origin main`  
    Pushes the local branch to remote and sets upstream.

13. `git clone <url>`  
    Clones a remote repository to your computer.

14. `git checkout -b <branch>`  
    Creates a new branch and switches to it.

15. `git merge <branch>`  
    Merges another branch into the current branch.

16. `git tag v1.0`  
    Adds a tag to the current commit (used for releases).

17. `git push origin v1.0`  
    Pushes a tag to the remote repository.

---

## Advanced Git Commands

1. `git stash`  
   Temporarily saves changes that are not ready to commit.

2. `git stash pop`  
   Restores stashed changes back into the working directory.

3. `git diff`  
   Shows changes not yet staged for commit.

4. `git diff --staged`  
   Shows changes that are staged for commit.

5. `git fetch`  
   Downloads commits from remote without merging automatically.

6. `git pull`  
   Fetches and merges changes from the remote branch.

7. `git reset --soft <commit>`  
   Moves HEAD to a previous commit but keeps changes staged.

8. `git reset --hard <commit>`  
   Moves HEAD to a previous commit and discards all changes.

9. `git cherry-pick <commit>`  
   Applies a commit from another branch onto the current branch.

10. `git log --graph --all --decorate`  
    Displays a visual representation of commit history with branches and merges.

11. `git reflog`  
    Shows all movements of HEAD, even “lost” commits.

12. `git shortlog`  
    Summarizes commits by author.

---

> All commands above were executed by **Manjula** during the Git Workshop.  
> Files tracked include `README.md`, `notes.txt`, and `.gitignore`.
