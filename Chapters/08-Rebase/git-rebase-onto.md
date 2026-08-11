# 🎯 Git Rebase Onto

## 🌐 English

`git rebase --onto` allows you to move a specific range of commits and reapply them onto another base.

It is useful when you want more control over which commits are rebased.

---

## 🔹 Basic Usage

```bash
git rebase --onto new-base old-base branch
```

Git takes the commits after `old-base` from `branch` and reapplies them onto `new-base`.

---

## 🔹 Example

Suppose you have:

```text
A -- B -- C -- D
     \
      E -- F
```

You want to move `E` and `F` onto `C`.

You can use:

```bash
git rebase --onto C B feature-branch
```

The result becomes:

```text
A -- B -- C -- E' -- F'
```

---

## 💡 When to Use It

`git rebase --onto` is useful when:

- You want to move a specific group of commits
- A branch was created from the wrong base
- You need to change the base of a feature branch
- You want more precise control over a rebase

---

## ⚠️ Important Note

The syntax can be confusing at first.

Always inspect your commit history before using it:

```bash
git log --oneline --graph
```

---

## 📝 Summary

```bash
git rebase --onto new-base old-base branch
```

This allows you to selectively move commits from one base to another.

---

# 🇵🇸 العربية

# 🎯 Git Rebase Onto

## العربية

يسمح لك `git rebase --onto` بنقل مجموعة محددة من Commits وإعادة تطبيقها فوق قاعدة أخرى.

يكون هذا مفيدًا عندما تريد تحكمًا أكبر في الـ Commits التي سيتم عمل Rebase لها.

---

## 🔹 الاستخدام الأساسي

```bash
git rebase --onto new-base old-base branch
```

يقوم Git بأخذ الـ Commits الموجودة بعد `old-base` من `branch` وإعادة تطبيقها فوق `new-base`.

---

## 🔹 مثال

لنفترض أن لديك:

```text
A -- B -- C -- D
     \
      E -- F
```

وتريد نقل `E` و `F` فوق `C`.

يمكنك استخدام:

```bash
git rebase --onto C B feature-branch
```

تصبح النتيجة:

```text
A -- B -- C -- E' -- F'
```

---

## 💡 متى نستخدمه؟

يكون `git rebase --onto` مفيدًا عندما:

- تريد نقل مجموعة محددة من Commits
- تم إنشاء فرع من قاعدة غير صحيحة
- تحتاج إلى تغيير قاعدة فرع يحتوي على ميزة
- تريد تحكمًا أكثر دقة في عملية Rebase

---

## ⚠️ ملاحظة مهمة

قد تبدو صيغة الأمر مربكة في البداية.

لذلك من الأفضل دائمًا مراجعة سجل Commits قبل استخدامه:

```bash
git log --oneline --graph
```

---

## 📝 الخلاصة

```bash
git rebase --onto new-base old-base branch
```

يسمح لك هذا الأمر بنقل Commits بشكل انتقائي من قاعدة إلى قاعدة أخرى.
