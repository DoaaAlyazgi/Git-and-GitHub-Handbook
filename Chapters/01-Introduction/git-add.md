# ➕ Git Add

## 🌐 English

`git add` is used to move changes from the working directory to the staging area.

Staging allows you to choose which changes will be included in your next commit.

---

## 🔹 Step 1: Add a Specific File

To stage one specific file, use:

```bash
git add filename
```

Example:

```bash
git add index.html
```

Only `index.html` will be staged.

---

## 🔹 Step 2: Add Multiple Files

You can stage multiple files at the same time:

```bash
git add index.html style.css
```

---

## 🔹 Step 3: Add All Changes

To stage all modified and new files in the current directory, use:

```bash
git add .
```

This is commonly used when you want to include all current changes in the next commit.

---

## 🔹 Step 4: Check the Staged Changes

After using `git add`, run:

```bash
git status
```

You should see the staged files under:

```text
Changes to be committed:
```

---

## 🧪 Example Workflow

```bash
git status
git add index.html
git status
git commit -m "Update homepage"
```

The first command checks the current state.

The second command stages `index.html`.

The third command confirms that the file is staged.

The final command creates a commit containing the staged changes.

---

## 💡 Important Note

`git add` does not create a commit.

It only prepares changes for the next commit.

You can stage some files while leaving other changes unstaged.

---

## 📌 Summary

| Command | Purpose |
|---|---|
| `git add filename` | Stage a specific file |
| `git add file1 file2` | Stage multiple files |
| `git add .` | Stage all changes |
| `git status` | Check the staging state |

---

# 🇦🇪 العربية

يُستخدم الأمر `git add` لنقل التغييرات من مجلد العمل إلى منطقة التجهيز (Staging Area).

تسمح لك منطقة التجهيز باختيار التغييرات التي تريد تضمينها في الـ Commit القادم.

---

## 🔹 الخطوة 1: إضافة ملف محدد

لإضافة ملف واحد إلى منطقة التجهيز، استخدم:

```bash
git add filename
```

مثال:

```bash
git add index.html
```

سيتم تجهيز ملف `index.html` فقط.

---

## 🔹 الخطوة 2: إضافة عدة ملفات

يمكنك تجهيز عدة ملفات في نفس الوقت:

```bash
git add index.html style.css
```

---

## 🔹 الخطوة 3: إضافة جميع التغييرات

لإضافة جميع الملفات الجديدة والملفات التي تم تعديلها داخل المجلد الحالي، استخدم:

```bash
git add .
```

يُستخدم هذا الأمر كثيرًا عندما تريد تضمين جميع التغييرات الحالية في الـ Commit القادم.

---

## 🔹 الخطوة 4: التحقق من الملفات المجهزة

بعد استخدام `git add`، قم بتشغيل:

```bash
git status
```

ستجد الملفات التي تمت إضافتها إلى منطقة التجهيز تحت:

```text
Changes to be committed:
```

---

## 🧪 مثال على سير العمل

```bash
git status
git add index.html
git status
git commit -m "Update homepage"
```

الأمر الأول يتحقق من الحالة الحالية للمشروع.

الأمر الثاني يضيف ملف `index.html` إلى منطقة التجهيز.

الأمر الثالث يتأكد من أن الملف أصبح جاهزًا للـ Commit.

الأمر الأخير ينشئ Commit يحتوي على التغييرات التي تمت إضافتها إلى منطقة التجهيز.

---

## 💡 ملاحظة مهمة

الأمر `git add` لا ينشئ Commit.

هو فقط يجهز التغييرات للـ Commit القادم.

يمكنك تجهيز بعض الملفات وترك تغييرات أخرى خارج منطقة التجهيز.

---

## 📌 الملخص

| الأمر | الاستخدام |
|---|---|
| `git add filename` | تجهيز ملف محدد |
| `git add file1 file2` | تجهيز عدة ملفات |
| `git add .` | تجهيز جميع التغييرات |
| `git status` | التحقق من حالة منطقة التجهيز |
