# 🌐 Chapter 04: Remote Repositories

Welcome to Chapter 04 of the Git & GitHub Handbook.

In this chapter, we will learn how to work with remote repositories and connect our local Git repository to platforms such as GitHub.

---

## 🌐 English

### 🎯 What You'll Learn

In this chapter, you will learn how to:

- Understand what a remote repository is
- Connect a local repository to a remote repository
- View remote repositories
- Add a remote repository
- Rename a remote
- Remove a remote
- Push changes to a remote repository
- Pull changes from a remote repository
- Fetch changes from a remote repository
- Clone an existing repository
- Understand the difference between `fetch`, `pull`, and `push`

---

## 📚 Commands Covered

### 1. `git remote`

Used to manage connections to remote repositories.

📄 Documentation:

- `git-remote.md`

---

### 2. `git clone`

Used to create a local copy of an existing remote repository.

📄 Documentation:

- `git-clone.md`

---

### 3. `git push`

Used to upload local commits to a remote repository.

📄 Documentation:

- `git-push.md`

---

### 4. `git pull`

Used to download changes from a remote repository and integrate them into the current branch.

📄 Documentation:

- `git-pull.md`

---

### 5. `git fetch`

Used to download changes from a remote repository without automatically merging them into the current branch.

📄 Documentation:

- `git-fetch.md`

---

## 🔄 Basic Remote Workflow

A common workflow with a remote repository looks like this:

```bash
git remote add origin https://github.com/username/repository.git
git push -u origin main
git pull
git push
```

The process is:

1. Connect the local repository to a remote repository
2. Push the local branch to the remote repository
3. Pull changes when updates are available
4. Push your new commits to the remote repository

---

## 🔗 Local vs Remote Repository

A **local repository** exists on your computer.

A **remote repository** exists on a remote server such as GitHub.

For example:

```text
Local Repository
      │
      │ git push
      ▼
Remote Repository
      │
      │ git pull / git fetch
      ▼
Local Repository
```

This allows developers to share and synchronize their work.

---

## 💡 Why Use Remote Repositories?

Remote repositories are useful because they allow you to:

- Store projects online
- Back up your work
- Collaborate with other developers
- Share code
- Synchronize changes between different computers
- Work with platforms such as GitHub

---

## 📝 Summary

Remote repositories allow Git projects to communicate with repositories stored on remote servers.

The main commands covered in this chapter are:

```bash
git remote
git clone
git push
git pull
git fetch
```

Understanding remote repositories is essential for working with GitHub and collaborating with other developers.

---

# 🇵🇸 العربية

# 🌐 الفصل 04: المستودعات البعيدة

مرحبًا بك في الفصل الرابع من دليل Git و GitHub.

في هذا الفصل، سنتعلم كيفية العمل مع المستودعات البعيدة وربط مستودع Git المحلي بمنصات مثل GitHub.

---

## 🎯 ماذا ستتعلم؟

في هذا الفصل، ستتعلم كيفية:

- فهم معنى المستودع البعيد
- ربط المستودع المحلي بمستودع بعيد
- عرض المستودعات البعيدة
- إضافة مستودع بعيد
- إعادة تسمية المستودع البعيد
- إزالة مستودع بعيد
- رفع التغييرات إلى المستودع البعيد
- تنزيل التغييرات من المستودع البعيد
- جلب التغييرات من المستودع البعيد
- نسخ مستودع موجود
- فهم الفرق بين `fetch` و `pull` و `push`

---

## 📚 الأوامر التي سنتعلمها

### 1. `git remote`

يُستخدم لإدارة الاتصالات مع المستودعات البعيدة.

📄 التوثيق:

- `git-remote.md`

---

### 2. `git clone`

يُستخدم لإنشاء نسخة محلية من مستودع بعيد موجود.

📄 التوثيق:

- `git-clone.md`

---

### 3. `git push`

يُستخدم لرفع الـ Commits المحلية إلى المستودع البعيد.

📄 التوثيق:

- `git-push.md`

---

### 4. `git pull`

يُستخدم لتنزيل التغييرات من المستودع البعيد ودمجها مع الفرع الحالي.

📄 التوثيق:

- `git-pull.md`

---

### 5. `git fetch`

يُستخدم لتنزيل التغييرات من المستودع البعيد دون دمجها تلقائيًا مع الفرع الحالي.

📄 التوثيق:

- `git-fetch.md`

---

## 🔄 سير العمل الأساسي مع المستودعات البعيدة

يمكن أن يكون سير العمل المعتاد مع مستودع بعيد بالشكل التالي:

```bash
git remote add origin https://github.com/username/repository.git
git push -u origin main
git pull
git push
```

وتكون العملية كالتالي:

1. ربط المستودع المحلي بمستودع بعيد
2. رفع الفرع المحلي إلى المستودع البعيد
3. تنزيل التغييرات عندما تتوفر تحديثات
4. رفع الـ Commits الجديدة إلى المستودع البعيد

---

## 🔗 المستودع المحلي مقابل المستودع البعيد

**المستودع المحلي** هو المستودع الموجود على جهاز الكمبيوتر الخاص بك.

أما **المستودع البعيد** فهو المستودع الموجود على خادم بعيد مثل GitHub.

مثال:

```text
المستودع المحلي
      │
      │ git push
      ▼
المستودع البعيد
      │
      │ git pull / git fetch
      ▼
المستودع المحلي
```

يسمح ذلك للمطورين بمشاركة عملهم ومزامنة التغييرات.

---

## 💡 لماذا نستخدم المستودعات البعيدة؟

المستودعات البعيدة مفيدة لأنها تسمح لك بـ:

- تخزين المشاريع على الإنترنت
- الاحتفاظ بنسخة احتياطية من عملك
- التعاون مع مطورين آخرين
- مشاركة الأكواد
- مزامنة التغييرات بين أجهزة مختلفة
- العمل مع منصات مثل GitHub

---

## 📝 الخلاصة

تسمح المستودعات البعيدة لمشاريع Git بالتواصل مع المستودعات المخزنة على خوادم بعيدة.

الأوامر الأساسية التي سنتعلمها في هذا الفصل هي:

```bash
git remote
git clone
git push
git pull
git fetch
```

ويُعد فهم المستودعات البعيدة أمرًا أساسيًا للعمل مع GitHub والتعاون مع المطورين الآخرين.
