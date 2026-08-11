# 📋 Git Stash List

## 🌐 English

`git stash list` is used to display all stashes currently saved in your local Git repository.

Each stash is assigned a reference such as `stash@{0}`, `stash@{1}`, and so on.

---

## 🔹 Basic Usage

To view all saved stashes:

```bash
git stash list
```

Example:

```text
stash@{0}: On main: Work in progress
stash@{1}: On feature-login: Update login page
stash@{2}: On development: Fix navigation
```

The most recent stash is usually `stash@{0}`.

---

## 🔹 Understanding the Stash Reference

A stash reference looks like:

```text
stash@{0}
```

The number identifies the stash.

For example:

```text
stash@{0}
```

means the latest stash.

```text
stash@{1}
```

means the stash before it.

---

## 🔹 Apply a Specific Stash

You can apply a specific stash using its reference:

```bash
git stash apply stash@{1}
```

---

## 🔹 Remove a Specific Stash

You can remove a specific stash using:

```bash
git stash drop stash@{1}
```

---

## 💡 Example Workflow

View your stashes:

```bash
git stash list
```

Choose a stash:

```bash
git stash apply stash@{1}
```

Check your changes:

```bash
git status
```

---

## 📝 Summary

`git stash list` helps you see and identify your saved stashes.

Common commands:

```bash
git stash list
git stash apply stash@{1}
git stash drop stash@{1}
```

---

# 🇵🇸 العربية

# 📋 Git Stash List

## العربية

يُستخدم الأمر `git stash list` لعرض جميع الـ Stashes المحفوظة حاليًا في مستودع Git المحلي.

يتم إعطاء كل Stash مرجعًا مثل `stash@{0}` و`stash@{1}` وهكذا.

---

## 🔹 الاستخدام الأساسي

لعرض جميع الـ Stashes المحفوظة:

```bash
git stash list
```

مثال:

```text
stash@{0}: On main: Work in progress
stash@{1}: On feature-login: Update login page
stash@{2}: On development: Fix navigation
```

عادةً يكون أحدث Stash هو `stash@{0}`.

---

## 🔹 فهم مرجع Stash

يكون مرجع الـ Stash بالشكل التالي:

```text
stash@{0}
```

يمثل الرقم ترتيب الـ Stash.

مثلًا:

```text
stash@{0}
```

يعني أحدث Stash.

```text
stash@{1}
```

يعني الـ Stash الذي يسبقه.

---

## 🔹 تطبيق Stash محدد

يمكنك تطبيق Stash محدد باستخدام مرجعه:

```bash
git stash apply stash@{1}
```

---

## 🔹 حذف Stash محدد

يمكنك حذف Stash محدد باستخدام:

```bash
git stash drop stash@{1}
```

---

## 💡 مثال على سير العمل

اعرض الـ Stashes:

```bash
git stash list
```

اختر Stash معينًا:

```bash
git stash apply stash@{1}
```

تحقق من التغييرات:

```bash
git status
```

---

## 📝 الخلاصة

يساعدك `git stash list` على رؤية الـ Stashes المحفوظة ومعرفة كل واحد منها.

الأوامر الشائعة:

```bash
git stash list
git stash apply stash@{1}
git stash drop stash@{1}
```
