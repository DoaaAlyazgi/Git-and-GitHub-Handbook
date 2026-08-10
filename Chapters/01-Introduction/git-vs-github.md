# 📌 Git vs GitHub

## 🌐 English

Git and GitHub are closely related, but they are **not the same thing**.

Understanding the difference between them is one of the most important concepts for anyone learning modern software development.

---

## 🔹 What is Git?

**Git** is a distributed Version Control System (VCS).

It is a tool that runs on your computer and helps you track changes in your code and manage different versions of your project.

With Git, you can:

- Track changes in your files.
- Create commits to save versions of your project.
- Create and manage branches.
- Switch between different versions of your code.
- Undo or restore changes.
- Work on features without affecting the main project.
- Merge changes from different branches.
- Work offline.

### 💡 Simple Example

Imagine you are building a website.

You make several changes:

```text
Version 1 → Basic website
Version 2 → Added login page
Version 3 → Added dashboard
Version 4 → Fixed bugs
```

Git keeps track of these changes and allows you to move between different versions when needed.

---

## 🔹 What is GitHub?

**GitHub** is a cloud-based platform that allows developers to store, share, and collaborate on Git repositories.

It works with Git, but it provides additional features that Git itself does not provide.

With GitHub, you can:

- Store Git repositories online.
- Share your projects with other developers.
- Collaborate with team members.
- Review and manage code changes.
- Create Pull Requests.
- Track issues and tasks.
- Manage projects.
- Store documentation using README files.
- Contribute to open-source projects.

### 💡 Simple Example

Imagine that Git is the tool you use to manage your project on your computer.

GitHub is the online platform where you can upload that project, share it with others, and work with a team.

---

## 🔄 Git vs GitHub

| Git | GitHub |
|---|---|
| Version Control System | Cloud-based development platform |
| Runs locally on your computer | Runs mainly online |
| Tracks changes in your project | Hosts Git repositories |
| Works offline | Requires internet for most online features |
| Manages commits and branches | Provides collaboration tools |
| Created by Linus Torvalds | Owned by Microsoft |

---

## 🧠 Easy Way to Remember

Think of it this way:

> **Git = The tool that manages your project history.**

> **GitHub = The platform where you store and collaborate on that project online.**

You can use Git without GitHub.

For example, you can create a Git repository on your computer and use commits, branches, merges, and other Git features without connecting to the internet.

However, GitHub uses Git to provide online collaboration and repository hosting.

---

## 🚀 How Git and GitHub Work Together

A common workflow looks like this:

```text
Your Computer
     ↓
    Git
     ↓
Commit Changes
     ↓
   GitHub
     ↓
Share / Collaborate
```

For example:

```bash
git add .
git commit -m "Add login page"
git push
```

The first two commands are Git commands.

The `git push` command sends your local commits to a remote repository, such as a repository hosted on GitHub.

---

## ⚠️ Important Note

Git and GitHub do not have to be used together.

Git is the version control system.

GitHub is one of many platforms that can host Git repositories.

Other platforms include GitLab and Bitbucket.

---

# 🌐 العربية

## 🔹 ما هو Git؟

**Git** هو نظام للتحكم في الإصدارات (Version Control System - VCS).

وهو أداة تعمل على جهازك وتساعدك على تتبع التغييرات التي تجريها على الكود وإدارة الإصدارات المختلفة من مشروعك.

باستخدام Git يمكنك:

- تتبع التغييرات في ملفاتك.
- إنشاء `commits` لحفظ إصدارات من مشروعك.
- إنشاء وإدارة `branches`.
- التنقل بين الإصدارات المختلفة من الكود.
- التراجع عن التغييرات أو استعادتها.
- العمل على ميزات جديدة دون التأثير على المشروع الرئيسي.
- دمج التغييرات من فروع مختلفة.
- العمل بدون اتصال بالإنترنت.

### 💡 مثال بسيط

