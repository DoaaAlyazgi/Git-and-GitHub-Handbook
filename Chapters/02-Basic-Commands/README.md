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

- `git-status.md`

---

### 2. `git add`

Add files to the staging area before committing.

📄 Documentation:

- `git-add.md`

---

### 3. `git commit`

Save staged changes as a new commit.

📄 Documentation:

- `git-commit.md`

---

### 4. `git diff`

View the differences between your current files and previous versions.

📄 Documentation:

- `git-diff.md`

---

### 5. `git log`

View the history of commits in your repository.

📄 Documentation:

- `git-log.md`

---

### 6. `git mv`

Move or rename files while keeping Git aware of the change.

📄 Documentation:

- `git-mv.md`

---

### 7. `git rm`

Remove files from the working directory and Git.

📄 Documentation:

- `git-rm.md`

---

### 8. `git restore`

Restore files to a previous state or discard unwanted changes.

📄 Documentation:

- `git-restore.md`

---

### 9. `git reset`

Move the current branch to another commit and optionally modify the staging area or working directory.

📄 Documentation:

- `git-reset.md`

---

### 10. `git clean`

Remove untracked files from the working directory.

📄 Documentation:

- `git-clean.md`

---

## 🔄 Basic Git Workflow

A common Git workflow looks like this:

```bash
git status
git add .
git status
git commit -m "Your commit message"
git status
```

This workflow allows you to check your changes, stage them, create a commit, and verify the repository status.

---

## 📌 Summary

The commands covered in this chapter form the foundation of everyday Git usage.

Understanding these commands will make it easier to work with Git repositories and prepare you for more advanced Git concepts in the next chapters.

---

# 🇵🇸 العربية

# 💻 الفصل الثاني: أوامر Git الأساسية

مرحبًا بك في الفصل الثاني من دليل Git وGitHub.

في هذا الفصل، سنتعلم أهم أوامر Git المستخدمة في التطوير اليومي.

---

## 🎯 ماذا ستتعلم؟

في هذا الفصل، ستتعلم كيفية:

- التحقق من الحالة الحالية لمستودعك.
- إضافة الملفات إلى منطقة التجهيز (Staging Area).
- إنشاء عمليات Commit.
- عرض التغييرات بين الملفات وعمليات Commit.
- عرض سجل عمليات Commit.
- إعادة تسمية الملفات ونقلها.
- إزالة الملفات من Git.
- استعادة الملفات.
- التراجع عن التغييرات باستخدام Reset.
- حذف الملفات غير المتتبعة.
- فهم سير العمل الأساسي في Git.

---

## 📚 الأوامر التي يغطيها الفصل

### 1. `git status`

يُستخدم الأمر `git status` للتحقق من الحالة الحالية لمجلد العمل ومنطقة التجهيز.

📄 التوثيق:

- `git-status.md`

---

### 2. `git add`

يُستخدم الأمر `git add` لإضافة الملفات إلى منطقة التجهيز قبل إنشاء Commit.

📄 التوثيق:

- `git-add.md`

---

### 3. `git commit`

يُستخدم الأمر `git commit` لحفظ التغييرات الموجودة في منطقة التجهيز كعملية Commit جديدة.

📄 التوثيق:

- `git-commit.md`

---

### 4. `git diff`

يُستخدم الأمر `git diff` لعرض الاختلافات بين الملفات الحالية والنسخ السابقة منها.

📄 التوثيق:

- `git-diff.md`

---

### 5. `git log`

يُستخدم الأمر `git log` لعرض سجل عمليات Commit الموجودة في المستودع.

📄 التوثيق:

- `git-log.md`

---

### 6. `git mv`

يُستخدم الأمر `git mv` لنقل الملفات أو إعادة تسميتها مع إبقاء Git على علم بالتغيير.

📄 التوثيق:

- `git-mv.md`

---

### 7. `git rm`

يُستخدم الأمر `git rm` لإزالة الملفات من مجلد العمل ومن Git.

📄 التوثيق:

- `git-rm.md`

---

### 8. `git restore`

يُستخدم الأمر `git restore` لاستعادة الملفات إلى حالة سابقة أو التخلص من التغييرات غير المرغوب فيها.

📄 التوثيق:

- `git-restore.md`

---

### 9. `git reset`

يُستخدم الأمر `git reset` لنقل الفرع الحالي إلى Commit آخر، مع إمكانية تعديل منطقة التجهيز أو مجلد العمل.

📄 التوثيق:

- `git-reset.md`

---

### 10. `git clean`

يُستخدم الأمر `git clean` لحذف الملفات غير المتتبعة من مجلد العمل.

📄 التوثيق:

- `git-clean.md`

---

## 🔄 سير العمل الأساسي في Git

يبدو سير العمل الشائع في Git بهذا الشكل:

```bash
git status
git add .
git status
git commit -m "Your commit message"
git status
```

يسمح لك هذا التسلسل بالتحقق من التغييرات، وإضافتها إلى منطقة التجهيز، وإنشاء Commit، ثم التحقق مرة أخرى من حالة المستودع.

---

## 📌 الخلاصة

الأوامر التي يغطيها هذا الفصل تشكل الأساس لاستخدام Git في العمل اليومي.

فهم هذه الأوامر سيساعدك على التعامل مع مستودعات Git بسهولة أكبر، وسيجهزك لتعلم مفاهيم Git المتقدمة في الفصول القادمة.
