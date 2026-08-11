# 🍒 Git Cherry Pick

## 🌐 English

`git cherry-pick` is used to apply the changes introduced by an existing commit to the current branch.

It allows you to select a specific commit from another branch without merging the entire branch.

---

## 🔹 Basic Usage

To cherry-pick a specific commit:

```bash
git cherry-pick commit-hash
```

Replace `commit-hash` with the ID of the commit you want to apply.

---

## 🔹 Find the Commit ID

You can view your commit history using:

```bash
git log --oneline
```

Example:

```text
a1b2c3d Fix login validation
e4f5g6h Update homepage
h7i8j9k Add navigation menu
```

You can then use the commit ID:

```bash
git cherry-pick a1b2c3d
```

---

## 🔹 Cherry Pick from Another Branch

Suppose you have two branches:

```text
main
feature-login
```

The `feature-login` branch contains a commit that you want to apply to `main`.

First, switch to `main`:

```bash
git switch main
```

Then cherry-pick the desired commit:

```bash
git cherry-pick commit-hash
```

Git applies the changes from that commit to `main`.

---

## 🔹 What Happens After Cherry Pick?

Cherry Pick creates a new commit on the current branch.

For example:

```text
feature-login:

A -- B -- C
         ↑
      Fix Login
```

After cherry-picking `C` into `main`:

```text
main:

A -- B -- C'
```

The changes are similar, but `C'` is a new commit with a different commit ID.

---

## 🔹 Check the Result

After cherry-picking, you can check the history:

```bash
git log --oneline
```

You can also check the repository status:

```bash
git status
```

---

## ⚠️ Important Note

Cherry Pick does not move the original commit.

Instead, Git creates a new commit containing the same changes on the current branch.

---

## 💡 When to Use Cherry Pick

Cherry Pick is useful when:

- You need one specific commit from another branch
- You want to apply a bug fix to another branch
- You do not want to merge an entire branch
- You need to move a small change between branches

---

## 📝 Summary

The basic command is:

```bash
git cherry-pick commit-hash
```

Cherry Pick allows you to selectively apply a specific commit to another branch without merging the entire branch.

---

# 🇵🇸 العربية

# 🍒 Git Cherry Pick

## العربية

يُستخدم الأمر `git cherry-pick` لتطبيق التغييرات التي تم إدخالها بواسطة Commit موجود على الفرع الحالي.

يسمح لك باختيار Commit محدد من فرع آخر دون الحاجة إلى دمج الفرع بالكامل.

---

## 🔹 الاستخدام الأساسي

لتطبيق Commit محدد:

```bash
git cherry-pick commit-hash
```

استبدل `commit-hash` بمعرّف الـ Commit الذي تريد تطبيقه.

---

## 🔹 العثور على Commit ID

يمكنك عرض سجل الـ Commits باستخدام:

```bash
git log --oneline
```

مثال:

```text
a1b2c3d Fix login validation
e4f5g6h Update homepage
h7i8j9k Add navigation menu
```

بعد ذلك يمكنك استخدام معرّف الـ Commit:

```bash
git cherry-pick a1b2c3d
```

---

## 🔹 Cherry Pick من فرع آخر

لنفترض أن لديك فرعين:

```text
main
feature-login
```

ويحتوي فرع `feature-login` على Commit تريد تطبيقه على `main`.

أولًا، انتقل إلى `main`:

```bash
git switch main
```

ثم قم بتطبيق الـ Commit المطلوب:

```bash
git cherry-pick commit-hash
```

يقوم Git بتطبيق التغييرات الموجودة في ذلك الـ Commit على فرع `main`.

---

## 🔹 ماذا يحدث بعد Cherry Pick؟

يقوم Cherry Pick بإنشاء Commit جديد على الفرع الحالي.

على سبيل المثال:

```text
feature-login:

A -- B -- C
         ↑
      Fix Login
```

بعد تطبيق `C` على `main` باستخدام Cherry Pick:

```text
main:

A -- B -- C'
```

تكون التغييرات متشابهة، ولكن `C'` هو Commit جديد وله Commit ID مختلف.

---

## 🔹 التحقق من النتيجة

بعد تنفيذ Cherry Pick، يمكنك التحقق من سجل Commits:

```bash
git log --oneline
```

ويمكنك أيضًا التحقق من حالة المستودع:

```bash
git status
```

---

## ⚠️ ملاحظة مهمة

لا يقوم Cherry Pick بنقل الـ Commit الأصلي.

بدلًا من ذلك، ينشئ Git Commit جديدًا يحتوي على نفس التغييرات على الفرع الحالي.

---

## 💡 متى نستخدم Cherry Pick؟

يكون Cherry Pick مفيدًا عندما:

- تحتاج إلى Commit محدد من فرع آخر
- تريد تطبيق إصلاح لمشكلة على فرع آخر
- لا تريد دمج الفرع بالكامل
- تحتاج إلى نقل تغيير صغير بين الفروع

---

## 📝 الخلاصة

الأمر الأساسي هو:

```bash
git cherry-pick commit-hash
```

يسمح لك Cherry Pick بتطبيق Commit محدد بشكل انتقائي على فرع آخر دون الحاجة إلى دمج الفرع بالكامل.
