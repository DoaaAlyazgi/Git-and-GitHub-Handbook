# 📌 What is Version Control?

---

## 🌐 English

Version Control is a system that helps developers **track, manage, and organize changes** made to files over time.

It allows you to keep a history of your project, understand what changed, and return to an earlier version when necessary.

Git is one of the most popular Version Control Systems (VCS).

---

## 💡 Why Do We Need Version Control?

Imagine you are working on a project and you make several changes.

You might create files like:

```text
project-final.zip
project-final-v2.zip
project-final-v3.zip
project-final-really-final.zip
project-final-really-final-v2.zip
```

😅 This quickly becomes confusing.

With Version Control, you don't need to manually create multiple copies of your project.

Instead, Git keeps track of your changes and maintains a history of your project.

---

## 🚀 What Does Version Control Allow You To Do?

With Version Control, you can:

- 📝 Track changes to your files.
- 🕐 Keep a history of your project.
- 🔍 See what changed between versions.
- ↩️ Return to an earlier version when needed.
- 🌿 Work on new features without affecting the main project.
- 👥 Collaborate with other developers.
- 🛡️ Recover from mistakes more safely.

---

## 🔄 A Simple Example

Imagine you are building a website.

### Version 1

```text
Home page
About page
Contact page
```

You save this version using Git.

Later, you add a login system.

### Version 2

```text
Home page
About page
Contact page
Login system
```

After that, you modify the login system, but your changes accidentally break it.

With Version Control, you can inspect the project's history and return to an earlier working version.

This is one of the main reasons developers use Git.

---

## 🧠 Version Control vs. Git

Version Control is the **concept and system** used to manage different versions of a project.

Git is a **tool that implements Version Control**.

Think of it like this:

```text
Version Control
      │
      ├── Git
      ├── Subversion (SVN)
      └── Mercurial
```

Git is one of the most widely used Version Control Systems today.

---

## 🛠️ Git Example

A basic Git workflow might look like this:

```bash
git add .
git commit -m "Add login system"
```

The `git commit` command creates a **snapshot** of your project at that point in time.

Later, you can view the project's history using:

```bash
git log
```

---

## 📌 Key Takeaway

> Version Control helps you track the history of your project and manage changes safely and efficiently.

Throughout this handbook, we will use **Git** to practice Version Control and learn how to manage projects properly.

---

## 🎯 Practical Exercise

Try to answer these questions:

1. Why do developers need Version Control?
2. What problem does Version Control solve?
3. What is the difference between Version Control and Git?
4. What does `git commit` do?
5. Which command can you use to view the project's history?

Try answering these questions before moving to the next lesson.

---

# 🌐 العربية

## ما هو نظام التحكم بالإصدارات؟

**Version Control** أو **نظام التحكم بالإصدارات** هو نظام يساعد المطورين على **تتبع وإدارة وتنظيم التغييرات** التي تحدث على ملفات المشروع مع مرور الوقت.

يسمح لك بالاحتفاظ بتاريخ المشروع ومعرفة ما الذي تغير، ومراجعة الإصدارات السابقة، والرجوع إلى إصدار سابق عند الحاجة.

ويُعتبر **Git** واحدًا من أشهر أنظمة التحكم بالإصدارات.

---

## 💡 لماذا نحتاج إلى Version Control؟

تخيلي أنك تعملين على مشروع وقمتِ بإجراء العديد من التعديلات.

قد ينتهي بك الأمر بملفات مثل:

```text
project-final.zip
project-final-v2.zip
project-final-v3.zip
project-final-really-final.zip
project-final-really-final-v2.zip
```

😅 بعد فترة يصبح من الصعب معرفة أي نسخة هي الصحيحة.

هنا يأتي دور Version Control.

بدلًا من إنشاء نسخ متعددة من المشروع يدويًا، يقوم Git بتتبع التغييرات والاحتفاظ بتاريخ المشروع.

---

## 🚀 ماذا يسمح لك Version Control أن تفعلي؟

باستخدام نظام التحكم بالإصدارات يمكنك:

- 📝 تتبع التغييرات التي تحدث على الملفات.
- 🕐 الاحتفاظ بتاريخ المشروع.
- 🔍 معرفة الفرق بين الإصدارات.
- ↩️ الرجوع إلى إصدار سابق عند الحاجة.
- 🌿 العمل على ميزات جديدة دون التأثير على المشروع الأساسي.
- 👥 التعاون مع مطورين آخرين.
- 🛡️ التعامل مع الأخطاء واستعادة حالة سابقة من المشروع.

---

## 🔄 مثال بسيط

لنفترض أنك تعملين على موقع إلكتروني.

### الإصدار الأول

```text
الصفحة الرئيسية
صفحة من نحن
صفحة التواصل
```

قمتِ بحفظ هذه الحالة باستخدام Git.

بعد ذلك أضفتِ نظام تسجيل الدخول.

### الإصدار الثاني

```text
الصفحة الرئيسية
صفحة من نحن
صفحة التواصل
نظام تسجيل الدخول
```

لاحقًا قمتِ بتعديل نظام تسجيل الدخول، ولكن التعديل تسبب في حدوث مشكلة.

باستخدام Version Control يمكنك مراجعة تاريخ المشروع ومعرفة النسخة السابقة والرجوع إلى حالة كانت تعمل بشكل صحيح.

وهذه واحدة من أهم فوائد Git.

---

## 🧠 ما الفرق بين Version Control و Git؟

**Version Control** هو المفهوم أو النظام الذي نستخدمه لإدارة إصدارات المشروع.

أما **Git** فهو أداة تستخدم لتطبيق هذا النظام.

يمكننا تبسيط الفكرة هكذا:

```text
Version Control
      │
      ├── Git
      ├── Subversion (SVN)
      └── Mercurial
```

ويُعد Git من أشهر أدوات Version Control المستخدمة حاليًا.

---

## 🛠️ مثال باستخدام Git

يمكن أن يكون سير العمل الأساسي باستخدام Git بهذا الشكل:

```bash
git add .
git commit -m "Add login system"
```

الأمر `git commit` يقوم بإنشاء **لقطة Snapshot** لحالة المشروع في تلك اللحظة.

وبعد ذلك يمكنك مشاهدة تاريخ التغييرات باستخدام:

```bash
git log
```

---

## 📌 الخلاصة

> Version Control يساعدك على تتبع تاريخ مشروعك وإدارة التغييرات بطريقة آمنة ومنظمة.

وفي هذا الـHandbook سنستخدم **Git** عمليًا لتعلم كيفية إدارة إصدارات المشاريع والتعامل مع التغييرات.

---

## 🎯 تمرين عملي

حاولي الإجابة عن الأسئلة التالية:

1. لماذا يحتاج المطورون إلى Version Control؟
2. ما المشكلة التي يحلها Version Control؟
3. ما الفرق بين Version Control و Git؟
4. ماذا يفعل الأمر `git commit`؟
5. ما الأمر الذي يمكنك استخدامه لعرض تاريخ المشروع؟

حاولي الإجابة عن هذه الأسئلة قبل الانتقال إلى الدرس التالي.
