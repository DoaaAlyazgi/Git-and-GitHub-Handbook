# 🍒 Git Cherry Pick Commit

## 🌐 English

`git cherry-pick <commit>` is used to apply the changes introduced by a specific commit to the current branch.

This allows you to select one commit without merging the entire branch.

---

## 🔹 Basic Usage

```bash
git cherry-pick commit-hash
```

Replace `commit-hash` with the ID of the commit you want to apply.

---

## 🔹 Find a Commit

Use:

```bash
git log --oneline
```

Example:

```text
a1b2c3d Fix authentication bug
e4f5g6h Update homepage
h7i8j9k Add navigation
```

Then apply the desired commit:

```bash
git cherry-pick a1b2c3d
```

---

## 🔹 Cherry Pick from Another Branch

First, switch to the branch where you want to apply the commit:

```bash
git switch main
```

Then run:

```bash
git cherry-pick a1b2c3d
```

Git creates a new commit on the current branch containing the changes from the selected commit.

---

## ⚠️ Important Note

Cherry Picking a commit does not move or delete the original commit.

The original commit remains on its original branch.

---

## 📝 Summary

```bash
git cherry-pick commit-hash
```

Use this command when you want to apply one specific commit to the current branch.

---

# 🇵🇸 العربية

# 🍒 Git Cherry Pick Commit

## العربية

يُستخدم الأمر `git cherry-pick <commit>` لتطبيق التغييرات التي أدخلها Commit محدد على الفرع الحالي.

يسمح لك ذلك باختيار Commit واحد دون الحاجة إلى دمج الفرع بالكامل.

---

## 🔹 الاستخدام الأساسي

```bash
git cherry-pick commit-hash
```

استبدل `commit-hash` بمعرّف الـ Commit الذي تريد تطبيقه.

---

## 🔹 العثور على Commit

استخدم:

```bash
git log --oneline
```

مثال:

```text
a1b2c3d Fix authentication bug
e4f5g6h Update homepage
h7i8j9k Add navigation
```

ثم طبّق الـ Commit المطلوب:

```bash
git cherry-pick a1b2c3d
```

---

## 🔹 Cherry Pick من فرع آخر

أولًا، انتقل إلى الفرع الذي تريد تطبيق الـ Commit عليه:

```bash
git switch main
```

ثم نفذ:

```bash
git cherry-pick a1b2c3d
```

يقوم Git بإنشاء Commit جديد على الفرع الحالي يحتوي على التغييرات الموجودة في الـ Commit المحدد.

---

## ⚠️ ملاحظة مهمة

لا يقوم Cherry Pick بنقل أو حذف الـ Commit الأصلي.

يبقى الـ Commit الأصلي موجودًا في فرعه الأصلي.

---

## 📝 الخلاصة

```bash
git cherry-pick commit-hash
```

استخدم هذا الأمر عندما تريد تطبيق Commit محدد على الفرع الحالي.
