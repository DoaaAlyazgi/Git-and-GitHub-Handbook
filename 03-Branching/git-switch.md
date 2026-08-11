# 🔀 Git Switch

## 🌐 English

`git switch` is used to switch between branches in a Git repository.

It can also be used to create a new branch and switch to it immediately.

---

## 🔹 View Your Current Branch

To see which branch you are currently on:

```bash
git branch
```

The current branch is marked with an asterisk `*`.

Example:

```text
* main
  feature-login
```

---

## 🔹 Switch to an Existing Branch

To switch to an existing branch:

```bash
git switch feature-login
```

This changes your current branch to `feature-login`.

---

## 🔹 Create and Switch to a New Branch

To create a new branch and switch to it immediately:

```bash
git switch -c feature-login
```

This is a convenient alternative to running:

```bash
git branch feature-login
git switch feature-login
```

---

## 🔹 Switch Back to the Main Branch

To return to the `main` branch:

```bash
git switch main
```

---

## 🔹 Switch to a Remote Branch

If a remote branch already exists and you want to create a local branch that tracks it:

```bash
git switch --track origin/feature-login
```

Git creates a local branch named `feature-login` and connects it to the remote branch.

---

## 🔹 Common Workflow

A typical workflow might look like this:

```bash
git switch -c feature-login
```

Make your changes:

```bash
git add .
git commit -m "Add login feature"
```

Return to the main branch:

```bash
git switch main
```

---

## 💡 Why Use `git switch`?

`git switch` makes branch switching easier and clearer.

It is specifically designed for working with branches, which makes it easier to understand than using `git checkout` for the same task.

---

## 📝 Summary

The most common `git switch` commands are:

```bash
git switch branch-name
```

Switch to an existing branch.

```bash
git switch -c branch-name
```

Create a new branch and switch to it.

```bash
git switch main
```

Switch back to the main branch.

---

# 🇵🇸 العربية

# 🔀 Git Switch

يُستخدم الأمر `git switch` للتنقل بين الفروع داخل مستودع Git.

ويمكن استخدامه أيضًا لإنشاء فرع جديد والانتقال إليه مباشرة.

---

## 🔹 معرفة الفرع الحالي

لمعرفة الفرع الذي تعمل عليه حاليًا:

```bash
git branch
```

يتم وضع علامة النجمة `*` بجانب الفرع الحالي.

مثال:

```text
* main
  feature-login
```

---

## 🔹 الانتقال إلى فرع موجود

للانتقال إلى فرع موجود:

```bash
git switch feature-login
```

ينقلك هذا الأمر إلى الفرع `feature-login`.

---

## 🔹 إنشاء فرع جديد والانتقال إليه

لإنشاء فرع جديد والانتقال إليه مباشرة:

```bash
git switch -c feature-login
```

وهذه طريقة مختصرة بدلًا من تنفيذ:

```bash
git branch feature-login
git switch feature-login
```

---

## 🔹 العودة إلى الفرع الرئيسي

للعودة إلى فرع `main`:

```bash
git switch main
```

---

## 🔹 الانتقال إلى فرع موجود على المستودع البعيد

إذا كان هناك فرع بعيد موجود وتريد إنشاء فرع محلي مرتبط به:

```bash
git switch --track origin/feature-login
```

يقوم Git بإنشاء فرع محلي باسم `feature-login` وربطه بالفرع الموجود على المستودع البعيد.

---

## 🔹 سير العمل الشائع

يمكن أن يكون سير العمل المعتاد بالشكل التالي:

```bash
git switch -c feature-login
```

قم بإجراء التغييرات:

```bash
git add .
git commit -m "Add login feature"
```

ثم ارجع إلى الفرع الرئيسي:

```bash
git switch main
```

---

## 💡 لماذا نستخدم `git switch`؟

يجعل `git switch` عملية التنقل بين الفروع أسهل وأكثر وضوحًا.

وهو مصمم خصيصًا للتعامل مع الفروع، مما يجعله أوضح من استخدام `git checkout` لنفس الغرض.

---

## 📝 الخلاصة

أهم أوامر `git switch` هي:

```bash
git switch branch-name
```

للانتقال إلى فرع موجود.

```bash
git switch -c branch-name
```

لإنشاء فرع جديد والانتقال إليه.

```bash
git switch main
```

للعودة إلى الفرع الرئيسي.
