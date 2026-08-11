# 🗑️ Git Rm

## 🌐 English

`git rm` is used to remove files from the working directory and the Git repository.

It removes the file and stages the deletion automatically.

---

## 🔹 Step 1: Remove a File

To remove a file from your project and stage the deletion, use:

    git rm filename.txt

Example:

    git rm old-file.txt

The file will be deleted from your working directory and staged for the next commit.

---

## 🔹 Step 2: Remove Multiple Files

You can remove multiple files at once:

    git rm file1.txt file2.txt

Git will delete the specified files and stage their removal.

---

## 🔹 Step 3: Remove a File from Git but Keep It Locally

If you want Git to stop tracking a file but keep the file on your computer, use:

    git rm --cached filename.txt

Example:

    git rm --cached config.txt

The file will remain in your project folder, but Git will no longer track it.

---

## 🔹 Step 4: Check the Changes

After removing a file, check the repository status:

    git status

You should see the deleted file listed as a staged change.

---

## 🔹 Step 5: Commit the Removal

After removing the file, create a commit:

    git commit -m "Remove unused file"

This permanently records the deletion in Git history.

---

## 💡 Important Note

`git rm` removes a file and stages the deletion at the same time.

If you only want to stop tracking a file while keeping it locally, use:

    git rm --cached filename.txt

This is commonly used when a file should not be included in the repository.

---

## 🧪 Example Workflow

    git status
    git rm old-file.txt
    git status
    git commit -m "Remove old file"

---

## 📌 Summary

| Command | Purpose |
|---|---|
| `git rm filename` | Delete a file and stage the deletion |
| `git rm file1 file2` | Delete multiple files |
| `git rm --cached filename` | Stop tracking a file but keep it locally |
| `git status` | Check the changes |
| `git commit` | Save the removal in Git history |

---

# 🇵🇸 العربية

## ما هو `git rm`؟

يُستخدم الأمر `git rm` لحذف الملفات من مجلد المشروع ومن مستودع Git.

يقوم الأمر بحذف الملف وتجهيز عملية الحذف تلقائيًا للـ Commit القادم.

---

## 🔹 الخطوة 1: حذف ملف

لحذف ملف من المشروع وتجهيز عملية الحذف، استخدم:

    git rm filename.txt

مثال:

    git rm old-file.txt

سيتم حذف الملف من مجلد المشروع، كما سيتم تجهيز عملية حذفه للـ Commit القادم.

---

## 🔹 الخطوة 2: حذف عدة ملفات

يمكنك حذف عدة ملفات في نفس الوقت:

    git rm file1.txt file2.txt

سيقوم Git بحذف الملفات المحددة وتجهيز عملية حذفها.

---

## 🔹 الخطوة 3: إزالة ملف من Git مع الاحتفاظ به محليًا

إذا كنت تريد إيقاف Git عن تتبع ملف مع الاحتفاظ بالملف على جهازك، استخدم:

    git rm --cached filename.txt

مثال:

    git rm --cached config.txt

سيبقى الملف موجودًا داخل مجلد المشروع، ولكن Git سيتوقف عن تتبعه.

---

## 🔹 الخطوة 4: التحقق من التغييرات

بعد حذف الملف، تحقق من حالة المستودع باستخدام:

    git status

ستجد الملف المحذوف ظاهرًا كتغيير مجهز للـ Commit.

---

## 🔹 الخطوة 5: حفظ عملية الحذف

بعد حذف الملف، أنشئ Commit:

    git commit -m "Remove unused file"

سيؤدي ذلك إلى حفظ عملية الحذف في سجل Git.

---

## 💡 ملاحظة مهمة

الأمر `git rm` يقوم بحذف الملف وتجهيز عملية الحذف في نفس الوقت.

إذا كنت تريد فقط إيقاف Git عن تتبع الملف مع إبقائه على جهازك، استخدم:

    git rm --cached filename.txt

يُستخدم هذا الأمر كثيرًا عندما يكون هناك ملف لا يجب أن يكون موجودًا داخل مستودع Git.

---

## 🧪 مثال على سير العمل

    git status
    git rm old-file.txt
    git status
    git commit -m "Remove old file"

---

## 📌 الملخص

| الأمر | الاستخدام |
|---|---|
| `git rm filename` | حذف ملف وتجهيز عملية الحذف |
| `git rm file1 file2` | حذف عدة ملفات |
| `git rm --cached filename` | إيقاف تتبع ملف مع الاحتفاظ به محليًا |
| `git status` | التحقق من التغييرات |
| `git commit` | حفظ عملية الحذف في سجل Git |
