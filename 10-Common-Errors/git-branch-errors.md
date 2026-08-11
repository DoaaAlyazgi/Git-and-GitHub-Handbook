# 🌿 Git Branch Errors

## 🌐 English

Git branch errors can happen when you try to create, switch, rename, or delete branches incorrectly.

Understanding the error message usually helps identify the problem.

---

## 🔹 Branch Already Exists

If you try to create a branch that already exists:

```bash
git branch feature
```

Git may report that the branch already exists.

Check your branches:

```bash
git branch
```

---

## 🔹 Switch to an Existing Branch

If the branch already exists, switch to it:

```bash
git switch feature
```

---

## 🔹 Uncommitted Changes

Git may prevent you from switching branches when your local changes would be overwritten.

Check your status:

```bash
git status
```

You can commit your changes:

```bash
git add .
git commit -m "Save changes"
```

Or temporarily store them:

```bash
git stash
```

Then switch branches:

```bash
git switch another-branch
```

---

## 🔹 Delete a Branch

To delete a local branch:

```bash
git branch -d feature
```

If the branch has unmerged changes and you are sure you want to delete it:

```bash
git branch -D feature
```

Use `-D` carefully because it can delete commits that have not been merged.

---

## 🔹 Rename a Branch

To rename the current branch:

```bash
git branch -m new-name
```

---

## 🔹 List Branches

To see local branches:

```bash
git branch
```

To see local and remote branches:

```bash
git branch -a
```

---

## 📝 Summary

Useful commands:

```bash
git branch
git switch branch-name
git branch -m new-name
git branch -d branch-name
git stash
```

---

# 🇵🇸 العربية

# 🌿 Git Branch Errors

## العربية

قد تحدث أخطاء الفروع عندما تحاول إنشاء أو الانتقال أو إعادة تسمية أو حذف Branch بطريقة غير صحيحة.

عادةً تساعدك رسالة الخطأ على معرفة المشكلة.

---

## 🔹 الفرع موجود مسبقًا

إذا حاولت إنشاء فرع موجود بالفعل:

```bash
git branch feature
```

قد يعرض Git رسالة تفيد بأن الفرع موجود مسبقًا.

تحقق من الفروع:

```bash
git branch
```

---

## 🔹 الانتقال إلى فرع موجود

إذا كان الفرع موجودًا بالفعل، انتقل إليه:

```bash
git switch feature
```

---

## 🔹 وجود تغييرات غير محفوظة

قد يمنعك Git من الانتقال إلى فرع آخر إذا كانت تغييراتك المحلية ستتعرض للكتابة فوقها.

تحقق من الحالة:

```bash
git status
```

يمكنك إنشاء Commit للتغييرات:

```bash
git add .
git commit -m "Save changes"
```

أو تخزينها مؤقتًا:

```bash
git stash
```

ثم الانتقال إلى الفرع الآخر:

```bash
git switch another-branch
```

---

## 🔹 حذف فرع

لحذف فرع محلي:

```bash
git branch -d feature
```

إذا كان الفرع يحتوي على تغييرات لم يتم دمجها وكنت متأكدًا من رغبتك في حذفه:

```bash
git branch -D feature
```

استخدم `-D` بحذر لأنه قد يحذف Commits لم يتم دمجها.

---

## 🔹 إعادة تسمية فرع

لإعادة تسمية الفرع الحالي:

```bash
git branch -m new-name
```

---

## 🔹 عرض الفروع

لعرض الفروع المحلية:

```bash
git branch
```

لعرض الفروع المحلية والبعيدة:

```bash
git branch -a
```

---

## 📝 الخلاصة

أوامر مفيدة:

```bash
git branch
git switch branch-name
git branch -m new-name
git branch -d branch-name
git stash
```
