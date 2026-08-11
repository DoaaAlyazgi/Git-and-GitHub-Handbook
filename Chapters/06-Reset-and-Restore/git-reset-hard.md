# 🔴 Git Reset Hard

## 🌐 English

`git reset --hard` moves the current branch to another commit and updates the staging area and working directory to match that commit.

This means that changes in the staging area and working directory can be permanently discarded.

---

## 🔹 Basic Usage

To move back one commit:

```bash
git reset --hard HEAD~1
```

The current branch moves back one commit and changes introduced after that commit are discarded.

---

## 🔹 Reset to a Specific Commit

You can reset to a specific commit:

```bash
git reset --hard commit-hash
```

Replace `commit-hash` with the commit you want to return to.

---

## ⚠️ Important Warning

`git reset --hard` can permanently delete uncommitted changes.

Before using it, make sure you do not need the changes.

You can check your current state with:

```bash
git status
```

---

## 💡 When to Use It

Use `git reset --hard` when:

- You are sure you want to discard local changes
- You want your working directory to exactly match a specific commit
- You need to remove unwanted local commits and their changes

---

## 🚨 Be Careful with Pushed Commits

Avoid using hard reset on commits that have already been pushed to a shared repository unless you fully understand the consequences.

Changing shared history can cause problems for other developers.

---

## 📝 Summary

```bash
git reset --hard HEAD~1
```

Moves the branch backward and discards changes from the staging area and working directory.

Use this command carefully.

---

# 🇵🇸 العربية

# 🔴 Git Reset Hard

## العربية

يقوم `git reset --hard` بنقل الفرع الحالي إلى Commit آخر وتحديث منطقة Staging ومجلد العمل ليصبحا مطابقين لذلك الـ Commit.

وهذا يعني أن التغييرات الموجودة في Staging ومجلد العمل قد يتم حذفها بشكل نهائي.

---

## 🔹 الاستخدام الأساسي

للعودة إلى Commit واحد سابق:

```bash
git reset --hard HEAD~1
```

ينتقل الفرع الحالي إلى Commit سابق ويتم حذف التغييرات التي تمت بعد ذلك الـ Commit.

---

## 🔹 Reset إلى Commit محدد

يمكنك تنفيذ Reset إلى Commit محدد:

```bash
git reset --hard commit-hash
```

استبدل `commit-hash` بمعرّف الـ Commit الذي تريد العودة إليه.

---

## ⚠️ تحذير مهم

يمكن لـ `git reset --hard` حذف التغييرات غير المحفوظة بشكل نهائي.

قبل استخدامه، تأكد من أنك لا تحتاج إلى هذه التغييرات.

يمكنك التحقق من الحالة الحالية باستخدام:

```bash
git status
```

---

## 💡 متى نستخدمه؟

استخدم `git reset --hard` عندما:

- تكون متأكدًا أنك تريد حذف التغييرات المحلية
- تريد أن يصبح مجلد العمل مطابقًا تمامًا لـ Commit محدد
- تحتاج إلى إزالة Commits محلية غير مرغوبة مع التغييرات الناتجة عنها

---

## 🚨 كن حذرًا مع Commits التي تم رفعها

تجنب استخدام Hard Reset على Commits تم رفعها مسبقًا إلى مستودع مشترك إلا إذا كنت تفهم النتائج بشكل كامل.

تغيير سجل مشترك يمكن أن يسبب مشاكل للمطورين الآخرين.

---

## 📝 الخلاصة

```bash
git reset --hard HEAD~1
```

ينقل الفرع إلى الوراء ويحذف التغييرات من Staging ومجلد العمل.

استخدم هذا الأمر بحذر.
