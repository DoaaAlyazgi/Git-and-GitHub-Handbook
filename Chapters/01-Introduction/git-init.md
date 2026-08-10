# ⚙️ Git Init

## 🌐 English

`git init` is used to create a new Git repository inside an existing project folder.

It tells Git to start tracking the project and creates a hidden `.git` directory that stores repository information.

---

## 🔹 Step 1: Open Your Project Folder

Open your terminal and navigate to the folder where your project is located.

Example:

```bash
cd my-project
```

---

## 🔹 Step 2: Initialize Git

Run:

```bash
git init
```

Git creates a hidden `.git` directory inside your project.

You may see:

```text
Initialized empty Git repository in /path/to/my-project/.git/
```

---

## 🔹 Step 3: Check the Repository Status

Run:

```bash
git status
```

This shows the current state of your files, including untracked and modified files.

---

## 💡 Important Note

`git init` only initializes Git in the current folder.

It does not create commits or upload your project to GitHub.

You must add, commit, and push your files separately.

---

## 🧪 Quick Example

```bash
cd my-project
git init
git status
```

### Summary

| Command | Purpose |
|---|---|
| `git init` | Create a new Git repository |
| `git status` | Check the repository status |

---

# 🇵🇸 العربية

يُستخدم الأمر `git init` لإنشاء مستودع Git جديد داخل مجلد مشروع موجود مسبقًا.

يخبر هذا الأمر Git بالبدء في تتبع المشروع، ويُنشئ مجلدًا مخفيًا باسم `.git` يحتوي على معلومات المستودع.

---

## 🔹 الخطوة 1: فتح مجلد المشروع

افتح Terminal أو Command Prompt وانتقل إلى المجلد الذي يوجد فيه مشروعك.

مثال:

```bash
cd my-project
```

---

## 🔹 الخطوة 2: تهيئة Git

قم بتشغيل الأمر:

```bash
git init
```

سيقوم Git بإنشاء مجلد مخفي باسم `.git` داخل مجلد المشروع.

قد تظهر لك رسالة مثل:

```text
Initialized empty Git repository in /path/to/my-project/.git/
```

وهذا يعني أن مستودع Git تم إنشاؤه بنجاح.

---

## 🔹 الخطوة 3: التحقق من حالة المستودع

قم بتشغيل:

```bash
git status
```

يعرض هذا الأمر الحالة الحالية للملفات، بما في ذلك الملفات التي لم تتم إضافتها والملفات التي تم تعديلها.

---

## 💡 ملاحظة مهمة

الأمر `git init` يقوم فقط بتهيئة Git داخل المجلد الحالي.

لا يقوم بإنشاء Commit أو رفع المشروع إلى GitHub تلقائيًا.

يجب إضافة الملفات وإنشاء Commit ثم رفعها بشكل منفصل.

---

## 🧪 مثال سريع

```bash
cd my-project
git init
git status
```

### الملخص

| الأمر | الاستخدام |
|---|---|
| `git init` | إنشاء مستودع Git جديد |
| `git status` | التحقق من حالة المستودع |
