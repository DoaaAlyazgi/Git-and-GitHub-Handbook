# 🔀 Git Rebase

## 🌐 English

`git rebase` is used to move or reapply commits from one branch on top of another branch.

It is commonly used to update a feature branch with the latest changes from the main branch while keeping a linear commit history.

---

## 🔹 Basic Usage

First, switch to the branch you want to rebase:

```bash
git switch feature-branch
```

Then rebase it onto `main`:

```bash
git rebase main
```

Git takes the commits from your feature branch and reapplies them on top of the latest `main`.

---

## 🔹 Example

Before rebase:

```text
A -- B -- C
     \
      D -- E
```

After:

```text
A -- B -- C -- D' -- E'
```

The changes from `D` and `E` are reapplied after `C`.

The rebased commits receive new commit IDs.

---

## 🔹 Update Your Branch Before Rebase

You can first update your local `main` branch:

```bash
git switch main
git pull
```

Then return to your feature branch:

```bash
git switch feature-branch
```

And run:

```bash
git rebase main
```

---

## 🔹 Continue After a Conflict

If Git stops because of a conflict:

```bash
git status
```

Resolve the conflict, stage the file:

```bash
git add filename.txt
```

Then continue:

```bash
git rebase --continue
```

---

## 🔹 Abort a Rebase

If you decide not to continue:

```bash
git rebase --abort
```

This cancels the rebase operation.

---

## ⚠️ Important Warning

Rebase rewrites commit history.

Avoid rebasing commits that have already been shared with other developers unless you understand the consequences.

---

## 📝 Summary

```bash
git switch feature-branch
git rebase main
```

Use Rebase to update a branch and maintain a cleaner, linear commit history.

---

# 🇵🇸 العربية

# 🔀 Git Rebase

## العربية

يُستخدم `git rebase` لنقل أو إعادة تطبيق Commits الخاصة بفرع فوق فرع آخر.

يُستخدم عادةً لتحديث فرع يحتوي على ميزات جديدة بأحدث التغييرات الموجودة في الفرع الرئيسي، مع الحفاظ على سجل Commits خطي.

---

## 🔹 الاستخدام الأساسي

أولًا، انتقل إلى الفرع الذي تريد تنفيذ Rebase له:

```bash
git switch feature-branch
```

ثم نفذ Rebase على `main`:

```bash
git rebase main
```

يقوم Git بأخذ Commits الموجودة في فرعك وإعادة تطبيقها فوق أحدث نسخة من `main`.

---

## 🔹 مثال

قبل Rebase:

```text
A -- B -- C
     \
      D -- E
```

بعد Rebase:

```text
A -- B -- C -- D' -- E'
```

يتم إعادة تطبيق التغييرات الموجودة في `D` و `E` بعد `C`.

تحصل الـ Commits التي تمت إعادة تطبيقها على Commit IDs جديدة.

---

## 🔹 تحديث الفرع قبل Rebase

يمكنك أولًا تحديث فرع `main` المحلي:

```bash
git switch main
git pull
```

ثم العودة إلى فرع الميزات:

```bash
git switch feature-branch
```

ثم تنفيذ:

```bash
git rebase main
```

---

## 🔹 متابعة Rebase بعد حدوث تعارض

إذا توقف Git بسبب تعارض:

```bash
git status
```

قم بحل التعارض ثم أضف الملف:

```bash
git add filename.txt
```

ثم تابع العملية:

```bash
git rebase --continue
```

---

## 🔹 إلغاء Rebase

إذا قررت عدم المتابعة:

```bash
git rebase --abort
```

يقوم هذا بإلغاء عملية Rebase.

---

## ⚠️ تحذير مهم

يقوم Rebase بإعادة كتابة سجل الـ Commits.

تجنب تنفيذ Rebase على Commits تمت مشاركتها بالفعل مع مطورين آخرين إلا إذا كنت تفهم النتائج.

---

## 📝 الخلاصة

```bash
git switch feature-branch
git rebase main
```

استخدم Rebase لتحديث الفرع والحفاظ على سجل Commits أكثر نظافة وخطية.
