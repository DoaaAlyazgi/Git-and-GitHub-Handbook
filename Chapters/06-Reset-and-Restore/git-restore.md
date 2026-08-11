# 🔄 Git Restore

## 🌐 English

`git restore` is used to restore files to a previous state or discard unwanted changes in the working directory.

It can also be used to remove files from the staging area without deleting their changes.

---

## 🔹 Discard Changes in a File

To discard changes made to a file:

```bash
git restore filename.txt
```

This restores the file to the version from the latest commit.

---

## 🔹 Restore Multiple Files

You can restore multiple files:

```bash
git restore file1.txt file2.txt
```

---

## 🔹 Unstage a File

To remove a file from the staging area:

```bash
git restore --staged filename.txt
```

The changes are not deleted. They are simply removed from the staging area.

---

## 🔹 Restore a File from a Specific Commit

You can restore a file from a specific commit:

```bash
git restore --source=HEAD~1 filename.txt
```

---

## ⚠️ Important Note

Be careful when using `git restore` without `--staged`.

Changes in the working directory may be permanently discarded.

---

## 📝 Summary

```bash
git restore filename.txt
git restore --staged filename.txt
git restore --source=HEAD~1 filename.txt
```

`git restore` is mainly used to restore files and manage changes in the working directory and staging area.

---

# 🇵🇸 العربية

# 🔄 Git Restore

## العربية

يُستخدم `git restore` لاستعادة الملفات إلى حالة سابقة أو للتراجع عن التغييرات غير المرغوبة في مجلد العمل.

ويمكن استخدامه أيضًا لإزالة الملفات من منطقة Staging دون حذف التغييرات الموجودة فيها.

---

## 🔹 التراجع عن تغييرات ملف

للتراجع عن التغييرات التي تم إجراؤها على ملف:

```bash
git restore filename.txt
```

يعيد هذا الأمر الملف إلى النسخة الموجودة في آخر Commit.

---

## 🔹 استعادة عدة ملفات

يمكنك استعادة عدة ملفات:

```bash
git restore file1.txt file2.txt
```

---

## 🔹 إزالة ملف من Staging

لإزالة ملف من منطقة Staging:

```bash
git restore --staged filename.txt
```

لا يتم حذف التغييرات، وإنما تتم إزالتها فقط من منطقة Staging.

---

## 🔹 استعادة ملف من Commit محدد

يمكنك استعادة ملف من Commit محدد:

```bash
git restore --source=HEAD~1 filename.txt
```

---

## ⚠️ ملاحظة مهمة

كن حذرًا عند استخدام `git restore` بدون `--staged`.

قد يتم حذف التغييرات الموجودة في مجلد العمل بشكل نهائي.

---

## 📝 الخلاصة

```bash
git restore filename.txt
git restore --staged filename.txt
git restore --source=HEAD~1 filename.txt
```

يُستخدم `git restore` بشكل أساسي لاستعادة الملفات وإدارة التغييرات في مجلد العمل ومنطقة Staging.
