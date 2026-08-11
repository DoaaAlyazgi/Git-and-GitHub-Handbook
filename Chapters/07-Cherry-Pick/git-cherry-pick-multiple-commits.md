# 🍒 Git Cherry Pick Multiple Commits

## 🌐 English

Git allows you to cherry-pick multiple commits and apply their changes to the current branch.

This is useful when you need several specific changes from another branch without merging the entire branch.

---

## 🔹 Cherry Pick Multiple Commits

You can specify multiple commit IDs:

```bash
git cherry-pick commit1 commit2 commit3
```

Git applies the commits in the order you provide.

---

## 🔹 Example

Suppose you have:

```text
a1b2c3d Fix login
e4f5g6h Update dashboard
h7i8j9k Fix navigation
```

You can apply the first and third commits:

```bash
git cherry-pick a1b2c3d h7i8j9k
```

---

## 🔹 Cherry Pick a Range

You can also cherry-pick a range of commits:

```bash
git cherry-pick A..D
```

This applies the commits after `A` up to and including `D`.

For example:

```bash
git cherry-pick a1b2c3d..h7i8j9k
```

---

## ⚠️ Important Note

When using a range, make sure you understand which commits are included.

You can inspect the history first:

```bash
git log --oneline
```

---

## 💡 When to Use It

Cherry-picking multiple commits is useful when:

- You need several related fixes
- You want to move a group of changes
- You do not want to merge an entire branch

---

## 📝 Summary

```bash
git cherry-pick commit1 commit2
```

Applies multiple selected commits.

```bash
git cherry-pick A..D
```

Applies a range of commits after `A` through `D`.

---

# 🇵🇸 العربية

# 🍒 Git Cherry Pick Multiple Commits

## العربية

يسمح لك Git بتطبيق عدة Commits باستخدام Cherry Pick ونقل تغييراتها إلى الفرع الحالي.

يكون هذا مفيدًا عندما تحتاج إلى عدة تغييرات محددة من فرع آخر دون دمج الفرع بالكامل.

---

## 🔹 تطبيق عدة Commits

يمكنك تحديد عدة Commit IDs:

```bash
git cherry-pick commit1 commit2 commit3
```

يقوم Git بتطبيق الـ Commits بالترتيب الذي تحدده.

---

## 🔹 مثال

لنفترض أن لديك:

```text
a1b2c3d Fix login
e4f5g6h Update dashboard
h7i8j9k Fix navigation
```

يمكنك تطبيق الـ Commit الأول والثالث:

```bash
git cherry-pick a1b2c3d h7i8j9k
```

---

## 🔹 تطبيق مجموعة من Commits

يمكنك أيضًا تطبيق مجموعة من Commits:

```bash
git cherry-pick A..D
```

يقوم هذا بتطبيق الـ Commits التي تأتي بعد `A` وحتى `D`.

مثال:

```bash
git cherry-pick a1b2c3d..h7i8j9k
```

---

## ⚠️ ملاحظة مهمة

عند استخدام نطاق من Commits، تأكد من فهم الـ Commits التي سيتم تطبيقها.

يمكنك مراجعة السجل أولًا:

```bash
git log --oneline
```

---

## 💡 متى نستخدمه؟

يكون تطبيق عدة Commits مفيدًا عندما:

- تحتاج إلى عدة إصلاحات مرتبطة
- تريد نقل مجموعة من التغييرات
- لا تريد دمج فرع كامل

---

## 📝 الخلاصة

```bash
git cherry-pick commit1 commit2
```

لتطبيق عدة Commits محددة.

```bash
git cherry-pick A..D
```

لتطبيق مجموعة من Commits بعد `A` وحتى `D`.