تخيل أنك تقوم ببناء موقع إلكتروني.

وقمت بإجراء عدة تغييرات:

```text
الإصدار 1 → موقع أساسي
الإصدار 2 → إضافة صفحة تسجيل الدخول
الإصدار 3 → إضافة لوحة التحكم
الإصدار 4 → إصلاح الأخطاء
```

يقوم Git بتتبع هذه التغييرات ويسمح لك بالانتقال بين الإصدارات المختلفة عند الحاجة.

---

## 🔹 ما هو GitHub؟

**GitHub** هو منصة سحابية تتيح للمطورين تخزين ومشاركة والتعاون على مستودعات Git.

يعمل GitHub مع Git، لكنه يوفر ميزات إضافية لا يوفرها Git بحد ذاته.

باستخدام GitHub يمكنك:

- تخزين مستودعات Git على الإنترنت.
- مشاركة مشاريعك مع مطورين آخرين.
- التعاون مع أعضاء الفريق.
- مراجعة وإدارة تغييرات الكود.
- إنشاء Pull Requests.
- متابعة المشاكل والمهام باستخدام Issues.
- إدارة المشاريع.
- تخزين التوثيق باستخدام ملفات README.
- المساهمة في مشاريع Open Source.

### 💡 مثال بسيط

تخيل أن **Git** هو الأداة التي تستخدمها لإدارة مشروعك على جهاز الكمبيوتر.

بينما **GitHub** هو المنصة الموجودة على الإنترنت التي ترفع عليها المشروع وتشاركه مع الآخرين وتعمل عليه مع فريقك.

---

## 🔄 الفرق بين Git و GitHub

| Git | GitHub |
|---|---|
| نظام للتحكم في الإصدارات | منصة سحابية لتطوير المشاريع |
| يعمل محليًا على جهازك | يعمل بشكل أساسي عبر الإنترنت |
| يتتبع التغييرات في المشروع | يستضيف مستودعات Git |
| يمكنه العمل بدون إنترنت | يحتاج إلى الإنترنت لمعظم الميزات السحابية |
| يدير الـ Commits والـ Branches | يوفر أدوات للتعاون بين المطورين |
| تم إنشاؤه بواسطة Linus Torvalds | مملوك لشركة Microsoft |

---

## 🧠 طريقة سهلة لتذكر الفرق

فكر في الأمر بهذه الطريقة:

> **Git = الأداة التي تدير سجل وتاريخ مشروعك.**

> **GitHub = المنصة التي تخزن عليها المشروع وتتعاون عليه عبر الإنترنت.**

يمكنك استخدام Git بدون GitHub.

على سبيل المثال، يمكنك إنشاء مستودع Git على جهاز الكمبيوتر الخاص بك واستخدام الـ commits والـ branches والـ merges وغيرها من ميزات Git بدون الحاجة إلى الاتصال بالإنترنت.

لكن GitHub يستخدم Git لتوفير التعاون عبر الإنترنت واستضافة المستودعات.

---

## 🚀 كيف يعمل Git و GitHub معًا؟

سير العمل الشائع يكون بهذا الشكل:

```text
جهاز الكمبيوتر الخاص بك
        ↓
       Git
        ↓
حفظ التغييرات Commit
        ↓
     GitHub
        ↓
المشاركة والتعاون
```

على سبيل المثال:

```bash
git add .
git commit -m "Add login page"
git push
```

أول أمرين هما أوامر Git.

أما الأمر `git push` فيرسل الـ commits الموجودة على جهازك إلى مستودع بعيد (Remote Repository)، مثل مستودع مستضاف على GitHub.

---

## ⚠️ ملاحظة مهمة

ليس من الضروري استخدام Git وGitHub معًا.

**Git** هو نظام التحكم في الإصدارات.

أما **GitHub** فهو إحدى المنصات التي يمكنها استضافة مستودعات Git.

ومن المنصات الأخرى:

- GitLab
- Bitbucket
