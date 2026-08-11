# 🌿 Git Branch

## 🌐 English

`git branch` is used to create, view, rename, and delete branches in a Git repository.

Branches allow you to work on different features or changes without directly affecting other branches.

---

## 🔹 View Branches

To view the branches in your repository:

```bash
git branch
```

The current branch is marked with an asterisk `*`.

Example:

```text
* main
  feature-login
  development
```

This means that the current branch is `main`.

---

## 🔹 Create a New Branch

To create a new branch:

```bash
git branch feature-login
```

This creates a branch named `feature-login`.

The command creates the branch but does not switch you to it.

---

## 🔹 Create and Switch to a Branch

You can create a branch and switch to it using:

```bash
git switch -c feature-login
```

This creates the branch and immediately switches to it.

---

## 🔹 Rename a Branch

To rename the current branch:

```bash
git branch -m new-name
```

Example:

```bash
git branch -m feature-auth
```

To rename another branch:

```bash
git branch -m old-name new-name
```

---

## 🔹 Delete a Branch

To delete a branch that has already been merged:

```bash
git branch -d feature-login
```

If Git prevents you from deleting the branch and you are sure you want to remove it:

```bash
git branch -D feature-login
```

Use `-D` carefully because it can delete a branch even if it contains unmerged changes.

---

## 🔹 List All Branches

To list local branches:

```bash
git branch
```

To list remote branches:

```bash
git branch -r
```

To list both local and remote branches:

```bash
git branch -a
```

---

## 💡 Example Workflow

Create a new feature branch:

```bash
git branch feature-login
```

Switch to it:

```bash
git switch feature-login
```

Make your changes and create a commit:

```bash
git add .
git commit -m "Add login feature"
```

Return to the main branch:

```bash
git switch main
```

After the feature has been merged, you can delete the branch:

```bash
git branch -d feature-login
```

---

## 📝 Summary

`git branch` is useful for managing branches in a Git repository.

Common commands include:

```bash
git branch
```

View branches.

```bash
git branch feature-login
```

Create a new branch.

```bash
git branch -m new-name
```

Rename a branch.

```bash
git branch -d feature-login
```

Delete a branch.

Branches help keep different lines of development separate and organized.

---

# 🇵🇸 العربية

# 🌿 Git Branch

## العربية

يُستخدم الأمر `git branch` لإنشاء الفروع وعرضها وإعادة تسميتها وحذفها داخل مستودع Git.

تسمح لك الفروع بالعمل على ميزات أو تغييرات مختلفة دون التأثير مباشرة على الفروع الأخرى.

---

## 🔹 عرض الفروع

لعرض الفروع الموجودة في المستودع:

```bash
git branch
```

يتم وضع علامة النجمة `*` بجانب الفرع الحالي.

مثال:

```text
* main
  feature-login
  development
```

هذا يعني أن الفرع الحالي هو `main`.

---

## 🔹 إنشاء فرع جديد

لإنشاء فرع جديد:

```bash
git branch feature-login
```

يقوم هذا الأمر بإنشاء فرع باسم `feature-login`.

لكن الأمر يقوم بإنشاء الفرع فقط ولا ينتقل إليه تلقائيًا.

---

## 🔹 إنشاء فرع والانتقال إليه

يمكنك إنشاء فرع جديد والانتقال إليه مباشرة باستخدام:

```bash
git switch -c feature-login
```

يقوم هذا الأمر بإنشاء الفرع ثم الانتقال إليه مباشرة.

---

## 🔹 إعادة تسمية فرع

لإعادة تسمية الفرع الحالي:

```bash
git branch -m new-name
```

مثال:

```bash
git branch -m feature-auth
```

لإعادة تسمية فرع آخر:

```bash
git branch -m old-name new-name
```

---

## 🔹 حذف فرع

لحذف فرع تم دمجه بالفعل:

```bash
git branch -d feature-login
```

إذا منعك Git من حذف الفرع وكنت متأكدًا من أنك تريد حذفه:

```bash
git branch -D feature-login
```

استخدم الخيار `-D` بحذر، لأنه يمكن أن يحذف الفرع حتى لو كان يحتوي على تغييرات لم يتم دمجها.

---

## 🔹 عرض جميع الفروع

لعرض الفروع المحلية:

```bash
git branch
```

لعرض الفروع الموجودة على المستودع البعيد:

```bash
git branch -r
```

لعرض الفروع المحلية والبعيدة معًا:

```bash
git branch -a
```

---

## 💡 مثال على سير العمل

أنشئ فرعًا جديدًا لميزة:

```bash
git branch feature-login
```

انتقل إليه:

```bash
git switch feature-login
```

قم بإجراء التغييرات وإنشاء Commit:

```bash
git add .
git commit -m "Add login feature"
```

ارجع إلى الفرع الرئيسي:

```bash
git switch main
```

بعد دمج الميزة، يمكنك حذف الفرع:

```bash
git branch -d feature-login
```

---

## 📝 الخلاصة

يُستخدم `git branch` لإدارة الفروع داخل مستودع Git.

من الأوامر الشائعة:

```bash
git branch
```

لعرض الفروع.

```bash
git branch feature-login
```

لإنشاء فرع جديد.

```bash
git branch -m new-name
```

لإعادة تسمية فرع.

```bash
git branch -d feature-login
```

لحذف فرع.

تساعد الفروع على إبقاء مسارات التطوير المختلفة منفصلة ومنظمة.
