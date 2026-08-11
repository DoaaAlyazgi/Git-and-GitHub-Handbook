# 🧹 Git Clean

## 🌐 English

`git clean` is used to remove untracked files and directories from the working directory.

It is useful for cleaning files that are not tracked by Git and are not needed in the project.

---

## 🔹 Step 1: Check What Will Be Removed

Before deleting anything, use:

    git clean -n

This performs a dry run and shows which untracked files would be removed.

It does not delete anything.

---

## 🔹 Step 2: Remove Untracked Files

To remove untracked files, use:

    git clean -f

The `-f` option means "force".

Git requires this option because the command can permanently delete files.

---

## 🔹 Step 3: Remove Untracked Directories

To remove untracked directories as well, use:

    git clean -fd

The `-d` option tells Git to include untracked directories.

---

## 🔹 Step 4: Preview Files and Directories

Before using `git clean -fd`, you can preview what will be removed:

    git clean -nd

This is a safer way to check the files and directories first.

---

## 💡 Important Warning

`git clean` can permanently delete untracked files.

Deleted files may not be recoverable through Git because Git was not tracking them.

Always use:

    git clean -n

or:

    git clean -nd

before using the force option.

---

## 🧪 Example Workflow

    git status
    git clean -n
    git clean -f
    git status

For untracked directories:

    git clean -nd
    git clean -fd

---

## 📌 Summary

| Command | Purpose |
|---|---|
| `git clean -n` | Preview untracked files |
| `git clean -f` | Remove untracked files |
| `git clean -nd` | Preview untracked files and directories |
| `git clean -fd` | Remove untracked files and directories |

---

# 🇵🇸 العربية

## ما هو `git clean`؟

يُستخدم الأمر `git clean` لحذف الملفات والمجلدات التي لا يتتبعها Git من مجلد العمل.

يكون مفيدًا لتنظيف الملفات غير المتتبعة التي لم تعد بحاجة إليها داخل المشروع.

---

## 🔹 الخطوة 1: معرفة ما سيتم حذفه

قبل حذف أي شيء، استخدم:

    git clean -n

يقوم هذا الأمر بعمل معاينة فقط، ويعرض الملفات غير المتتبعة التي سيتم حذفها.

ولا يقوم بحذف أي ملف.

---

## 🔹 الخطوة 2: حذف الملفات غير المتتبعة

لحذف الملفات غير المتتبعة، استخدم:

    git clean -f

يشير الخيار `-f` إلى "Force"، أي تنفيذ عملية الحذف بالقوة.

يتطلب Git هذا الخيار لأن الأمر يمكن أن يؤدي إلى حذف الملفات بشكل نهائي.

---

## 🔹 الخطوة 3: حذف المجلدات غير المتتبعة

لحذف المجلدات غير المتتبعة أيضًا، استخدم:

    git clean -fd

يخبر الخيار `-d` Git بتضمين المجلدات غير المتتبعة في عملية الحذف.

---

## 🔹 الخطوة 4: معاينة الملفات والمجلدات

قبل استخدام `git clean -fd`، يمكنك معرفة ما سيتم حذفه أولًا باستخدام:

    git clean -nd

تُعد هذه طريقة أكثر أمانًا للتأكد من الملفات والمجلدات التي سيتم حذفها.

---

## 💡 تحذير مهم

يمكن للأمر `git clean` حذف الملفات غير المتتبعة بشكل نهائي.

وقد لا تتمكن من استعادة الملفات المحذوفة باستخدام Git، لأن Git لم يكن يتتبعها من الأساس.

لذلك استخدم دائمًا:

    git clean -n

أو:

    git clean -nd

قبل استخدام خيارات الحذف بالقوة.

---

## 🧪 مثال على سير العمل

    git status
    git clean -n
    git clean -f
    git status

ولحذف المجلدات غير المتتبعة أيضًا:

    git clean -nd
    git clean -fd

---

## 📌 الملخص

| الأمر | الاستخدام |
|---|---|
| `git clean -n` | معاينة الملفات غير المتتبعة |
| `git clean -f` | حذف الملفات غير المتتبعة |
| `git clean -nd` | معاينة الملفات والمجلدات غير المتتبعة |
| `git clean -fd` | حذف الملفات والمجلدات غير المتتبعة |
