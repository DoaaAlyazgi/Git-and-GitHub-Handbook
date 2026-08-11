# 💾 Git Commit

## 🌐 English

`git commit` is used to save staged changes as a new snapshot in the Git repository.

A commit represents a specific point in the project's history.

---

## 🔹 Basic Usage

Before creating a commit, you need to stage your changes:

```bash
git add .
```

Then create a commit:

```bash
git commit -m "Your commit message"
```

The message should briefly describe the changes you made.

---

## 🔹 Commit a Specific Change

You can stage a specific file:

```bash
git add filename.txt
```

Then commit it:

```bash
git commit -m "Update filename"
```

---

## 🔹 Write a Good Commit Message

A good commit message should be:

- Short
- Clear
- Descriptive
- Related to the changes

Example:

```bash
git commit -m "Add login page"
```

Another example:

```bash
git commit -m "Fix navigation menu"
```

---

## 🔹 View Your Commits

After creating a commit, you can view your commit history using:

```bash
git log
```

For a shorter version:

```bash
git log --oneline
```

---

## 🔄 Basic Workflow

A common Git workflow is:

```bash
git status
git add .
git commit -m "Describe your changes"
```

### Step 1: Check the status

```bash
git status
```

### Step 2: Stage your changes

```bash
git add .
```

### Step 3: Create a commit

```bash
git commit -m "Describe your changes"
```

---

## 💡 Example

Suppose you created a new file called `index.html`.

First, check the repository status:

```bash
git status
```

Then add the file:

```bash
git add index.html
```

Finally, create a commit:

```bash
git commit -m "Add homepage"
```

Now the changes are saved as a new snapshot in Git.

---

## 📝 Summary

`git commit` saves staged changes into the Git repository.

The basic process is:

```bash
git add .
git commit -m "Your commit message"
```

Remember that `git add` stages the changes, while `git commit` saves those staged changes as a new point in the project's history.

---

# 🇵🇸 العربية

`git commit` يُستخدم لحفظ التغييرات التي تم تجهيزها (Staged Changes) كنسخة جديدة داخل مستودع Git.

يمثل الـ Commit نقطة محددة في تاريخ المشروع.

---

## 🔹 الاستخدام الأساسي

قبل إنشاء Commit، يجب أولًا تجهيز التغييرات:

```bash
git add .
```

بعد ذلك يمكنك إنشاء Commit:

```bash
git commit -m "Your commit message"
```

يجب أن تصف رسالة الـ Commit التغييرات التي قمت بها بشكل مختصر وواضح.

---

## 🔹 عمل Commit لتغيير محدد

يمكنك تجهيز ملف محدد:

```bash
git add filename.txt
```

ثم إنشاء Commit:

```bash
git commit -m "Update filename"
```

---

## 🔹 كتابة رسالة Commit جيدة

يُفضل أن تكون رسالة الـ Commit:

- قصيرة
- واضحة
- وصفية
- مرتبطة بالتغييرات التي قمت بها

مثال:

```bash
git commit -m "Add login page"
```

مثال آخر:

```bash
git commit -m "Fix navigation menu"
```

---

## 🔹 عرض الـ Commits

بعد إنشاء Commit، يمكنك عرض سجل الـ Commits باستخدام:

```bash
git log
```

ولعرض نسخة مختصرة من السجل:

```bash
git log --oneline
```

---

## 🔄 سير العمل الأساسي

من الطرق الشائعة للعمل باستخدام Git:

```bash
git status
git add .
git commit -m "Describe your changes"
```

### الخطوة 1: فحص حالة المستودع

```bash
git status
```

### الخطوة 2: تجهيز التغييرات

```bash
git add .
```

### الخطوة 3: إنشاء Commit

```bash
git commit -m "Describe your changes"
```

---

## 💡 مثال

لنفترض أنك أنشأت ملفًا جديدًا باسم `index.html`.

أولًا، افحص حالة المستودع:

```bash
git status
```

ثم أضف الملف إلى منطقة التجهيز:

```bash
git add index.html
```

وأخيرًا، أنشئ Commit:

```bash
git commit -m "Add homepage"
```

الآن أصبحت التغييرات محفوظة كنقطة جديدة في تاريخ المشروع داخل Git.

---

## 📝 الخلاصة

يُستخدم `git commit` لحفظ التغييرات التي تم تجهيزها داخل مستودع Git.

العملية الأساسية هي:

```bash
git add .
git commit -m "Your commit message"
```

تذكّر أن `git add` يقوم بتجهيز التغييرات، بينما `git commit` يقوم بحفظ هذه التغييرات المجهزة كنقطة جديدة في تاريخ المشروع.
