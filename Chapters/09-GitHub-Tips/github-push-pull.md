# 🔄 Git Push and Pull

## 🌐 English

`git push` and `git pull` are used to synchronize changes between your local repository and a remote repository such as GitHub.

---

## 🔹 Git Push

`git push` sends your local commits to the remote repository.

Basic usage:

```bash
git push origin main
```

For a feature branch:

```bash
git push origin feature-branch
```

---

## 🔹 Git Pull

`git pull` retrieves changes from the remote repository and integrates them into your current branch.

Basic usage:

```bash
git pull origin main
```

---

## 🔄 Typical Workflow

A common workflow is:

```bash
git add .
git commit -m "Update project"
git push origin main
```

To get the latest changes:

```bash
git pull origin main
```

---

## 🔹 Push a New Branch

To push a new branch and set its upstream:

```bash
git push -u origin feature-branch
```

After that, you can usually use:

```bash
git push
```

and:

```bash
git pull
```

---

## ⚠️ Important Note

Always make sure you understand the changes on the remote repository before pushing or pulling, especially when working with other developers.

---

## 📝 Summary

```bash
git push
git pull
```

Use `push` to send local commits to a remote repository.

Use `pull` to retrieve and integrate remote changes.

---

# 🇵🇸 العربية

# 🔄 Git Push و Git Pull

## العربية

يُستخدم `git push` و `git pull` لمزامنة التغييرات بين المستودع المحلي والمستودع البعيد مثل GitHub.

---

## 🔹 Git Push

يقوم `git push` بإرسال الـ Commits الموجودة في المستودع المحلي إلى المستودع البعيد.

الاستخدام الأساسي:

```bash
git push origin main
```

ولفرع يحتوي على ميزة:

```bash
git push origin feature-branch
```

---

## 🔹 Git Pull

يقوم `git pull` بجلب التغييرات من المستودع البعيد ودمجها مع الفرع الحالي.

الاستخدام الأساسي:

```bash
git pull origin main
```

---

## 🔄 سير العمل المعتاد

يمكن أن يكون سير العمل بالشكل التالي:

```bash
git add .
git commit -m "Update project"
git push origin main
```

وللحصول على أحدث التغييرات:

```bash
git pull origin main
```

---

## 🔹 رفع فرع جديد

لرفع فرع جديد وربطه بالـ Remote:

```bash
git push -u origin feature-branch
```

بعد ذلك يمكنك غالبًا استخدام:

```bash
git push
```

و:

```bash
git pull
```

---

## ⚠️ ملاحظة مهمة

تأكد دائمًا من فهم التغييرات الموجودة في المستودع البعيد قبل تنفيذ Push أو Pull، خصوصًا عند العمل مع مطورين آخرين.

---

## 📝 الخلاصة

```bash
git push
git pull
```

استخدم `push` لإرسال الـ Commits المحلية إلى المستودع البعيد.

واستخدم `pull` لجلب ودمج التغييرات الموجودة في المستودع البعيد.
