# ⬆️ Git Push

## 🌐 English

`git push` is used to upload local commits to a remote repository.

It allows you to send your committed changes from your local repository to platforms such as GitHub.

---

## 🔹 Basic Usage

To push your current branch:

```bash
git push
```

Git uploads your local commits to the configured remote repository.

---

## 🔹 Push a Specific Branch

To push a specific branch:

```bash
git push origin feature-login
```

Here:

- `origin` is the name of the remote repository.
- `feature-login` is the branch you want to push.

---

## 🔹 Push a New Branch

When pushing a branch for the first time:

```bash
git push -u origin feature-login
```

The `-u` option sets the remote branch as the upstream branch.

After that, you can usually use:

```bash
git push
```

---

## 🔹 Push the Main Branch

To push the `main` branch:

```bash
git push origin main
```

---

## 🔹 Push All Branches

To push all local branches:

```bash
git push --all
```

---

## ⚠️ Before Using `git push`

Make sure your changes have been committed:

```bash
git status
```

Then:

```bash
git add .
git commit -m "Describe your changes"
git push
```

---

## 💡 Example Workflow

Create a change:

```bash
git add .
```

Create a commit:

```bash
git commit -m "Update homepage"
```

Push the commit:

```bash
git push
```

The commit is now uploaded to the remote repository.

---

## 📝 Summary

The most common commands are:

```bash
git push
```

Push the current branch.

```bash
git push origin main
```

Push the `main` branch.

```bash
git push -u origin feature-login
```

Push a new branch and set its upstream branch.

---

# 🇵🇸 العربية

# ⬆️ Git Push

يُستخدم الأمر `git push` لرفع الـ Commits المحلية إلى المستودع البعيد.

يسمح لك بإرسال التغييرات التي قمت بحفظها محليًا إلى منصات مثل GitHub.

---

## 🔹 الاستخدام الأساسي

لرفع الفرع الحالي:

```bash
git push
```

يقوم Git برفع الـ Commits المحلية إلى المستودع البعيد المرتبط.

---

## 🔹 رفع فرع محدد

لرفع فرع محدد:

```bash
git push origin feature-login
```

هنا:

- `origin` هو اسم المستودع البعيد.
- `feature-login` هو الفرع الذي تريد رفعه.

---

## 🔹 رفع فرع جديد

عند رفع فرع لأول مرة:

```bash
git push -u origin feature-login
```

يقوم الخيار `-u` بتعيين الفرع البعيد كفرع Upstream للفرع المحلي.

بعد ذلك يمكنك غالبًا استخدام:

```bash
git push
```

---

## 🔹 رفع الفرع الرئيسي

لرفع فرع `main`:

```bash
git push origin main
```

---

## 🔹 رفع جميع الفروع

لرفع جميع الفروع المحلية:

```bash
git push --all
```

---

## ⚠️ قبل استخدام `git push`

تأكد من أنك قمت بإنشاء Commit للتغييرات:

```bash
git status
```

ثم:

```bash
git add .
git commit -m "Describe your changes"
git push
```

---

## 💡 مثال على سير العمل

أضف التغيير:

```bash
git add .
```

أنشئ Commit:

```bash
git commit -m "Update homepage"
```

ارفع الـ Commit:

```bash
git push
```

الآن تم رفع الـ Commit إلى المستودع البعيد.

---

## 📝 الخلاصة

الأوامر الأكثر استخدامًا هي:

```bash
git push
```

لرفع الفرع الحالي.

```bash
git push origin main
```

لرفع فرع `main`.

```bash
git push -u origin feature-login
```

لرفع فرع جديد وتعيين الفرع البعيد كـ Upstream.
