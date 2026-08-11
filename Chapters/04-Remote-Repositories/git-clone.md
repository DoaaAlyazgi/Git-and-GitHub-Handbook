# 📥 Git Clone

## 🌐 English

`git clone` is used to create a local copy of an existing remote repository.

It is commonly used when you want to download a project from GitHub and start working on it locally.

---

## 🔹 Basic Usage

To clone a repository:

```bash
git clone https://github.com/username/repository.git
```

Git downloads the repository and creates a new directory containing the project files and Git history.

---

## 🔹 Clone into a Specific Directory

You can choose the name of the directory:

```bash
git clone https://github.com/username/repository.git my-project
```

Git will create a directory called `my-project`.

---

## 🔹 Clone a Specific Branch

To clone a specific branch:

```bash
git clone -b feature-login https://github.com/username/repository.git
```

This clones the repository and checks out the specified branch.

---

## 🔹 Clone Using SSH

If SSH authentication is configured, you can clone using an SSH URL:

```bash
git clone git@github.com:username/repository.git
```

---

## 🔹 What Happens After Cloning?

After cloning a repository, Git automatically:

- Downloads the project files
- Downloads the Git history
- Creates a local repository
- Adds the remote repository
- Usually names the remote `origin`
- Checks out the default branch

You can check the remote connection with:

```bash
git remote -v
```

---

## 💡 Example Workflow

Clone a project:

```bash
git clone https://github.com/username/repository.git
```

Enter the project directory:

```bash
cd repository
```

Check the current status:

```bash
git status
```

You can now start working on the project.

---

## 📝 Summary

The most common command is:

```bash
git clone URL
```

`git clone` is useful when you want to create a local copy of an existing Git repository.

---

# 🇵🇸 العربية

# 📥 Git Clone

يُستخدم الأمر `git clone` لإنشاء نسخة محلية من مستودع بعيد موجود.

ويُستخدم عادةً عندما تريد تنزيل مشروع من GitHub والبدء بالعمل عليه على جهازك.

---

## 🔹 الاستخدام الأساسي

لنسخ مستودع:

```bash
git clone https://github.com/username/repository.git
```

يقوم Git بتنزيل المستودع وإنشاء مجلد جديد يحتوي على ملفات المشروع وتاريخ Git.

---

## 🔹 نسخ المستودع إلى مجلد محدد

يمكنك اختيار اسم المجلد:

```bash
git clone https://github.com/username/repository.git my-project
```

سيقوم Git بإنشاء مجلد باسم `my-project`.

---

## 🔹 نسخ فرع محدد

لنسخ فرع محدد:

```bash
git clone -b feature-login https://github.com/username/repository.git
```

يقوم هذا بنسخ المستودع والانتقال إلى الفرع المحدد.

---

## 🔹 النسخ باستخدام SSH

إذا كان SSH مُعدًا على جهازك، يمكنك استخدام رابط SSH:

```bash
git clone git@github.com:username/repository.git
```

---

## 🔹 ماذا يحدث بعد عملية Clone؟

بعد نسخ المستودع، يقوم Git تلقائيًا بـ:

- تنزيل ملفات المشروع
- تنزيل تاريخ Git
- إنشاء مستودع محلي
- إضافة المستودع البعيد
- تسمية المستودع البعيد عادةً باسم `origin`
- الانتقال إلى الفرع الافتراضي

يمكنك التحقق من الاتصال بالمستودع البعيد باستخدام:

```bash
git remote -v
```

---

## 💡 مثال على سير العمل

انسخ المشروع:

```bash
git clone https://github.com/username/repository.git
```

ادخل إلى مجلد المشروع:

```bash
cd repository
```

تحقق من الحالة الحالية:

```bash
git status
```

الآن يمكنك البدء بالعمل على المشروع.

---

## 📝 الخلاصة

الأمر الأكثر استخدامًا هو:

```bash
git clone URL
```

يُعد `git clone` مفيدًا عندما تريد إنشاء نسخة محلية من مستودع Git موجود.
