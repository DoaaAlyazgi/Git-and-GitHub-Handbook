# ⚠️ Git Not a Repository

## 🌐 English

The error:

```text
fatal: not a git repository
```

appears when you run a Git command outside a Git repository.

Git needs to know which repository you are working with before it can perform most repository-related operations.

---

## 🔹 Check Your Current Location

You can check the files and folders in your current directory.

On Windows:

```bash
dir
```

On macOS or Linux:

```bash
ls
```

Make sure you are inside your project folder.

---

## 🔹 Check Git Status

Run:

```bash
git status
```

If you are outside a Git repository, Git may show:

```text
fatal: not a git repository (or any of the parent directories): .git
```

---

## 🔹 Move into the Project Folder

Use:

```bash
cd project-name
```

Then try:

```bash
git status
```

---

## 🔹 Initialize a New Repository

If the folder is a new project and does not have a Git repository yet:

```bash
git init
```

Then:

```bash
git status
```

---

## 💡 Common Causes

This error can happen when:

- You are in the wrong directory
- The project has not been initialized with Git
- You cloned a repository but are outside its folder
- The `.git` directory is missing

---

## 📝 Summary

If you see:

```text
fatal: not a git repository
```

First check your location:

```bash
git status
```

Then move into the correct project directory or initialize the repository:

```bash
cd project-name
git init
```

---

# 🇵🇸 العربية

# ⚠️ Git Not a Repository

## العربية

يظهر الخطأ:

```text
fatal: not a git repository
```

عندما تقوم بتنفيذ أمر من أوامر Git خارج مستودع Git.

يحتاج Git إلى معرفة المستودع الذي تعمل عليه حتى يتمكن من تنفيذ معظم العمليات المتعلقة بالمستودع.

---

## 🔹 التحقق من المكان الحالي

يمكنك عرض الملفات والمجلدات الموجودة في المكان الحالي.

على Windows:

```bash
dir
```

على macOS أو Linux:

```bash
ls
```

تأكد من أنك داخل مجلد المشروع.

---

## 🔹 التحقق من حالة Git

نفذ:

```bash
git status
```

إذا كنت خارج مستودع Git، قد يعرض Git:

```text
fatal: not a git repository (or any of the parent directories): .git
```

---

## 🔹 الانتقال إلى مجلد المشروع

استخدم:

```bash
cd project-name
```

ثم جرّب:

```bash
git status
```

---

## 🔹 إنشاء مستودع جديد

إذا كان المجلد يحتوي على مشروع جديد ولم يتم إنشاء مستودع Git له بعد:

```bash
git init
```

ثم:

```bash
git status
```

---

## 💡 الأسباب الشائعة

قد يحدث هذا الخطأ عندما:

- تكون داخل المجلد الخطأ
- لم يتم إنشاء Git Repository للمشروع
- قمت بعمل Clone للمستودع ولكنك خارج مجلده
- مجلد `.git` غير موجود

---

## 📝 الخلاصة

إذا ظهر لك:

```text
fatal: not a git repository
```

تحقق أولًا من مكانك:

```bash
git status
```

ثم انتقل إلى مجلد المشروع الصحيح أو قم بإنشاء مستودع:

```bash
cd project-name
git init
```
