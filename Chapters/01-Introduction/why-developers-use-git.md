# 📌 What is Version Control?

---

# 🌐 English

## 📌 Definition

Version Control is a system that helps developers **track, manage, and organize changes** made to files over time.

It keeps a history of your project so you can understand:

- What changed?
- When did it change?
- Who made the change?
- Why was the change made?
- Can we return to an earlier version?

Git is one of the most popular **Version Control Systems (VCS)** used by developers around the world.

---

## 💡 Why Do We Need Version Control?

Imagine that you are working on a project and making many changes every day.

Without Version Control, you might create files like:

```text
project-final.zip
project-final-v2.zip
project-final-v3.zip
project-final-really-final.zip
project-final-really-final-v2.zip
```

😅 After a while, it becomes difficult to know which version is the correct one.

This is where **Version Control** becomes useful.

Instead of manually creating multiple copies of your project, Git keeps track of your changes and maintains a history of your project.

---

## 🚀 What Does Version Control Allow You to Do?

Using a Version Control System, you can:

- 📝 Track changes made to your files.
- 🕐 Keep a history of your project.
- 🔍 See exactly what changed between versions.
- ↩️ Return to an earlier version when necessary.
- 🌿 Work on different features using branches.
- 👥 Collaborate with other developers.
- 🛡️ Reduce the risk of losing important work.
- 📦 Manage different versions of your project.

---

## 🧠 Think of Version Control as a Time Machine

A simple way to understand Version Control is to think of it as a **time machine for your code**.

Imagine that your project goes through several versions:

```text
Version 1 → Version 2 → Version 3 → Version 4
```

Later, you discover that something is broken in Version 4.

Without Version Control, finding the previous working version could be difficult.

With Version Control, you can review your project's history and return to an earlier version when necessary.

In simple words:

> Version Control gives your project a history that you can inspect and use whenever you need it.

---

## 🔄 How Does Version Control Work?

A simplified Version Control workflow looks like this:

```text
Make Changes
     ↓
Track Changes
     ↓
Save a Version
     ↓
Make More Changes
     ↓
Save Another Version
     ↓
Review History
     ↓
Return to an Earlier Version if Needed
```

In Git, saving a version of your changes is called creating a **commit**.

We will learn more about commits in later chapters.

---

## 👥 Version Control and Teamwork

Version Control becomes even more important when multiple developers work on the same project.

For example:

```text
Developer A → Login
Developer B → Dashboard
Developer C → Payment System
```

Each developer can work on their own changes without constantly overwriting the work of others.

Git provides tools such as **branches** and **merging** to help developers manage this process.

---

## 🌿 What is a Branch?

A branch allows you to work on a feature or change separately from the main project.

For example:

```text
main
 │
 ├── feature-login
 │
 ├── feature-dashboard
 │
 └── bugfix-payment
```

Developers can use branches to:

- Build new features.
- Experiment with ideas.
- Fix bugs.
- Work independently from the main branch.

Branches will be explained in detail in a later chapter.

---

## 🔍 Version Control vs. Manual Backups

Version Control is different from simply creating backups.

A manual backup might look like:

```text
project-backup-1
project-backup-2
project-backup-3
```

But Version Control records meaningful information about changes.

For example:

```text
Commit 1
Added login page

Commit 2
Added registration form

Commit 3
Fixed login validation

Commit 4
Added password reset
```

This makes it much easier to understand how the project evolved over time.

---

## 🧩 Version Control Systems

There are different Version Control Systems.

Some examples include:

- Git
- Subversion (SVN)
- Mercurial
- Perforce

Git is one of the most widely used Version Control Systems in modern software development.

---

## 🆚 Git vs. Version Control

It is important to understand the difference.

**Version Control** is the concept or system used to track and manage changes.

**Git** is a specific tool that implements Version Control.

Think of it like this:

```text
Version Control
      ↓
The concept / system
      ↓
Git
      ↓
A tool used to implement it
```

So when someone says:

> "I use Git for Version Control."

They mean that Git is the tool they use to track and manage changes in their projects.

---

## 📌 Key Takeaways

Remember these important points:

