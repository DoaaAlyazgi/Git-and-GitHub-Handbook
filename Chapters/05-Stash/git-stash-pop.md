# 📤 Git Stash Pop

## 🌐 English

`git stash pop` is used to restore the latest stashed changes and remove that stash from the stash list.

It is useful when you temporarily saved your work and are now ready to continue working on it.

---

## 🔹 Basic Usage

To apply the latest stash:

```bash
git stash pop
```

Git restores the changes and removes the stash from the stash list.

---

## 🔹 Apply a Specific Stash

You can apply a specific stash:

```bash
git stash pop stash@{1}
```

This restores the selected stash and removes it from the stash list if the operation succeeds.

---

## 🔹 What Happens If a Conflict Occurs?

Sometimes applying a stash can result in conflicts.

Check the repository status:

```bash
git status
```

Resolve the conflicts manually, then stage the resolved files:

```bash
git add .
```

You can then continue working or create a commit.

---

## 🔹 `git stash pop` vs `git stash apply`

The main difference is:

```bash
git stash pop
```

Restores the stash and removes it from the stash list.

While:

```bash
git stash apply
```

Restores the stash but keeps it in the stash list.

---

## 💡 Example Workflow

Save your changes:

```bash
git stash
```

Switch branches:

```bash
git switch main
```

Return later:

```bash
git switch feature-login
```

Restore your work:

```bash
git stash pop
```

---

## 📝 Summary

The most common commands are:

```bash
git stash pop
```

Restore and remove the latest stash.

```bash
git stash pop stash@{1}
```

Restore and remove a specific stash.

---

# 🇵🇸 العربية

# 📤 Git Stash Pop

## العربية

يُستخدم الأمر `git stash pop` لاستعادة أحدث التغييرات المحفوظة في Stash ثم حذف ذلك الـ Stash من القائمة.

يكون هذا مفيدًا عندما تحفظ عملك مؤقتًا ثم تصبح مستعدًا لمتابعة العمل عليه.

---

## 🔹 الاستخدام الأساسي

لتطبيق أحدث Stash:

```bash
git stash pop
```

يقوم Git باستعادة التغييرات وحذف الـ Stash من قائمة Stashes.

---

## 🔹 تطبيق Stash محدد

يمكنك تطبيق Stash محدد:

```bash
git stash pop stash@{1}
```

يقوم هذا باستعادة الـ Stash المحدد وحذفه من القائمة إذا نجحت العملية.

---

## 🔹 ماذا يحدث إذا حدث تعارض؟

في بعض الحالات قد تحدث تعارضات أثناء تطبيق Stash.

تحقق من حالة المستودع:

```bash
git status
```

قم بحل التعارضات يدويًا، ثم جهّز الملفات التي تم حلها:

```bash
git add .
```

بعد ذلك يمكنك متابعة العمل أو إنشاء Commit.

---

## 🔹 الفرق بين `git stash pop` و `git stash apply`

الفرق الأساسي هو:

```bash
git stash pop
```

يستعيد الـ Stash ويحذفه من القائمة.

بينما:

```bash
git stash apply
```

يستعيد الـ Stash لكنه يبقيه في القائمة.

---

## 💡 مثال على سير العمل

احفظ تغييراتك:

```bash
git stash
```

انتقل إلى فرع آخر:

```bash
git switch main
```

ارجع لاحقًا:

```bash
git switch feature-login
```

استعد عملك:

```bash
git stash pop
```

---

## 📝 الخلاصة

الأوامر الأكثر استخدامًا:

```bash
git stash pop
```

لاستعادة وحذف أحدث Stash.

```bash
git stash pop stash@{1}
```

لاستعادة وحذف Stash محدد.
