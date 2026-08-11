# 🔄 Chapter 06: Git Reset & Restore

Welcome to Chapter 06 of the Git & GitHub Handbook.

In this chapter, we will learn how to undo changes, restore files, and move the current branch to a different commit using Git.

---

## 🌐 English

### 🎯 What You'll Learn

In this chapter, you will learn how to:

- Restore modified files
- Unstage files
- Undo commits
- Move the current branch to another commit
- Understand the difference between `reset` and `restore`
- Use soft reset
- Use mixed reset
- Use hard reset
- Safely undo unwanted changes

---

## 📚 Commands Covered

### 1. `git restore`

Restore files to a previous state or remove unwanted working-directory changes.

📄 Documentation:

- `git-restore.md`

---

### 2. `git reset`

Move the current branch to another commit and optionally change the staging area or working directory.

📄 Documentation:

- `git-reset.md`

---

### 3. `git reset --soft`

Move the branch to another commit while keeping changes staged.

📄 Documentation:

- `git-reset-soft.md`

---

### 4. `git reset --mixed`

Move the branch to another commit while keeping the changes in the working directory but removing them from the staging area.

📄 Documentation:

- `git-reset-mixed.md`

---

### 5. `git reset --hard`

Move the branch to another commit and discard changes from the staging area and working directory.

📄 Documentation:

- `git-reset-hard.md`

---

## 🔄 Reset Modes

Git provides three common reset modes:

```text
--soft
--mixed
--hard
```

They differ in what happens to your staging area and working directory.

### `--soft`

Keeps changes staged.

### `--mixed`

Keeps changes in the working directory but unstages them.

### `--hard`

Discards changes from the staging area and working directory.

---

## 🔄 Reset vs Restore

The two commands have different purposes.

### `git restore`

Primarily works with files and is commonly used to discard working-directory changes or unstage files.

### `git reset`

Primarily moves the current branch to another commit and can also change the staging area and working directory depending on the selected mode.

---

## ⚠️ Important Warning

Some reset operations can permanently discard changes.

Be especially careful when using:

```bash
git reset --hard
```

Always make sure you understand which changes will be removed before running destructive commands.

---

## 💡 Basic Undo Workflow

A simple workflow for undoing a working-directory change:

```bash
git status
git restore filename.txt
```

To unstage a file:

```bash
git restore --staged filename.txt
```

To move the current branch back one commit while keeping the changes staged:

```bash
git reset --soft HEAD~1
```

---

## 📝 Summary

The main commands covered in this chapter are:

```bash
git restore
git reset
git reset --soft
git reset --mixed
git reset --hard
```

Understanding these commands helps you safely manage unwanted changes and correct mistakes in your Git history.

---

# 🇵🇸 العربية

# 🔄 الفصل 06: Git Reset & Restore

مرحبًا بك في الفصل السادس من دليل Git و GitHub.

في هذا الفصل، سنتعلم كيفية التراجع عن التغييرات، واستعادة الملفات، ونقل الفرع الحالي إلى Commit مختلف باستخدام Git.

---

## 🎯 ماذا ستتعلم؟

في هذا الفصل، ستتعلم كيفية:

- استعادة الملفات التي تم تعديلها
- إزالة الملفات من منطقة Staging
- التراجع عن الـ Commits
- نقل الفرع الحالي إلى Commit آخر
- فهم الفرق بين `reset` و `restore`
- استخدام Soft Reset
- استخدام Mixed Reset
- استخدام Hard Reset
- التراجع بأمان عن التغييرات غير المرغوبة

---

## 📚 الأوامر التي سنتعلمها

### 1. `git restore`

استعادة الملفات إلى حالة سابقة أو إزالة التغييرات غير المرغوبة من مجلد العمل.

📄 التوثيق:

- `git-restore.md`

---

### 2. `git reset`

نقل الفرع الحالي إلى Commit آخر، مع إمكانية تعديل منطقة Staging أو مجلد العمل.

📄 التوثيق:

- `git-reset.md`

---

### 3. `git reset --soft`

نقل الفرع إلى Commit آخر مع إبقاء التغييرات في منطقة Staging.

📄 التوثيق:

- `git-reset-soft.md`

---

### 4. `git reset --mixed`

نقل الفرع إلى Commit آخر مع إبقاء التغييرات في مجلد العمل، ولكن إزالتها من منطقة Staging.

📄 التوثيق:

- `git-reset-mixed.md`

---

### 5. `git reset --hard`

نقل الفرع إلى Commit آخر مع حذف التغييرات من منطقة Staging ومجلد العمل.

📄 التوثيق:

- `git-reset-hard.md`

---

## 🔄 أوضاع Reset

يوفر Git ثلاثة أوضاع شائعة لـ Reset:

```text
--soft
--mixed
--hard
```

وتختلف هذه الأوضاع في طريقة تعاملها مع منطقة Staging ومجلد العمل.

### `--soft`

يبقي التغييرات في منطقة Staging.

### `--mixed`

يبقي التغييرات في مجلد العمل ولكنه يزيلها من منطقة Staging.

### `--hard`

يحذف التغييرات من منطقة Staging ومجلد العمل.

---

## 🔄 الفرق بين Reset و Restore

لكل أمر استخدام مختلف.

### `git restore`

يعمل بشكل أساسي مع الملفات، ويُستخدم عادةً للتراجع عن تغييرات مجلد العمل أو إزالة الملفات من منطقة Staging.

### `git reset`

يُستخدم بشكل أساسي لنقل الفرع الحالي إلى Commit آخر، ويمكنه أيضًا تعديل منطقة Staging ومجلد العمل حسب الوضع المستخدم.

---

## ⚠️ تحذير مهم

يمكن لبعض عمليات Reset أن تؤدي إلى حذف التغييرات بشكل نهائي.

كن حذرًا بشكل خاص عند استخدام:

```bash
git reset --hard
```

تأكد دائمًا من فهم التغييرات التي سيتم حذفها قبل تنفيذ الأوامر التي قد تكون مدمرة.

---

## 💡 سير عمل بسيط للتراجع عن التغييرات

للتراجع عن تغيير في مجلد العمل:

```bash
git status
git restore filename.txt
```

لإزالة ملف من منطقة Staging:

```bash
git restore --staged filename.txt
```

للعودة بالفرع الحالي إلى Commit سابق مع إبقاء التغييرات في منطقة Staging:

```bash
git reset --soft HEAD~1
```

---

## 📝 الخلاصة

الأوامر الأساسية التي سنتعلمها في هذا الفصل هي:

```bash
git restore
git reset
git reset --soft
git reset --mixed
git reset --hard
```

يساعدك فهم هذه الأوامر على إدارة التغييرات غير المرغوبة وتصحيح الأخطاء في سجل Git بطريقة أكثر أمانًا.