1. Version Control tracks changes over time.
2. It keeps a history of your project.
3. It allows you to return to previous versions.
4. It helps developers collaborate.
5. Branches allow developers to work on separate features.
6. Git is a Version Control System.
7. Git makes project history easier to manage.

---

## 🧪 Quick Practice

Before moving to the next topic, try to answer:

1. What is Version Control?
2. Why do developers need Version Control?
3. What is the difference between Git and Version Control?
4. Why are branches useful?
5. What is a commit?

---

# 🇵🇸 العربية

## 📌 التعريف

نظام التحكم بالإصدارات **(Version Control)** هو نظام يساعد المطورين على **تتبع وإدارة وتنظيم التغييرات** التي يتم إجراؤها على الملفات مع مرور الوقت.

يقوم بالاحتفاظ بتاريخ المشروع حتى تتمكن من معرفة:

- ما الذي تغير؟
- متى حدث التغيير؟
- من قام بالتغيير؟
- لماذا حدث التغيير؟
- هل يمكننا العودة إلى نسخة سابقة؟

ويُعد **Git** واحدًا من أشهر **أنظمة التحكم بالإصدارات (VCS)** المستخدمة من قبل المطورين حول العالم.

---

## 💡 لماذا نحتاج إلى Version Control؟

تخيل أنك تعمل على مشروع وتقوم بإجراء العديد من التعديلات عليه كل يوم.

بدون Version Control، قد تبدأ بإنشاء ملفات مثل:

```text
project-final.zip
project-final-v2.zip
project-final-v3.zip
project-final-really-final.zip
project-final-really-final-v2.zip
```

😅 بعد فترة، يصبح من الصعب معرفة أي نسخة هي النسخة الصحيحة.

وهنا يأتي دور **Version Control**.

بدلًا من إنشاء نسخ متعددة من المشروع بشكل يدوي، يقوم Git بتتبع التغييرات والاحتفاظ بتاريخ المشروع.

---

## 🚀 ماذا يسمح لك Version Control أن تفعل؟

باستخدام نظام التحكم بالإصدارات، يمكنك:

- 📝 تتبع التغييرات التي تحدث على الملفات.
- 🕐 الاحتفاظ بتاريخ المشروع.
- 🔍 معرفة التغييرات التي حدثت بين الإصدارات.
- ↩️ العودة إلى نسخة سابقة عند الحاجة.
- 🌿 العمل على ميزات مختلفة باستخدام Branches.
- 👥 التعاون مع مطورين آخرين.
- 🛡️ تقليل خطر فقدان العمل المهم.
- 📦 إدارة الإصدارات المختلفة من المشروع.

---

## 🧠 تخيل Version Control كأنه آلة زمن للكود

طريقة بسيطة لفهم Version Control هي أن تتخيله كأنه **آلة زمن للكود**.

تخيل أن مشروعك يمر بعدة إصدارات:

```text
الإصدار 1 → الإصدار 2 → الإصدار 3 → الإصدار 4
```

بعد ذلك تكتشف أن هناك مشكلة في الإصدار الرابع.

بدون Version Control، قد يكون من الصعب العثور على النسخة السابقة التي كانت تعمل بشكل صحيح.

أما باستخدام Version Control، فيمكنك مراجعة تاريخ المشروع والعودة إلى نسخة سابقة عند الحاجة.

ببساطة:

> Version Control يمنح مشروعك تاريخًا يمكنك مراجعته والرجوع إليه في أي وقت تحتاجه.

---

## 🔄 كيف يعمل Version Control؟

يمكن تبسيط طريقة عمل Version Control بالشكل التالي:

```text
إجراء تغييرات
     ↓
تتبع التغييرات
     ↓
حفظ نسخة
     ↓
إجراء تغييرات جديدة
     ↓
حفظ نسخة أخرى
     ↓
مراجعة تاريخ المشروع
     ↓
العودة إلى نسخة سابقة عند الحاجة
```

في Git، تُسمى عملية حفظ نسخة من التغييرات **Commit**.

وسنتعلم المزيد عن الـ Commits في الفصول القادمة.

---

## 👥 Version Control والعمل الجماعي

يصبح Version Control أكثر أهمية عندما يعمل عدة مطورين على نفس المشروع.

على سبيل المثال:

