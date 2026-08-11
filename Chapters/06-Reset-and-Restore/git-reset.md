# ↩️ Git Reset

## 🌐 English

`git reset` is used to move the current branch to another commit.

It can also modify the staging area and working directory depending on the reset mode.

---

## 🔹 Basic Usage

To move the current branch back one commit:

```bash
git reset HEAD~1
```

By default, Git uses mixed reset.

---

## 🔹 Reset to a Specific Commit

You can reset to a specific commit:

```bash
git reset commit-hash
```

Replace `commit-hash` with the ID of the commit you want to reset to.

---

## 🔹 Reset Modes

Git provides three common reset modes:

```bash
git reset --soft
git reset --mixed
git reset --hard
```

Each mode handles staged and working-directory changes differently.

---

## 🔹 View Commit History

Before resetting, it is useful to view your commit history:

```bash
git log --oneline
```

Example:

```text
a1b2c3d Update README
e4f5g6h Add login page
h7i8j9k Initial commit
```

You can then choose the commit you want to reset to.

---

## ⚠️ Important Warning

Reset changes the current branch's history.

Be especially careful when resetting commits that have already been pushed to a shared remote repository.

---

## 📝 Summary

```bash
git reset HEAD~1
git reset commit-hash
git reset --soft HEAD~1
git reset --mixed HEAD~1
git reset --hard HEAD~1
```

`git reset` is mainly used to move the current branch and undo commits.

---

# 🇵🇸 العربية

# ↩️ Git Reset

## العربية

يُستخدم `git reset` لنقل الفرع الحالي إلى Commit آخر.

ويمكنه أيضًا تعديل منطقة Staging ومجلد العمل حسب وضع Reset المستخدم.

---

## 🔹 الاستخدام الأساسي

للعودة بالفرع الحالي إلى Commit واحد سابق:

```bash
git reset HEAD~1
```

بشكل افتراضي، يستخدم Git وضع Mixed.

---

## 🔹 Reset إلى Commit محدد

يمكنك تنفيذ Reset إلى Commit محدد:

```bash
git reset commit-hash
```

استبدل `commit-hash` بمعرّف الـ Commit الذي تريد العودة إليه.

---

## 🔹 أوضاع Reset

يوفر Git ثلاثة أوضاع شائعة:

```bash
git reset --soft
git reset --mixed
git reset --hard
```

ويتعامل كل وضع منها بشكل مختلف مع التغييرات الموجودة في Staging ومجلد العمل.

---

## 🔹 عرض سجل Commits

قبل تنفيذ Reset، من المفيد عرض سجل الـ Commits:

```bash
git log --oneline
```

مثال:

```text
a1b2c3d Update README
e4f5g6h Add login page
h7i8j9k Initial commit
```

بعد ذلك يمكنك اختيار الـ Commit الذي تريد العودة إليه.

---

## ⚠️ تحذير مهم

يقوم Reset بتغيير سجل الفرع الحالي.

كن حذرًا بشكل خاص عند تنفيذ Reset على Commits تم رفعها مسبقًا إلى مستودع Remote مشترك.

---

## 📝 الخلاصة

```bash
git reset HEAD~1
git reset commit-hash
git reset --soft HEAD~1
git reset --mixed HEAD~1
git reset --hard HEAD~1
```

يُستخدم `git reset` بشكل أساسي لنقل الفرع الحالي والتراجع عن الـ Commits.
