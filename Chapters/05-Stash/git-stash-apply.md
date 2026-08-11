# 📥 Git Stash Apply

## 🌐 English

`git stash apply` is used to restore stashed changes without removing the stash from the stash list.

This is useful when you want to restore the changes but also keep a backup of the stash.

---

## 🔹 Basic Usage

To apply the latest stash:

```bash
git stash apply
```

The changes are restored to your working directory.

The stash remains available in the stash list.

---

## 🔹 Apply a Specific Stash

To apply a specific stash:

```bash
git stash apply stash@{1}
```

This restores the changes stored in `stash@{1}`.

---

## 🔹 Check the Result

After applying a stash, check the repository status:

```bash
git status
```

You can also review the changes:

```bash
git diff
```

---

## 🔹 Remove the Stash After Applying

If you no longer need the stash after applying it, you can remove it:

```bash
git stash drop stash@{1}
```

Alternatively, if you want to restore and remove the latest stash in one command, use:

```bash
git stash pop
```

---

## 💡 `apply` vs `pop`

```bash
git stash apply
```

Restores the stash and keeps it.

```bash
git stash pop
```

Restores the stash and removes it.

---

## 📝 Summary

Common commands:

```bash
git stash apply
```

Apply the latest stash.

```bash
git stash apply stash@{1}
```

Apply a specific stash.

`git stash apply` is useful when you want to restore your work while keeping the stash as a backup.

---

# 🇵🇸 العربية

# 📥 Git Stash Apply

## العربية

يُستخدم الأمر `git stash apply` لاستعادة التغييرات المحفوظة في Stash دون حذف الـ Stash من القائمة.

يكون هذا مفيدًا عندما تريد استعادة التغييرات مع الاحتفاظ بنسخة من الـ Stash كنسخة احتياطية.

---

## 🔹 الاستخدام الأساسي

لتطبيق أحدث Stash:

```bash
git stash apply
```

يتم استعادة التغييرات إلى مجلد العمل.

ويبقى الـ Stash موجودًا في قائمة Stashes.

---

## 🔹 تطبيق Stash محدد

لتطبيق Stash محدد:

```bash
git stash apply stash@{1}
```

يقوم هذا باستعادة التغييرات الموجودة في `stash@{1}`.

---

## 🔹 التحقق من النتيجة

بعد تطبيق Stash، تحقق من حالة المستودع:

```bash
git status
```

ويمكنك أيضًا مراجعة التغييرات:

```bash
git diff
```

---

## 🔹 حذف Stash بعد تطبيقه

إذا لم تعد بحاجة إلى Stash بعد تطبيقه، يمكنك حذفه:

```bash
git stash drop stash@{1}
```

أما إذا كنت تريد استعادة أحدث Stash وحذفه في أمر واحد، فاستخدم:

```bash
git stash pop
```

---

## 💡 الفرق بين `apply` و `pop`

```bash
git stash apply
```

يستعيد الـ Stash ويبقيه محفوظًا.

```bash
git stash pop
```

يستعيد الـ Stash ويحذفه.

---

## 📝 الخلاصة

الأوامر الشائعة:

```bash
git stash apply
```

لتطبيق أحدث Stash.

```bash
git stash apply stash@{1}
```

لتطبيق Stash محدد.

يُعد `git stash apply` مفيدًا عندما تريد استعادة عملك مع الاحتفاظ بالـ Stash كنسخة احتياطية.
