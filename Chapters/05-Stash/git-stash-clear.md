# 🧹 Git Stash Clear

## 🌐 English

`git stash clear` is used to remove all stashes from the local Git repository.

Unlike `git stash drop`, which removes one stash, `git stash clear` removes every saved stash.

---

## 🔹 Basic Usage

To delete all saved stashes:

```bash
git stash clear
```

After running this command, the stash list will be empty.

---

## 🔹 Check the Stash List

Before clearing your stashes, you can view them:

```bash
git stash list
```

Then, if you are sure you no longer need them:

```bash
git stash clear
```

---

## ⚠️ Important Warning

`git stash clear` deletes all saved stashes.

Make sure you do not need any of the stored changes before using this command.

---

## 💡 Example

View your stashes:

```bash
git stash list
```

Example:

```text
stash@{0}: On main: Work in progress
stash@{1}: On feature-login: Update login page
stash@{2}: On development: Fix navigation
```

Clear all stashes:

```bash
git stash clear
```

Check again:

```bash
git stash list
```

There should now be no saved stashes.

---

## 📝 Summary

The main command is:

```bash
git stash clear
```

It removes all saved stashes from the local repository.

Use this command carefully because all saved stashes will be removed.

---

# 🇵🇸 العربية

# 🧹 Git Stash Clear

## العربية

يُستخدم الأمر `git stash clear` لحذف جميع الـ Stashes الموجودة في مستودع Git المحلي.

على عكس `git stash drop` الذي يحذف Stash واحدًا، يقوم `git stash clear` بحذف جميع الـ Stashes المحفوظة.

---

## 🔹 الاستخدام الأساسي

لحذف جميع الـ Stashes المحفوظة:

```bash
git stash clear
```

بعد تنفيذ هذا الأمر، ستصبح قائمة الـ Stashes فارغة.

---

## 🔹 التحقق من قائمة Stashes

قبل حذف جميع الـ Stashes، يمكنك عرضها:

```bash
git stash list
```

ثم إذا كنت متأكدًا أنك لم تعد بحاجة إليها:

```bash
git stash clear
```

---

## ⚠️ تحذير مهم

يقوم `git stash clear` بحذف جميع الـ Stashes المحفوظة.

تأكد من أنك لا تحتاج إلى أي من التغييرات المخزنة قبل استخدام هذا الأمر.

---

## 💡 مثال

اعرض الـ Stashes:

```bash
git stash list
```

مثال:

```text
stash@{0}: On main: Work in progress
stash@{1}: On feature-login: Update login page
stash@{2}: On development: Fix navigation
```

احذف جميع الـ Stashes:

```bash
git stash clear
```

تحقق مرة أخرى:

```bash
git stash list
```

يجب ألا تظهر أي Stashes محفوظة الآن.

---

## 📝 الخلاصة

الأمر الأساسي هو:

```bash
git stash clear
```

يقوم بحذف جميع الـ Stashes المحفوظة من المستودع المحلي.

استخدم هذا الأمر بحذر لأنه سيؤدي إلى حذف جميع الـ Stashes المحفوظة.
