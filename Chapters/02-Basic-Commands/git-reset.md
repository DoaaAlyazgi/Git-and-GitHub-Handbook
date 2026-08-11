# ↩️ Git Reset

## 🌐 English

`git reset` is used to move the current branch to another commit and change the state of the staging area or working directory.

It is commonly used to undo commits or unstage changes.

---

## 🔹 Step 1: Unstage a File

To remove a file from the staging area without deleting its changes, use:

    git reset filename

Example:

    git reset index.html

The file will be removed from the staging area, but your changes will remain in the working directory.

---

## 🔹 Step 2: Unstage All Files

To unstage all staged files, use:

    git reset

This removes the files from the staging area while keeping your actual changes.

---

## 🔹 Step 3: Reset to the Previous Commit

To move the current branch back by one commit while keeping your changes staged, use:

    git reset --soft HEAD~1

This removes the latest commit but keeps its changes in the staging area.

---

## 🔹 Step 4: Mixed Reset

The default reset mode is `--mixed`.

You can use:

    git reset --mixed HEAD~1

This removes the latest commit and unstages its changes, but keeps the changes in your working directory.

---

## 🔹 Step 5: Hard Reset

To completely remove the latest commit and its changes, use:

    git reset --hard HEAD~1

⚠️ Be careful with `--hard`.

It can permanently delete uncommitted changes.

---

## 💡 Understanding the Three Main Modes

| Command | Commit | Staging Area | Working Directory |
|---|---|---|---|
| `git reset --soft HEAD~1` | Reset | Keep changes staged | Keep changes |
| `git reset --mixed HEAD~1` | Reset | Unstage changes | Keep changes |
| `git reset --hard HEAD~1` | Reset | Remove changes | Remove changes |

---

## 🧪 Example Workflow

To undo the most recent commit while keeping your changes:

    git reset --soft HEAD~1

To undo the most recent commit and unstage the changes:

    git reset --mixed HEAD~1

To completely remove the commit and its changes:

    git reset --hard HEAD~1

---

## ⚠️ Important Note

`git reset --hard` should be used carefully.

Before using it, make sure you do not have important uncommitted changes that you want to keep.

When working with shared repositories, be especially careful when resetting commits that may already have been pushed to a remote repository.

---

# 🇵🇸 العربية

## ما هو `git reset`؟

يُستخدم الأمر `git reset` لنقل الفرع الحالي إلى Commit آخر، ويمكنه أيضًا تغيير حالة منطقة التجهيز (Staging Area) أو مجلد العمل.

يُستخدم بشكل شائع للتراجع عن Commits أو إزالة الملفات من منطقة التجهيز.

---

## 🔹 الخطوة 1: إزالة ملف من منطقة التجهيز

لإزالة ملف من منطقة التجهيز دون حذف التغييرات الموجودة عليه، استخدم:

    git reset filename

مثال:

    git reset index.html

سيتم إزالة الملف من منطقة التجهيز، ولكن ستبقى التغييرات الموجودة عليه داخل مجلد العمل.

---

## 🔹 الخطوة 2: إزالة جميع الملفات من منطقة التجهيز

لإزالة جميع الملفات التي تمت إضافتها إلى منطقة التجهيز، استخدم:

    git reset

سيؤدي هذا إلى إزالة الملفات من منطقة التجهيز مع الاحتفاظ بالتغييرات الفعلية الموجودة عليها.

---

## 🔹 الخطوة 3: الرجوع إلى Commit السابق

للرجوع بالفرع الحالي Commit واحد إلى الخلف مع الاحتفاظ بالتغييرات داخل منطقة التجهيز، استخدم:

    git reset --soft HEAD~1

يؤدي هذا إلى إزالة آخر Commit، مع إبقاء التغييرات الموجودة فيه جاهزة داخل منطقة التجهيز.

---

## 🔹 الخطوة 4: استخدام Mixed Reset

الوضع الافتراضي للأمر `git reset` هو `--mixed`.

يمكنك استخدام:

    git reset --mixed HEAD~1

يؤدي هذا إلى إزالة آخر Commit وإزالة التغييرات من منطقة التجهيز، مع الاحتفاظ بها داخل مجلد العمل.

---

## 🔹 الخطوة 5: استخدام Hard Reset

لإزالة آخر Commit وتغييراته بشكل كامل، استخدم:

    git reset --hard HEAD~1

⚠️ انتبه عند استخدام `--hard`.

قد يؤدي هذا الأمر إلى حذف التغييرات غير المحفوظة نهائيًا.

---

## 💡 فهم الأنواع الثلاثة الأساسية

| الأمر | الـ Commit | منطقة التجهيز | مجلد العمل |
|---|---|---|---|
| `git reset --soft HEAD~1` | يرجع للخلف | يحتفظ بالتغييرات مجهزة | يحتفظ بالتغييرات |
| `git reset --mixed HEAD~1` | يرجع للخلف | يزيل التغييرات من التجهيز | يحتفظ بالتغييرات |
| `git reset --hard HEAD~1` | يرجع للخلف | يزيل التغييرات | يزيل التغييرات |

---

## 🧪 مثال على سير العمل

للتراجع عن آخر Commit مع الاحتفاظ بالتغييرات:

    git reset --soft HEAD~1

للتراجع عن آخر Commit وإزالة التغييرات من منطقة التجهيز:

    git reset --mixed HEAD~1

لإزالة الـ Commit وتغييراته بشكل كامل:

    git reset --hard HEAD~1

---

## ⚠️ ملاحظة مهمة

يجب استخدام `git reset --hard` بحذر شديد.

قبل استخدامه، تأكد من عدم وجود تغييرات مهمة غير محفوظة تريد الاحتفاظ بها.

وعند العمل على مستودعات مشتركة، يجب الانتباه بشكل خاص عند إعادة ضبط Commits تم رفعها مسبقًا إلى المستودع البعيد.
