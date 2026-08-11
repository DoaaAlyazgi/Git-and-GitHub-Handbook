# 🔗 Git Merge

## 🌐 English

`git merge` is used to combine the changes from one branch into another branch.

It is commonly used to merge a completed feature branch into the main branch.

---

## 🔹 Basic Usage

First, switch to the branch that you want to merge changes into:

```bash
git switch main
```

Then merge the other branch:

```bash
git merge feature-login
```

This combines the changes from `feature-login` into `main`.

---

## 🔹 Example

Suppose you have two branches:

```text
main
feature-login
```

You worked on the login feature inside `feature-login`.

When the feature is ready, switch to `main`:

```bash
git switch main
```

Then merge the feature branch:

```bash
git merge feature-login
```

The changes from `feature-login` are now included in `main`.

---

## 🔹 Fast-Forward Merge

A fast-forward merge happens when the target branch has not received any new commits since the feature branch was created.

Example:

```bash
git switch main
git merge feature-login
```

Git can simply move the `main` branch pointer forward to the latest commit.

---

## 🔹 Merge Commit

A merge commit may be created when both branches have new commits.

Example:

```text
A---B---C main
     \
      D---E feature-login
```

After merging:

```text
A---B---C-------M main
     \         /
      D---E----
```

`M` represents the merge commit.

---

## 🔹 Merge Conflicts

Sometimes Git cannot automatically combine the changes because the same part of a file was changed differently in both branches.

This creates a **merge conflict**.

Git may mark the conflict inside the file like this:

```text
<<<<<<< HEAD
Current branch changes
=======
Incoming branch changes
>>>>>>> feature-login
```

You must manually choose which changes to keep.

After resolving the conflict:

```bash
git add .
git commit
```

The merge is then completed.

---

## 🔹 Abort a Merge

If you want to cancel a merge that has conflicts:

```bash
git merge --abort
```

This attempts to return the repository to the state it was in before the merge started.

---

## 🔹 Delete the Merged Branch

After successfully merging a feature branch, you can delete it:

```bash
git branch -d feature-login
```

This removes the local branch after its changes have been merged.

---

## 💡 Best Practice

Before merging a branch, it is a good idea to make sure your working directory is clean:

```bash
git status
```

Then switch to the target branch:

```bash
git switch main
```

Update it if necessary:

```bash
git pull
```

Finally, merge the feature branch:

```bash
git merge feature-login
```

---

## 📝 Summary

The basic merge workflow is:

```bash
git switch main
git merge feature-login
```

If a conflict occurs:

```bash
git status
```

Resolve the conflicts in the affected files, then:

```bash
git add .
git commit
```

If you want to cancel the merge:

```bash
git merge --abort
```

Git merge is an essential command for combining work from different branches.

---

# 🇵🇸 العربية

# 🔗 Git Merge

## العربية

يُستخدم الأمر `git merge` لدمج التغييرات الموجودة في فرع مع فرع آخر.

ويُستخدم عادةً لدمج فرع يحتوي على ميزة مكتملة مع الفرع الرئيسي.

---

## 🔹 الاستخدام الأساسي

أولًا، انتقل إلى الفرع الذي تريد دمج التغييرات فيه:

```bash
git switch main
```

ثم قم بدمج الفرع الآخر:

```bash
git merge feature-login
```

يقوم هذا بدمج التغييرات الموجودة في `feature-login` داخل `main`.

---

## 🔹 مثال

لنفترض أن لديك فرعين:

```text
main
feature-login
```

لقد عملت على ميزة تسجيل الدخول داخل `feature-login`.

عندما تصبح الميزة جاهزة، انتقل إلى `main`:

```bash
git switch main
```

ثم ادمج فرع الميزة:

```bash
git merge feature-login
```

تصبح التغييرات الموجودة في `feature-login` الآن جزءًا من `main`.

---

## 🔹 الدمج السريع Fast-Forward

يحدث الدمج السريع عندما لا يحتوي الفرع المستهدف على Commits جديدة منذ إنشاء فرع الميزة.

مثال:

```bash
git switch main
git merge feature-login
```

في هذه الحالة يستطيع Git تحريك مؤشر فرع `main` مباشرةً إلى أحدث Commit.

---

## 🔹 Merge Commit

قد يقوم Git بإنشاء Merge Commit عندما يحتوي كلا الفرعين على Commits جديدة.

مثال:

```text
A---B---C main
     \
      D---E feature-login
```

بعد الدمج:

```text
A---B---C-------M main
     \         /
      D---E----
```

يمثل `M` الـ Merge Commit.

---

## 🔹 تعارضات الدمج Merge Conflicts

في بعض الحالات لا يستطيع Git دمج التغييرات تلقائيًا، خصوصًا عندما يتم تعديل نفس الجزء من الملف بطريقة مختلفة في الفرعين.

ينتج عن ذلك **Merge Conflict**.

قد يضع Git علامات التعارض داخل الملف بالشكل التالي:

```text
<<<<<<< HEAD
Current branch changes
=======
Incoming branch changes
>>>>>>> feature-login
```

يجب عليك اختيار التغييرات التي تريد الاحتفاظ بها وحل التعارض يدويًا.

بعد حل التعارض:

```bash
git add .
git commit
```

وبذلك يكتمل الدمج.

---

## 🔹 إلغاء عملية الدمج

إذا أردت إلغاء عملية دمج تحتوي على تعارضات:

```bash
git merge --abort
```

يحاول هذا الأمر إعادة المستودع إلى الحالة التي كان عليها قبل بدء عملية الدمج.

---

## 🔹 حذف الفرع بعد دمجه

بعد نجاح عملية الدمج، يمكنك حذف فرع الميزة:

```bash
git branch -d feature-login
```

يقوم هذا بحذف الفرع المحلي بعد دمج التغييرات الخاصة به.

---

## 💡 أفضل ممارسة

قبل دمج أي فرع، من الأفضل التأكد من أن مجلد العمل لا يحتوي على تغييرات غير محفوظة:

```bash
git status
```

ثم الانتقال إلى الفرع المستهدف:

```bash
git switch main
```

وتحديثه إذا لزم الأمر:

```bash
git pull
```

وأخيرًا دمج فرع الميزة:

```bash
git merge feature-login
```

---

## 📝 الخلاصة

سير العمل الأساسي للدمج هو:

```bash
git switch main
git merge feature-login
```

إذا حدث تعارض:

```bash
git status
```

قم بحل التعارضات في الملفات المتأثرة، ثم:

```bash
git add .
git commit
```

إذا أردت إلغاء عملية الدمج:

```bash
git merge --abort
```

يُعد `git merge` من الأوامر الأساسية لدمج العمل من فروع مختلفة.
