# 💾 Git Commit

## 🌐 English

`git commit` saves staged changes as a new snapshot in the Git repository.

A commit represents a specific point in the project's history.

---

## 🔹 Step 1: Stage Your Changes

Before creating a commit, add the files you want to include.

    git add .

This stages all modified and new files.

You can also stage a specific file.

    git add filename.txt

---

## 🔹 Step 2: Create a Commit

Create a commit with a clear message.

    git commit -m "Add new feature"

The message should briefly describe what changed.

---

## 🔹 Step 3: Check Your Commits

Use the following command to view your recent commits.

    git log --oneline

Example:

    a1b2c3d Add new feature

---

## 💡 Common Workflow

A basic Git workflow is:

    git status
    git add .
    git commit -m "Describe your changes"

---

## 📌 Important

Good commit messages should be:

- Clear
- Short
- Descriptive
- Related to the actual changes

Examples:

    git commit -m "Add login page"
    git commit -m "Fix navigation bug"
    git commit -m "Update README"

---

# 🇵🇸 العربية

## ما هو `git commit`؟

يُستخدم الأمر `git commit` لحفظ التغييرات التي تمت إضافتها إلى منطقة التجهيز (Staging Area) كلقطة جديدة داخل مستودع Git.

يمثل الـ Commit نقطة محددة في تاريخ المشروع، ويمكن الرجوع إليها ومراجعتها لاحقًا.

---

## 🔹 الخطوة 1: تجهيز التغييرات

قبل إنشاء Commit، يجب أولًا إضافة الملفات التي تريد حفظها.

    git add .

يؤدي هذا الأمر إلى تجهيز جميع الملفات الجديدة والمعدلة.

يمكنك أيضًا تجهيز ملف محدد فقط.

    git add filename.txt

---

## 🔹 الخطوة 2: إنشاء Commit

أنشئ Commit باستخدام رسالة واضحة تصف التغيير.

    git commit -m "Add new feature"

يُفضّل أن تكون رسالة الـ Commit قصيرة وواضحة وتصف التغيير الذي قمت به.

---

## 🔹 الخطوة 3: عرض الـ Commits

لعرض آخر الـ Commits الموجودة في المشروع، استخدم:

    git log --oneline

مثال:

    a1b2c3d Add new feature

---

## 💡 سير العمل الأساسي

سير العمل الأساسي في Git يكون عادةً:

    git status
    git add .
    git commit -m "Describe your changes"

أي:

1. `git status` لمعرفة حالة الملفات.
2. `git add .` لتجهيز التغييرات.
3. `git commit` لحفظ التغييرات في تاريخ المشروع.

---

## 📌 ملاحظة مهمة

يُفضّل أن تكون رسائل الـ Commit:

- واضحة
- قصيرة
- وصفية
- مرتبطة بالتغييرات الفعلية

أمثلة:

    git commit -m "Add login page"
    git commit -m "Fix navigation bug"
    git commit -m "Update README"