```text
المطور A → تسجيل الدخول
المطور B → لوحة التحكم
المطور C → نظام الدفع
```

يمكن لكل مطور العمل على التغييرات الخاصة به دون الكتابة فوق عمل المطورين الآخرين باستمرار.

يوفر Git أدوات مثل **Branches** و **Merging** لمساعدة المطورين على إدارة هذه العملية.

---

## 🌿 ما هو الـ Branch؟

الـ **Branch** يسمح لك بالعمل على ميزة أو تعديل بشكل منفصل عن المشروع الرئيسي.

على سبيل المثال:

```text
main
 │
 ├── feature-login
 │
 ├── feature-dashboard
 │
 └── bugfix-payment
```

يمكن للمطورين استخدام الـ Branches من أجل:

- تطوير ميزات جديدة.
- تجربة أفكار مختلفة.
- إصلاح الأخطاء.
- العمل بشكل مستقل عن الفرع الرئيسي.

وسنتعلم الـ Branches بالتفصيل في فصل لاحق.

---

## 🔍 Version Control مقابل النسخ الاحتياطية اليدوية

Version Control يختلف عن مجرد إنشاء نسخ احتياطية.

قد تكون النسخ الاحتياطية اليدوية بهذا الشكل:

```text
project-backup-1
project-backup-2
project-backup-3
```

لكن Version Control يقوم بتسجيل معلومات مهمة عن التغييرات.

على سبيل المثال:

```text
Commit 1
إضافة صفحة تسجيل الدخول

Commit 2
إضافة نموذج التسجيل

Commit 3
إصلاح التحقق من تسجيل الدخول

Commit 4
إضافة إعادة تعيين كلمة المرور
```

وهذا يجعل من السهل جدًا فهم كيفية تطور المشروع مع مرور الوقت.

---

## 🧩 أنظمة التحكم بالإصدارات

هناك العديد من أنظمة التحكم بالإصدارات.

من أمثلتها:

- Git
- Subversion (SVN)
- Mercurial
- Perforce

ويُعد Git واحدًا من أكثر أنظمة التحكم بالإصدارات استخدامًا في تطوير البرمجيات الحديث.

---

## 🆚 ما الفرق بين Git و Version Control؟

من المهم فهم الفرق بين الاثنين.

**Version Control** هو المفهوم أو النظام المستخدم لتتبع وإدارة التغييرات.

أما **Git** فهو أداة محددة تستخدم لتطبيق نظام التحكم بالإصدارات.

يمكنك التفكير في الأمر بهذا الشكل:

```text
Version Control
      ↓
المفهوم / النظام
      ↓
Git
      ↓
أداة تستخدم لتطبيق النظام
```

لذلك عندما يقول شخص:

> "I use Git for Version Control."

فهو يقصد أنه يستخدم Git كأداة لتتبع وإدارة التغييرات في مشاريعه.

---

## 📌 أهم النقاط

تذكر هذه النقاط الأساسية:

1. Version Control يتتبع التغييرات مع مرور الوقت.
2. يحتفظ بتاريخ المشروع.
3. يسمح لك بالعودة إلى إصدارات سابقة.
4. يساعد المطورين على التعاون.
5. Branches تسمح للمطورين بالعمل على ميزات منفصلة.
6. Git هو نظام للتحكم بالإصدارات.
7. Git يجعل إدارة تاريخ المشروع أسهل.

---

## 🧪 تدريب سريع

قبل الانتقال إلى الموضوع التالي، حاول الإجابة عن الأسئلة التالية:

1. ما هو Version Control؟
2. لماذا يحتاج المطورون إلى Version Control؟
3. ما الفرق بين Git و Version Control؟
4. لماذا نستخدم Branches؟
5. ما هو الـ Commit؟

---

## 🎯 Next Step | الخطوة التالية

**English:**  
In the next section, we will learn more about Git and understand how Git works in practice.

**العربية:**  
في القسم القادم سنتعرف بشكل أعمق على Git وسنفهم كيف يعمل Git بشكل عملي.

> 🚀 **Learn Git by Doing, Not Just Reading.**
>
> 🚀 **تعلم Git بالممارسة، وليس بالقراءة فقط.**
