# 💻 Chapter 02: Basic Git Commands

Welcome to Chapter 02 of the Git & GitHub Handbook.

In this chapter, we will learn the most important Git commands used in everyday development.

---

## 🌐 English

### 🎯 What You'll Learn

In this chapter, you will learn how to:

- Check the current state of your repository
- Add files to the staging area
- Create commits
- View changes between files and commits
- View your commit history
- Rename and move files
- Remove files from Git
- Restore files
- Reset changes
- Clean untracked files
- Understand the basic Git workflow

---

## 📚 Commands Covered

### 1. `git status`

Check the current state of your working directory and staging area.

📄 Documentation:

- [git-status.md](git-status.md)

---

### 2. `git add`

Add files to the staging area before committing.

📄 Documentation:

- [git-add.md](git-add.md)

---

### 3. `git commit`

Save staged changes as a new commit.

📄 Documentation:

- [git-commit.md](git-commit.md)

---

### 4. `git diff`

View the differences between your current files and previous versions.

📄 Documentation:

- [git-diff.md](git-diff.md)

---

### 5. `git log`

View the history of commits in your repository.

📄 Documentation:

- [git-log.md](git-log.md)

---

### 6. `git mv`

Move or rename files while keeping Git aware of the change.

📄 Documentation:

- [git-mv.md](git-mv.md)

---

### 7. `git rm`

Remove files from the working directory and Git.

📄 Documentation:

- [git-rm.md](git-rm.md)

---

### 8. `git restore`

Restore files to a previous state or discard unwanted changes.

📄 Documentation:

- [git-restore.md](git-restore.md)

---

### 9. `git reset`

Move the current branch to another commit and optionally modify the staging area or working directory.

📄 Documentation:

- [git-reset.md](git-reset.md)

---

### 10. `git clean`

Remove untracked files from the working directory.

📄 Documentation:

- [git-clean.md](git-clean.md)

---

## 🔄 Basic Git Workflow

A common Git workflow looks like this:

```bash
git status
git add .
git status
git commit -m "Your commit message"
git log
