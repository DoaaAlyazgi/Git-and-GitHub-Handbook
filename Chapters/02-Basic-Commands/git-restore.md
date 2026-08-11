# ↩️ Git Restore

## 🌐 English

`git restore` is used to restore files to a previous state or remove changes from the working directory.

It is especially useful when you want to undo changes before they are committed.

---

## 🔹 Step 1: Restore Changes in a File

If you modified a file and want to discard those changes, use:

    git restore filename.txt

Example:

    git restore index.html

This restores the file to the version from the latest commit.

⚠️ Any uncommitted changes in that file will be discarded.

---

## 🔹 Step 2: Restore All Modified Files

To discard changes in all modified files, use:

    git restore .

This restores all files to their latest committed state.

⚠️ Be careful because uncommitted changes will be permanently removed.

---

## 🔹 Step 3: Unstage a File

If you already used `git add` but want to remove a file from the staging area, use:

    git restore --staged filename.txt

Example:

    git restore --staged index.html

This removes the file from the staging area but keeps your changes in the working directory.

---

## 🔹 Step 4: Unstage All Files

To remove all staged changes from the staging area:

    git restore --staged .

Your file changes will remain in the working directory.

---

## 💡 Important Note

`git restore` can be used for two different purposes:

- Restore changes in the working directory.
- Remove files from the staging area.

Always check your changes with:

    git status

before using `git restore`.

---

## 🧪 Example Workflow

    git status
    git add index.html
    git status
    git restore --staged index.html
    git status

This allows you to stage a file and then safely remove it from the staging area without deleting your actual changes.

---

# 🇵🇸 العربية

## ما هو `git restore`؟

يُستخدم الأمر `git restore` لاستعادة الملفات إلى حالة سابقة أو إزالة التغييرات من مجلد العمل.

ويُعد مفيدًا بشكل خاص عندما تريد التراجع عن تغييرات لم يتم حفظها في Commit بعد.

---

## 🔹 الخطوة 1: استعادة التغييرات في ملف

إذا قمت بتعديل ملف وتريد التخلص من هذه التغييرات، استخدم:

    git restore filename.txt

مثال:

    git restore index.html

سيعيد هذا الأمر الملف إلى النسخة الموجودة في آخر Commit.

⚠️ سيتم حذف أي تغييرات غير محفوظة في Commit داخل هذا الملف.

---

## 🔹 الخطوة 2: استعادة جميع الملفات المعدلة

للتخلص من التغييرات الموجودة في جميع الملفات المعدلة، استخدم:

    git restore .

سيعيد هذا الأمر جميع الملفات إلى آخر حالة محفوظة في Commit.

⚠️ انتبه، لأن التغييرات غير المحفوظة سيتم حذفها نهائيًا.

---

## 🔹 الخطوة 3: إزالة ملف من منطقة التجهيز

إذا استخدمت `git add` وأردت إزالة ملف من منطقة التجهيز، استخدم:

    git restore --staged filename.txt

مثال:

    git restore --staged index.html

سيؤدي هذا إلى إزالة الملف من منطقة التجهيز، ولكنه سيُبقي التغييرات الموجودة على الملف داخل مجلد العمل.

---

## 🔹 الخطوة 4: إزالة جميع الملفات من منطقة التجهيز

لإزالة جميع الملفات من منطقة التجهيز:

    git restore --staged .

ستبقى التغييرات الموجودة على الملفات داخل مجلد العمل.

---

## 💡 ملاحظة مهمة

يمكن استخدام `git restore` لغرضين أساسيين:

- استعادة التغييرات الموجودة في مجلد العمل.
- إزالة الملفات من منطقة التجهيز.

من الأفضل دائمًا التحقق من حالة المشروع باستخدام:

    git status

قبل استخدام `git restore`.

---

## 🧪 مثال على سير العمل

    git status
    git add index.html
    git status
    git restore --staged index.html
    git status

يسمح لك هذا المثال بإضافة ملف إلى منطقة التجهيز ثم إزالته منها بدون حذف التغييرات الفعلية الموجودة في الملف.
