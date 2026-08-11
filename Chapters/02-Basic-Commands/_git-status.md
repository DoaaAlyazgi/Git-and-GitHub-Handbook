# 📊 Git Status

## 🌐 English

`git status` is used to check the current state of a Git repository.

It shows which files have been modified, which files are untracked, and which changes are ready to be committed.

---

## 🔹 Step 1: Run Git Status

Open your terminal inside the project folder and run:

```bash
git status
```

Git will display information about the current state of your repository.

---

## 🔹 Step 2: Understand the Output

You may see information such as:

```text
On branch main

Untracked files:
  index.html
  style.css
```

This means Git has detected files that are not being tracked yet.

---

## 🔹 Step 3: After Modifying a File

If you modify a tracked file and run:

```bash
git status
```

Git may show:

```text
Changes not staged for commit:
  modified: index.html
```

This means the file has been changed but the changes are not staged yet.

---

## 💡 Important Note

`git status` does not change your files.

It only gives you information about the current state of your repository.

It is one of the most useful Git commands and is commonly used before and after making changes.

---

## 🧪 Quick Example

```bash
git status
git add .
git status
```

The first command shows the current state.

The second command stages the changes.

The third command shows which changes are now ready to be committed.

---

## 📌 Summary

| Command | Purpose |
|---|---|
| `git status` | Check the current repository status |
| `git add .` | Stage changes for the next commit |

---

# 🇵🇸 العربية

يُستخدم الأمر `git status` للتحقق من الحالة الحالية لمستودع Git.

يعرض هذا الأمر الملفات التي تم تعديلها، والملفات التي لم تتم متابعتها بعد، والتغييرات التي أصبحت جاهزة لإنشاء Commit.

---

## 🔹 الخطوة 1: تشغيل Git Status

افتح Terminal داخل مجلد المشروع وقم بتشغيل:

```bash
git status
```

سيعرض Git معلومات حول الحالة الحالية للمستودع.

---

## 🔹 الخطوة 2: فهم النتيجة

قد تظهر لك معلومات مثل:

```text
On branch main

Untracked files:
  index.html
  style.css
```

هذا يعني أن Git اكتشف ملفات لم تتم متابعتها بعد.

---

## 🔹 الخطوة 3: بعد تعديل أحد الملفات

إذا قمت بتعديل ملف تتم متابعته ثم شغّلت:

```bash
git status
```

قد يظهر لك:

```text
Changes not staged for commit:
  modified: index.html
```

هذا يعني أن الملف تم تعديله، ولكن التغييرات لم تتم إضافتها إلى منطقة التجهيز (Staging Area) بعد.

---

## 💡 ملاحظة مهمة

الأمر `git status` لا يقوم بتغيير ملفات المشروع.

هو فقط يعرض معلومات عن الحالة الحالية لمستودع Git.

ويُعد من أهم أوامر Git، ويُستخدم عادةً قبل وبعد إجراء التعديلات على المشروع.

---

## 🧪 مثال سريع

```bash
git status
git add .
git status
```

الأمر الأول يعرض الحالة الحالية للمستودع.

الأمر الثاني يضيف التغييرات إلى منطقة التجهيز.

الأمر الثالث يعرض التغييرات التي أصبحت جاهزة لإنشاء Commit.

---

## 📌 الملخص

| الأمر | الاستخدام |
|---|---|
| `git status` | التحقق من حالة المستودع الحالية |
| `git add .` | تجهيز التغييرات للـ Commit التالي |
