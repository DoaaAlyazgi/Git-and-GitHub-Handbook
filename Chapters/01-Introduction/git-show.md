# 👀 Git Show

## 🌐 English

`git show` is used to display information about a specific commit.

It shows the commit details, including the commit message, author, date, and changes introduced by that commit.

---

## 🔹 Step 1: Show the Latest Commit

To view information about the latest commit, use:

```bash
git show
```

This displays the details and changes of the most recent commit.

---

## 🔹 Step 2: Show a Specific Commit

To view a specific commit, provide its commit ID:

```bash
git show <commit-id>
```

Example:

```bash
git show a1b2c3d
```

You can find the commit ID using:

```bash
git log --oneline
```

---

## 🔹 Step 3: Show Only Commit Information

To display the commit information without showing the full changes, use:

```bash
git show --no-patch
```

This shows details such as the commit ID, author, date, and commit message.

---

## 🔹 Step 4: Show a Summary of Changes

To see a summary of the files changed in a commit, use:

```bash
git show --stat
```

This shows which files were changed and how many lines were added or removed.

---

## 🧪 Example Workflow

```bash
git log --oneline
git show a1b2c3d
```

First, `git log --oneline` helps you find the commit ID.

Then, `git show` displays the details and changes of that commit.

---

## 💡 Important Note

`git show` does not modify your files or create a new commit.

It is mainly used to inspect and understand what happened in a particular commit.

---

## 📌 Summary

| Command | Purpose |
|---|---|
| `git show` | Show the latest commit |
| `git show <commit-id>` | Show a specific commit |
| `git show --no-patch` | Show commit information without changes |
| `git show --stat` | Show a summary of changed files |

---

# 🇵🇸 العربية

## ما هو `git show`؟

يُستخدم الأمر `git show` لعرض معلومات حول Commit محدد.

يعرض تفاصيل الـ Commit، بما في ذلك رسالة الـ Commit، واسم صاحبه، والتاريخ، والتغييرات التي تم إدخالها في ذلك الـ Commit.

---

## 🔹 الخطوة 1: عرض آخر Commit

لعرض معلومات آخر Commit، استخدم:

```bash
git show
```

يعرض هذا الأمر تفاصيل وتغييرات أحدث Commit في المستودع.

---

## 🔹 الخطوة 2: عرض Commit محدد

لعرض Commit محدد، أضف معرّف الـ Commit:

```bash
git show <commit-id>
```

مثال:

```bash
git show a1b2c3d
```

يمكنك العثور على معرّف الـ Commit باستخدام:

```bash
git log --oneline
```

---

## 🔹 الخطوة 3: عرض معلومات الـ Commit فقط

لعرض معلومات الـ Commit دون عرض التغييرات الكاملة، استخدم:

```bash
git show --no-patch
```

يعرض هذا الأمر معلومات مثل معرّف الـ Commit، واسم صاحبه، والتاريخ، ورسالة الـ Commit.

---

## 🔹 الخطوة 4: عرض ملخص التغييرات

لعرض ملخص بالملفات التي تم تغييرها في Commit، استخدم:

```bash
git show --stat
```

يعرض هذا الأمر الملفات التي تم تغييرها وعدد الأسطر التي تمت إضافتها أو حذفها.

---

## 🧪 مثال على سير العمل

```bash
git log --oneline
git show a1b2c3d
```

أولًا، يساعدك الأمر `git log --oneline` في العثور على معرّف الـ Commit.

بعد ذلك، يعرض `git show` تفاصيل وتغييرات ذلك الـ Commit.

---

## 💡 ملاحظة مهمة

الأمر `git show` لا يغيّر ملفات المشروع ولا ينشئ Commit جديدًا.

يُستخدم بشكل أساسي لفحص وفهم ما حدث داخل Commit معين.

---

## 📌 الملخص

| الأمر | الاستخدام |
|---|---|
| `git show` | عرض آخر Commit |
| `git show <commit-id>` | عرض Commit محدد |
| `git show --no-patch` | عرض معلومات الـ Commit دون التغييرات |
| `git show --stat` | عرض ملخص الملفات التي تم تغييرها |
