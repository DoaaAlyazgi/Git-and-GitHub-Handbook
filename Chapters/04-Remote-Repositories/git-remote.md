# 🌐 Git Remote

## 🌐 English

`git remote` is used to manage connections between your local Git repository and remote repositories.

A remote repository is usually hosted on a platform such as GitHub.

---

## 🔹 View Remote Repositories

To see the remote repositories connected to your project:

```bash
git remote
```

Example:

```text
origin
```

`origin` is the default name commonly used for the main remote repository.

---

## 🔹 View Remote URLs

To see the URLs associated with your remotes:

```bash
git remote -v
```

Example:

```text
origin  https://github.com/username/repository.git (fetch)
origin  https://github.com/username/repository.git (push)
```

This shows the URL used for fetching and pushing changes.

---

## 🔹 Add a Remote Repository

To connect your local repository to a remote repository:

```bash
git remote add origin https://github.com/username/repository.git
```

Here:

- `origin` is the name of the remote.
- The URL is the address of the remote repository.

---

## 🔹 Change a Remote URL

To change the URL of an existing remote:

```bash
git remote set-url origin https://github.com/username/new-repository.git
```

This is useful if the repository URL changes.

---

## 🔹 Rename a Remote

To rename a remote:

```bash
git remote rename origin upstream
```

This changes the remote name from `origin` to `upstream`.

---

## 🔹 Remove a Remote

To remove a remote:

```bash
git remote remove origin
```

This removes the connection to the remote repository from your local Git configuration.

It does not delete the remote repository itself from GitHub.

---

## 🔹 Show Remote Information

To see detailed information about a remote:

```bash
git remote show origin
```

This can display information such as:

- Remote URL
- Tracked branches
- Remote branches
- Push and fetch information

---

## 💡 Example

Suppose you have a local project and a GitHub repository.

First, initialize Git:

```bash
git init
```

Then connect the project to GitHub:

```bash
git remote add origin https://github.com/username/repository.git
```

Check the connection:

```bash
git remote -v
```

You can then push your changes:

```bash
git push -u origin main
```

---

## 📝 Summary

The most common `git remote` commands are:

```bash
git remote
```

View remote names.

```bash
git remote -v
```

View remote URLs.

```bash
git remote add origin URL
```

Add a remote repository.

```bash
git remote set-url origin URL
```

Change a remote URL.

```bash
git remote remove origin
```

Remove a remote.

```bash
git remote show origin
```

Show detailed information about a remote.

---

# 🇵🇸 العربية

# 🌐 Git Remote

يُستخدم الأمر `git remote` لإدارة الاتصالات بين مستودع Git المحلي والمستودعات البعيدة.

عادةً ما يكون المستودع البعيد مستضافًا على منصة مثل GitHub.

---

## 🔹 عرض المستودعات البعيدة

لعرض المستودعات البعيدة المرتبطة بمشروعك:

```bash
git remote
```

مثال:

```text
origin
```

`origin` هو الاسم الافتراضي الشائع الاستخدام للمستودع البعيد الرئيسي.

---

## 🔹 عرض روابط المستودعات البعيدة

لعرض الروابط المرتبطة بالمستودعات البعيدة:

```bash
git remote -v
```

مثال:

```text
origin  https://github.com/username/repository.git (fetch)
origin  https://github.com/username/repository.git (push)
```

يعرض هذا الأمر الرابط المستخدم لجلب التغييرات والرابط المستخدم لرفعها.

---

## 🔹 إضافة مستودع بعيد

لربط المستودع المحلي بمستودع بعيد:

```bash
git remote add origin https://github.com/username/repository.git
```

هنا:

- `origin` هو اسم المستودع البعيد.
- الرابط هو عنوان المستودع البعيد.

---

## 🔹 تغيير رابط المستودع البعيد

لتغيير رابط مستودع بعيد موجود:

```bash
git remote set-url origin https://github.com/username/new-repository.git
```

يكون هذا مفيدًا عندما يتغير رابط المستودع.

---

## 🔹 إعادة تسمية المستودع البعيد

لإعادة تسمية المستودع البعيد:

```bash
git remote rename origin upstream
```

يغير هذا الأمر اسم المستودع البعيد من `origin` إلى `upstream`.

---

## 🔹 إزالة مستودع بعيد

لإزالة مستودع بعيد:

```bash
git remote remove origin
```

يقوم هذا بإزالة الاتصال بالمستودع البعيد من إعدادات Git المحلية.

ولا يقوم بحذف المستودع البعيد نفسه من GitHub.

---

## 🔹 عرض معلومات المستودع البعيد

لعرض معلومات تفصيلية عن مستودع بعيد:

```bash
git remote show origin
```

يمكن أن يعرض هذا الأمر معلومات مثل:

- رابط المستودع البعيد
- الفروع المتتبعة
- الفروع البعيدة
- معلومات الرفع والجلب

---

## 💡 مثال

لنفترض أن لديك مشروعًا محليًا ومستودعًا على GitHub.

أولًا، قم بإنشاء مستودع Git:

```bash
git init
```

ثم اربط المشروع بمستودع GitHub:

```bash
git remote add origin https://github.com/username/repository.git
```

تحقق من الاتصال:

```bash
git remote -v
```

بعد ذلك يمكنك رفع التغييرات:

```bash
git push -u origin main
```

---

## 📝 الخلاصة

أهم أوامر `git remote` هي:

```bash
git remote
```

لعرض أسماء المستودعات البعيدة.

```bash
git remote -v
```

لعرض روابط المستودعات البعيدة.

```bash
git remote add origin URL
```

لإضافة مستودع بعيد.

```bash
git remote set-url origin URL
```

لتغيير رابط المستودع البعيد.

```bash
git remote remove origin
```

لإزالة مستودع بعيد.

```bash
git remote show origin
```

لعرض معلومات تفصيلية عن المستودع البعيد.
