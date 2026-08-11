# ⚔️ Git Rebase Conflicts

## 🌐 English

A rebase conflict occurs when Git cannot automatically apply a commit on top of the new base.

This usually happens when the same parts of a file have been changed differently.

---

## 🔹 Start a Rebase

```bash
git rebase main
```

If Git encounters a conflict, the rebase pauses.

---

## 🔹 Check the Conflict

Run:

```bash
git status
```

Git will show the files that contain conflicts.

---

## 🔹 Resolve the Conflict

Open the conflicted file.

You may see:

```text
<<<<<<< HEAD
Changes from main
=======
Changes from your branch
>>>>>>> commit
```

Choose the correct changes or combine them.

Remove the conflict markers after resolving the file.

---

## 🔹 Stage the Resolved File

```bash
git add filename.txt
```

Or stage all resolved files:

```bash
git add .
```

---

## 🔹 Continue the Rebase

```bash
git rebase --continue
```

Git continues applying the remaining commits.

---

## 🔹 Repeat if Necessary

If another conflict occurs:

```bash
git status
```

Resolve it, then:

```bash
git add .
git rebase --continue
```

Repeat until the rebase is complete.

---

## 🔹 Abort the Rebase

If you do not want to continue:

```bash
git rebase --abort
```

---

## ⚠️ Important Note

Always review the files after resolving conflicts.

Make sure the final code contains the correct changes from both sides when necessary.

---

## 📝 Summary

The common workflow is:

```bash
git rebase main
git status
git add .
git rebase --continue
```

To cancel:

```bash
git rebase --abort
```

---

# 🇵🇸 العربية

# ⚔️ Git Rebase Conflicts

## العربية

يحدث تعارض Rebase عندما لا يستطيع Git تطبيق Commit تلقائيًا فوق القاعدة الجديدة.

يحدث ذلك عادةً عندما يتم تعديل الأجزاء نفسها من ملف بطريقة مختلفة.

---

## 🔹 بدء Rebase

```bash
git rebase main
```

إذا واجه Git تعارضًا، تتوقف عملية Rebase مؤقتًا.

---

## 🔹 التحقق من التعارض

نفذ:

```bash
git status
```

سيعرض Git الملفات التي تحتوي على تعارضات.

---

## 🔹 حل التعارض

افتح الملف الذي يحتوي على التعارض.

قد ترى:

```text
<<<<<<< HEAD
Changes from main
=======
Changes from your branch
>>>>>>> commit
```

اختر التغييرات الصحيحة أو ادمج بينها.

بعد حل الملف، احذف علامات التعارض.

---

## 🔹 إضافة الملف الذي تم حله إلى Staging

```bash
git add filename.txt
```

أو إضافة جميع الملفات التي تم حلها:

```bash
git add .
```

---

## 🔹 متابعة Rebase

```bash
git rebase --continue
```

سيقوم Git بمتابعة تطبيق الـ Commits المتبقية.

---

## 🔹 تكرار العملية عند الحاجة

إذا حدث تعارض آخر:

```bash
git status
```

قم بحله، ثم:

```bash
git add .
git rebase --continue
```

كرر العملية حتى تكتمل عملية Rebase.

---

## 🔹 إلغاء Rebase

إذا كنت لا تريد المتابعة:

```bash
git rebase --abort
```

---

## ⚠️ ملاحظة مهمة

راجع الملفات دائمًا بعد حل التعارضات.

تأكد من أن الكود النهائي يحتوي على التغييرات الصحيحة من كلا الجانبين عند الحاجة.

---

## 📝 الخلاصة

سير العمل المعتاد:

```bash
git rebase main
git status
git add .
git rebase --continue
```

ولإلغاء العملية:

```bash
git rebase --abort
```
