# 📦 Git Stash

## 🌐 English

`git stash` is used to temporarily save changes that you have made in your working directory without creating a commit.

It is useful when you need to switch branches or work on something else while keeping your unfinished changes safe.

---

## 🔹 Basic Usage

To temporarily save your changes:

```bash
git stash
```

Git saves your modified files and returns the working directory to a clean state.

You can then switch branches or perform other Git operations.

---

## 🔹 Stash with a Message

You can give your stash a descriptive message:

```bash
git stash push -m "Work in progress"
```

This makes it easier to identify the stash later.

---

## 🔹 View Stashes

To see your saved stashes:

```bash
git stash list
```

Example:

```text
stash@{0}: On main: Work in progress
stash@{1}: On feature-login: Update login page
```

---

## 🔹 Apply a Stash

To restore the latest stash without deleting it:

```bash
git stash apply
```

The changes are restored to your working directory, but the stash remains in the stash list.

---

## 🔹 Apply and Remove a Stash

To restore the latest stash and remove it from the stash list:

```bash
git stash pop
```

This is useful when you no longer need to keep the stash after restoring it.

---

## 🔹 Stash Specific Changes

You can stash specific files:

```bash
git stash push filename.txt
```

You can also specify multiple files:

```bash
git stash push file1.txt file2.txt
```

---

## 🔹 Include Untracked Files

By default, `git stash` does not include untracked files.

To include untracked files:

```bash
git stash -u
```

---

## 🔹 Create a Branch from a Stash

If the changes in a stash should become the starting point of a new branch:

```bash
git stash branch feature-login
```

Git creates a new branch, applies the stash, and removes the stash if the operation succeeds.

---

## 💡 Example Workflow

Suppose you are working on a feature:

```bash
git status
```

You have unfinished changes, but you need to switch to another branch.

Save your changes:

```bash
git stash
```

Switch branches:

```bash
git switch main
```

Do your work on `main`.

Later, return to your feature branch:

```bash
git switch feature-login
```

Restore your changes:

```bash
git stash pop
```

Your unfinished work is now restored.

---

## ⚠️ Important Note

`git stash` is useful for temporary work.

If your changes are important and represent a meaningful step in your project, creating a commit is usually a better choice.

Stashes are intended as temporary storage rather than a replacement for commits.

---

## 📝 Summary

The most common commands are:

```bash
git stash
```

Temporarily save changes.

```bash
git stash list
```

View saved stashes.

```bash
git stash apply
```

Restore a stash without deleting it.

```bash
git stash pop
```

Restore and remove the latest stash.

```bash
git stash -u
```

Include untracked files.

```bash
git stash branch branch-name
```

Create a branch from a stash.

---

# 🇵🇸 العربية

# 📦 Git Stash

## العربية

يُستخدم الأمر `git stash` لحفظ التغييرات التي قمت بها في مجلد العمل بشكل مؤقت دون إنشاء Commit.

يكون هذا مفيدًا عندما تحتاج إلى الانتقال بين الفروع أو العمل على شيء آخر مع الحفاظ على التغييرات غير المكتملة بأمان.

---

## 🔹 الاستخدام الأساسي

لحفظ التغييرات بشكل مؤقت:

```bash
git stash
```

يقوم Git بحفظ الملفات التي تم تعديلها وإعادة مجلد العمل إلى حالة نظيفة.

بعد ذلك يمكنك الانتقال بين الفروع أو تنفيذ عمليات Git أخرى.

---

## 🔹 حفظ Stash مع رسالة

يمكنك إضافة رسالة توضح محتوى الـ Stash:

```bash
git stash push -m "Work in progress"
```

يساعد ذلك على معرفة محتوى الـ Stash بسهولة لاحقًا.

---

## 🔹 عرض Stashes

لعرض التغييرات المحفوظة:

```bash
git stash list
```

مثال:

```text
stash@{0}: On main: Work in progress
stash@{1}: On feature-login: Update login page
```

---

## 🔹 تطبيق Stash

لاستعادة أحدث Stash دون حذفه:

```bash
git stash apply
```

يتم استعادة التغييرات إلى مجلد العمل، لكن يبقى الـ Stash موجودًا في قائمة Stashes.

---

## 🔹 تطبيق وحذف Stash

لاستعادة أحدث Stash وحذفه من القائمة:

```bash
git stash pop
```

يكون هذا مفيدًا عندما لا تعود بحاجة إلى الاحتفاظ بالـ Stash بعد استعادة التغييرات.

---

## 🔹 حفظ ملفات محددة

يمكنك حفظ ملفات محددة في Stash:

```bash
git stash push filename.txt
```

ويمكنك أيضًا تحديد عدة ملفات:

```bash
git stash push file1.txt file2.txt
```

---

## 🔹 تضمين الملفات غير المتتبعة

بشكل افتراضي، لا يقوم `git stash` بحفظ الملفات غير المتتبعة.

لتضمين الملفات غير المتتبعة:

```bash
git stash -u
```

---

## 🔹 إنشاء فرع من Stash

إذا كانت التغييرات الموجودة في Stash يجب أن تكون نقطة البداية لفرع جديد:

```bash
git stash branch feature-login
```

يقوم Git بإنشاء فرع جديد وتطبيق الـ Stash عليه، ثم يحذف الـ Stash إذا نجحت العملية.

---

## 💡 مثال على سير العمل

لنفترض أنك تعمل على ميزة:

```bash
git status
```

لديك تغييرات غير مكتملة، لكنك تحتاج إلى الانتقال إلى فرع آخر.

احفظ تغييراتك:

```bash
git stash
```

انتقل إلى الفرع الآخر:

```bash
git switch main
```

قم بعملك على `main`.

لاحقًا، ارجع إلى فرع الميزة:

```bash
git switch feature-login
```

استعد تغييراتك:

```bash
git stash pop
```

الآن تمت استعادة عملك غير المكتمل.

---

## ⚠️ ملاحظة مهمة

يُستخدم `git stash` لحفظ العمل بشكل مؤقت.

إذا كانت تغييراتك مهمة وتمثل خطوة حقيقية في مشروعك، فمن الأفضل عادةً إنشاء Commit لها.

الـ Stash مخصص للتخزين المؤقت وليس بديلًا عن الـ Commits.

---

## 📝 الخلاصة

الأوامر الأكثر استخدامًا هي:

```bash
git stash
```

لحفظ التغييرات بشكل مؤقت.

```bash
git stash list
```

لعرض الـ Stashes المحفوظة.

```bash
git stash apply
```

لاستعادة Stash دون حذفه.

```bash
git stash pop
```

لاستعادة وحذف أحدث Stash.

```bash
git stash -u
```

لتضمين الملفات غير المتتبعة.

```bash
git stash branch branch-name
```

لإنشاء فرع من Stash.
