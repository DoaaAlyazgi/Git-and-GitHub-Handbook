# ⚔️ Git Merge Conflict

## 🌐 English

A merge conflict occurs when Git cannot automatically combine changes from different branches.

This commonly happens when different branches modify the same part of a file.

---

## 🔹 Start a Merge

For example:

```bash
git switch main
git merge feature-branch
```

If Git cannot automatically merge the changes, it reports a conflict.

---

## 🔹 Check the Conflict

Run:

```bash
git status
```

Git will show the files that contain conflicts.

---

## 🔹 Conflict Markers

Open the conflicted file.

You may see:

```text
<<<<<<< HEAD
Changes from the current branch
=======
Changes from the other branch
>>>>>>> feature-branch
```

These markers show the conflicting changes.

---

## 🔹 Resolve the Conflict

Choose the correct changes or combine them.

Remove the conflict markers:

```text
<<<<<<<
=======
>>>>>>>
```

Save the file after resolving the conflict.

---

## 🔹 Stage the Resolved File

```bash
git add filename.txt
```

Or:

```bash
git add .
```

---

## 🔹 Complete the Merge

After resolving the conflicts:

```bash
git commit
```

Git will create the merge commit.

---

## 🔹 Abort the Merge

If you do not want to continue:

```bash
git merge --abort
```

This cancels the current merge operation.

---

## 💡 Important Tip

Always review the resolved files before completing the merge.

Make sure that the final version contains the correct changes.

---

## 📝 Summary

Typical workflow:

```bash
git merge feature-branch
git status
```

Resolve the conflicts:

```bash
git add .
git commit
```

Or cancel the merge:

```bash
git merge --abort
```

---

# 🇵🇸 العربية

# ⚔️ Git Merge Conflict

## العربية

يحدث Merge Conflict عندما لا يستطيع Git دمج التغييرات الموجودة في فروع مختلفة تلقائيًا.

يحدث ذلك غالبًا عندما تقوم فروع مختلفة بتعديل الجزء نفسه من أحد الملفات.

---

## 🔹 بدء عملية Merge

على سبيل المثال:

```bash
git switch main
git merge feature-branch
```

إذا لم يتمكن Git من دمج التغييرات تلقائيًا، فسيظهر تعارض.

---

## 🔹 التحقق من التعارض

نفذ:

```bash
git status
```

سيعرض Git الملفات التي تحتوي على تعارضات.

---

## 🔹 علامات التعارض

افتح الملف الذي يحتوي على التعارض.

قد ترى:

```text
<<<<<<< HEAD
Changes from the current branch
=======
Changes from the other branch
>>>>>>> feature-branch
```

توضح هذه العلامات التغييرات المتعارضة.

---

## 🔹 حل التعارض

اختر التغييرات الصحيحة أو ادمج بينها.

احذف علامات التعارض:

```text
<<<<<<<
=======
>>>>>>>
```

ثم احفظ الملف بعد حل التعارض.

---

## 🔹 إضافة الملف الذي تم حله

```bash
git add filename.txt
```

أو:

```bash
git add .
```

---

## 🔹 إكمال عملية Merge

بعد حل جميع التعارضات:

```bash
git commit
```

سيقوم Git بإنشاء Merge Commit.

---

## 🔹 إلغاء عملية Merge

إذا كنت لا تريد المتابعة:

```bash
git merge --abort
```

يقوم هذا بإلغاء عملية Merge الحالية.

---

## 💡 نصيحة مهمة

راجع الملفات التي قمت بحل تعارضاتها قبل إكمال عملية Merge.

تأكد من أن النسخة النهائية تحتوي على التغييرات الصحيحة.

---

## 📝 الخلاصة

سير العمل المعتاد:

```bash
git merge feature-branch
git status
```

حل التعارضات ثم:

```bash
git add .
git commit
```

أو ألغِ عملية الدمج:

```bash
git merge --abort
```
