# 🌐 Git Remote

## 🌐 English

A remote repository is a version of your Git repository that is hosted somewhere else, such as GitHub.

The remote allows your local repository to communicate with the repository hosted on GitHub.

---

## 🔹 Add a Remote

To connect your local repository to GitHub:

```bash
git remote add origin repository-url
```

Example:

```bash
git remote add origin https://github.com/username/project.git
```

---

## 🔹 View Remotes

To see the configured remote repositories:

```bash
git remote -v
```

Example:

```text
origin  https://github.com/username/project.git (fetch)
origin  https://github.com/username/project.git (push)
```

---

## 🔹 Change a Remote URL

You can change the URL of an existing remote:

```bash
git remote set-url origin new-url
```

---

## 🔹 Remove a Remote

To remove a remote:

```bash
git remote remove origin
```

---

## 💡 Why Use Remotes?

Remotes allow you to:

- Push changes to GitHub
- Pull changes from GitHub
- Collaborate with other developers
- Keep local and remote repositories synchronized

---

## 📝 Summary

Common remote commands:

```bash
git remote -v
git remote add origin repository-url
git remote set-url origin new-url
git remote remove origin
```

---

# 🇵🇸 العربية

# 🌐 Git Remote

## العربية

المستودع البعيد هو نسخة من مستودع Git الخاص بك مستضافة في مكان آخر، مثل GitHub.

يسمح الـ Remote للمستودع المحلي بالتواصل مع المستودع الموجود على GitHub.

---

## 🔹 إضافة Remote

لربط المستودع المحلي بمستودع GitHub:

```bash
git remote add origin repository-url
```

مثال:

```bash
git remote add origin https://github.com/username/project.git
```

---

## 🔹 عرض الـ Remotes

لمشاهدة المستودعات البعيدة التي تم إعدادها:

```bash
git remote -v
```

مثال:

```text
origin  https://github.com/username/project.git (fetch)
origin  https://github.com/username/project.git (push)
```

---

## 🔹 تغيير رابط Remote

يمكنك تغيير رابط Remote موجود:

```bash
git remote set-url origin new-url
```

---

## 🔹 حذف Remote

لحذف Remote:

```bash
git remote remove origin
```

---

## 💡 لماذا نستخدم Remotes؟

تسمح لك Remotes بـ:

- رفع التغييرات إلى GitHub
- جلب التغييرات من GitHub
- التعاون مع المطورين الآخرين
- إبقاء المستودع المحلي والبعيد متزامنين

---

## 📝 الخلاصة

أهم أوامر Remote:

```bash
git remote -v
git remote add origin repository-url
git remote set-url origin new-url
git remote remove origin
```
