# 📦 Git Mv

## 🌐 English

`git mv` is used to move or rename files and directories while keeping Git aware of the change.

It is a convenient alternative to manually moving or renaming a file and then using `git add` and `git rm`.

---

## 🔹 Step 1: Rename a File

To rename a file, use:

    git mv old-name.txt new-name.txt

Example:

    git mv index.html home.html

Git recognizes this as a rename and stages the change automatically.

---

## 🔹 Step 2: Move a File

To move a file into another directory, use:

    git mv file.txt docs/file.txt

Example:

    git mv README.md docs/README.md

The file is moved and the change is staged automatically.

---

## 🔹 Step 3: Rename a Directory

You can also rename a directory:

    git mv old-folder new-folder

Example:

    git mv images assets

Git will track the directory changes and stage them.

---

## 🔹 Step 4: Check the Changes

After using `git mv`, check the repository status:

    git status

You should see the rename or move listed as a staged change.

---

## 🧪 Example Workflow

    git mv old-name.txt new-name.txt
    git status
    git commit -m "Rename file"

---

## 💡 Important Note

`git mv` does not create a commit.

It only moves or renames the file and stages the change.

You still need to create a commit to permanently record the change in Git history.

---

## 📌 Summary

| Command | Purpose |
|---|---|
| `git mv old new` | Rename a file |
| `git mv file folder/file` | Move a file |
| `git status` | Check the staged change |
| `git commit` | Save the change in Git history |

---

# 🇵🇸 العربية

## ما هو `git mv`؟

يُستخدم الأمر `git mv` لنقل الملفات والمجلدات أو إعادة تسميتها مع إبقاء Git على علم بهذا التغيير.

وهو طريقة سهلة بدلًا من نقل الملف أو إعادة تسميته يدويًا ثم استخدام `git add` و`git rm` بشكل منفصل.

---

## 🔹 الخطوة 1: إعادة تسمية ملف

لإعادة تسمية ملف، استخدم:

    git mv old-name.txt new-name.txt

مثال:

    git mv index.html home.html

سيتعرف Git على العملية كتغيير في اسم الملف، وسيقوم بتجهيز التغيير تلقائيًا.

---

## 🔹 الخطوة 2: نقل ملف

لنقل ملف إلى مجلد آخر، استخدم:

    git mv file.txt docs/file.txt

مثال:

    git mv README.md docs/README.md

سيتم نقل الملف وتجهيز التغيير تلقائيًا.

---

## 🔹 الخطوة 3: إعادة تسمية مجلد

يمكنك أيضًا إعادة تسمية مجلد باستخدام:

    git mv old-folder new-folder

مثال:

    git mv images assets

سيقوم Git بتتبع التغيير وتجهيزه.

---

## 🔹 الخطوة 4: التحقق من التغييرات

بعد استخدام `git mv`، تحقق من حالة المستودع:

    git status

ستجد عملية إعادة التسمية أو النقل ظاهرة كتغيير مجهز للـ Commit.

---

## 🧪 مثال على سير العمل

    git mv old-name.txt new-name.txt
    git status
    git commit -m "Rename file"

---

## 💡 ملاحظة مهمة

الأمر `git mv` لا ينشئ Commit.

هو فقط يقوم بنقل الملف أو إعادة تسميته وتجهيز التغيير.

يجب عليك إنشاء Commit بشكل منفصل لحفظ التغيير نهائيًا في سجل Git.

---

## 📌 الملخص

| الأمر | الاستخدام |
|---|---|
| `git mv old new` | إعادة تسمية ملف |
| `git mv file folder/file` | نقل ملف |
| `git status` | التحقق من التغيير المجهز |
| `git commit` | حفظ التغيير في سجل Git |
