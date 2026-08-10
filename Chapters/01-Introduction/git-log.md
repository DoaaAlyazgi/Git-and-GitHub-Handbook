# 📜 Git Log

## 🌐 English

`git log` is used to view the history of commits in a Git repository.

It helps you see what changes were made, when they were made, and who made them.

---

## 🔹 Step 1: View the Commit History

Run:

    git log

Git will display information about each commit, including:

- Commit ID
- Author
- Date
- Commit message

---

## 🔹 Step 2: View a Shorter History

To display commits in a compact format, use:

    git log --oneline

Example:

    a1b2c3d Add login page
    e4f5g6h Fix navigation bug
    i7j8k9l Update README

This format makes the commit history easier to read.

---

## 🔹 Step 3: Limit the Number of Commits

To show only the latest few commits:

    git log -3

This displays the last three commits.

You can replace `3` with any number.

---

## 🔹 Step 4: View a Specific Commit

To see detailed information about a specific commit:

    git show COMMIT_ID

Example:

    git show a1b2c3d

This shows the changes and information related to that commit.

---

## 💡 Useful Commands

    git log
    git log --oneline
    git log -3
    git show COMMIT_ID

---

## 📌 Why Use `git log`?

`git log` is useful when you want to:

- Review the project's history
- Find a previous change
- Identify who made a change
- Check when a change was made
- Find a specific commit

---

# 🇵🇸 العربية

## ما هو `git log`؟

يُستخدم الأمر `git log` لعرض سجل الـ Commits الموجودة في مستودع Git.

يساعدك على معرفة التغييرات التي تم إجراؤها، ومتى تمت، ومن قام بها.

---

## 🔹 الخطوة 1: عرض سجل الـ Commits

استخدم الأمر:

    git log

سيعرض Git معلومات عن كل Commit، مثل:

- معرّف الـ Commit
- اسم صاحب الـ Commit
- تاريخ الـ Commit
- رسالة الـ Commit

---

## 🔹 الخطوة 2: عرض سجل مختصر

لعرض الـ Commits بطريقة مختصرة وأسهل للقراءة، استخدم:

    git log --oneline

مثال:

    a1b2c3d Add login page
    e4f5g6h Fix navigation bug
    i7j8k9l Update README

هذا الشكل يجعل قراءة سجل المشروع أسهل.

---

## 🔹 الخطوة 3: تحديد عدد الـ Commits

لعرض آخر عدد محدد من الـ Commits، استخدم:

    git log -3

يعرض هذا الأمر آخر ثلاثة Commits.

يمكنك استبدال الرقم `3` بأي رقم تريده.

---

## 🔹 الخطوة 4: عرض Commit محدد

لعرض تفاصيل Commit معين، استخدم:

    git show COMMIT_ID

مثال:

    git show a1b2c3d

يعرض هذا الأمر معلومات الـ Commit والتغييرات المرتبطة به.

---

## 💡 أوامر مفيدة

    git log
    git log --oneline
    git log -3
    git show COMMIT_ID

---

## 📌 لماذا نستخدم `git log`؟

يُستخدم `git log` عندما تريد:

- مراجعة تاريخ المشروع
- البحث عن تغيير سابق
- معرفة من قام بتغيير معين
- معرفة وقت إجراء التغيير
- العثور على Commit محدد
