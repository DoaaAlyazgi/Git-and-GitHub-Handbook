# 🔍 Git Diff

## 🌐 English

`git diff` is used to see the changes made to files before they are committed.

It helps you review what was added, removed, or modified.

---

## 🔹 Step 1: Check Unstaged Changes

Run:

    git diff

This shows changes in files that have been modified but not staged yet.

---

## 🔹 Step 2: Compare Staged Changes

To see changes that have already been staged with `git add`, use:

    git diff --staged

This shows what will be included in the next commit.

---

## 🔹 Step 3: Compare a Specific File

You can check changes in a specific file:

    git diff filename.txt

This helps you focus on one file instead of the entire project.

---

## 💡 Example Workflow

A common workflow is:

    git status
    git diff
    git add .
    git diff --staged
    git commit -m "Update project"

This allows you to review your changes before committing them.

---

## 📌 Why Use `git diff`?

`git diff` is useful when you want to:

- Review your changes
- Find accidental modifications
- Check exactly what changed
- Review changes before committing
- Compare staged and unstaged changes

---

# 🇵🇸 العربية

## ما هو `git diff`؟

يُستخدم الأمر `git diff` لعرض التغييرات التي تم إجراؤها على الملفات قبل حفظها في Commit.

يساعدك على معرفة ما تمت إضافته أو حذفه أو تعديله.

---

## 🔹 الخطوة 1: عرض التغييرات غير المجهزة

استخدم:

    git diff

يعرض هذا الأمر التغييرات الموجودة في الملفات التي تم تعديلها ولكن لم تتم إضافتها إلى منطقة التجهيز بعد.

---

## 🔹 الخطوة 2: عرض التغييرات المجهزة

لعرض التغييرات التي تمت إضافتها باستخدام `git add`، استخدم:

    git diff --staged

يعرض هذا الأمر التغييرات التي سيتم تضمينها في الـ Commit القادم.

---

## 🔹 الخطوة 3: مقارنة ملف محدد

يمكنك عرض التغييرات الموجودة في ملف معين:

    git diff filename.txt

يساعدك هذا على التركيز على ملف واحد بدلًا من عرض جميع التغييرات في المشروع.

---

## 💡 مثال على سير العمل

يمكن أن يكون سير العمل كالتالي:

    git status
    git diff
    git add .
    git diff --staged
    git commit -m "Update project"

بهذه الطريقة يمكنك مراجعة التغييرات قبل حفظها في Commit.

---

## 📌 لماذا نستخدم `git diff`؟

يُستخدم `git diff` عندما تريد:

- مراجعة التغييرات
- اكتشاف التعديلات غير المقصودة
- معرفة ما الذي تغير بالضبط
- مراجعة التغييرات قبل إنشاء Commit
- مقارنة التغييرات المجهزة وغير المجهزة
