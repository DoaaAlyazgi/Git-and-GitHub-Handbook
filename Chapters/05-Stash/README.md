# 📦 Chapter 05: Git Stash

Welcome to Chapter 05 of the Git & GitHub Handbook.

In this chapter, we will learn how to temporarily save changes that are not ready to be committed.

---

## 🌐 English

### 🎯 What You'll Learn

In this chapter, you will learn how to:

- Temporarily save uncommitted changes
- Remove changes from the working directory
- Restore stashed changes
- View saved stashes
- Apply a stash without deleting it
- Remove a stash
- Create a branch from a stash
- Work safely when you need to switch branches

---

## 📚 Commands Covered

### 1. `git stash`

Temporarily save your uncommitted changes.

📄 Documentation:

- `git-stash.md`

---

### 2. `git stash list`

View all saved stashes.

📄 Documentation:

- `git-stash-list.md`

---

### 3. `git stash pop`

Apply the latest stash and remove it from the stash list.

📄 Documentation:

- `git-stash-pop.md`

---

### 4. `git stash apply`

Apply a stash without removing it from the stash list.

📄 Documentation:

- `git-stash-apply.md`

---

### 5. `git stash drop`

Delete a specific stash.

📄 Documentation:

- `git-stash-drop.md`

---

### 6. `git stash clear`

Delete all saved stashes.

📄 Documentation:

- `git-stash-clear.md`

---

## 🔄 Basic Stash Workflow

A common stash workflow looks like this:

```bash
git stash
git switch main
git switch feature-branch
git stash pop
```

This allows you to temporarily save your work, switch branches, and restore your changes later.

---

## 💡 Why Use Git Stash?

Git Stash is useful when:

- You are working on something but are not ready to commit it
- You need to switch branches temporarily
- You need to pull or update another branch
- You want to keep your working directory clean
- You want to save unfinished work temporarily

---

## 📝 Summary

Git Stash provides a temporary storage area for uncommitted changes.

The main commands covered in this chapter are:

```bash
git stash
git stash list
git stash pop
git stash apply
git stash drop
git stash clear
```

---

# 🇵🇸 العربية

# 📦 الفصل 05: Git Stash

مرحبًا بك في الفصل الخامس من دليل Git و GitHub.

في هذا الفصل، سنتعلم كيفية حفظ التغييرات التي لم تصبح جاهزة بعد لإنشاء Commit بشكل مؤقت.

---

## 🎯 ماذا ستتعلم؟

في هذا الفصل، ستتعلم كيفية:

- حفظ التغييرات غير المحفوظة بشكل مؤقت
- إزالة التغييرات من مجلد العمل
- استعادة التغييرات المحفوظة
- عرض التغييرات المحفوظة في Stash
- تطبيق Stash دون حذفه
- حذف Stash
- إنشاء فرع من Stash
- العمل بأمان عند الحاجة إلى الانتقال بين الفروع

---

## 📚 الأوامر التي سنتعلمها

### 1. `git stash`

حفظ التغييرات غير المحفوظة بشكل مؤقت.

📄 التوثيق:

- `git-stash.md`

---

### 2. `git stash list`

عرض جميع التغييرات المحفوظة في Stash.

📄 التوثيق:

- `git-stash-list.md`

---

### 3. `git stash pop`

تطبيق أحدث Stash وحذفه من قائمة Stash.

📄 التوثيق:

- `git-stash-pop.md`

---

### 4. `git stash apply`

تطبيق Stash دون حذفه من قائمة Stash.

📄 التوثيق:

- `git-stash-apply.md`

---

### 5. `git stash drop`

حذف Stash محدد.

📄 التوثيق:

- `git-stash-drop.md`

---

### 6. `git stash clear`

حذف جميع التغييرات المحفوظة في Stash.

📄 التوثيق:

- `git-stash-clear.md`

---

## 🔄 سير العمل الأساسي مع Stash

يمكن أن يكون سير العمل المعتاد بالشكل التالي:

```bash
git stash
git switch main
git switch feature-branch
git stash pop
```

يسمح لك ذلك بحفظ عملك مؤقتًا، والتنقل بين الفروع، ثم استعادة تغييراتك لاحقًا.

---

## 💡 لماذا نستخدم Git Stash؟

يكون Git Stash مفيدًا عندما:

- تعمل على شيء ولكنك لست مستعدًا لإنشاء Commit له
- تحتاج إلى الانتقال إلى فرع آخر مؤقتًا
- تحتاج إلى تنفيذ Pull أو تحديث فرع آخر
- تريد إبقاء مجلد العمل نظيفًا
- تريد حفظ عمل غير مكتمل بشكل مؤقت

---

## 📝 الخلاصة

يوفر Git Stash مساحة تخزين مؤقتة للتغييرات التي لم يتم عمل Commit لها.

الأوامر الأساسية التي سنتعلمها في هذا الفصل هي:

```bash
git stash
git stash list
git stash pop
git stash apply
git stash drop
git stash clear
```
