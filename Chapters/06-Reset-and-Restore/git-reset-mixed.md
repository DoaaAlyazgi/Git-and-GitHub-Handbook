# 🟡 Git Reset Mixed

## 🌐 English

`git reset --mixed` moves the current branch to another commit while keeping the changes in the working directory.

However, the changes are removed from the staging area.

Mixed reset is the default mode of `git reset`.

---

## 🔹 Basic Usage

```bash
git reset --mixed HEAD~1
```

The branch moves back one commit.

The changes remain in the working directory but are unstaged.

---

## 🔹 Check the Changes

After the reset:

```bash
git status
```

You will see the changes as modified but not staged.

---

## 🔹 Stage the Changes Again

If you want to stage the changes again:

```bash
git add .
```

Then create a new commit:

```bash
git commit -m "Updated changes"
```

---

## 💡 When to Use It

Use `git reset --mixed` when:

- You want to undo a commit
- You want to keep the changes
- You want to review the changes before staging them again
- You want to modify which files will be included in the next commit

---

## 📝 Summary

```bash
git reset --mixed HEAD~1
```

Moves the branch backward while keeping changes in the working directory and unstaging them.

---

# 🇵🇸 العربية

# 🟡 Git Reset Mixed

## العربية

يقوم `git reset --mixed` بنقل الفرع الحالي إلى Commit آخر مع إبقاء التغييرات في مجلد العمل.

لكن يتم إزالة هذه التغييرات من منطقة Staging.

ويُعد Mixed هو الوضع الافتراضي عند استخدام `git reset`.

---

## 🔹 الاستخدام الأساسي

```bash
git reset --mixed HEAD~1
```

يعود الفرع إلى Commit سابق.

وتبقى التغييرات في مجلد العمل ولكن يتم إلغاء وضع Staging عنها.

---

## 🔹 التحقق من التغييرات

بعد تنفيذ Reset:

```bash
git status
```

ستظهر التغييرات على أنها Modified ولكنها غير موجودة في Staging.

---

## 🔹 إضافة التغييرات إلى Staging مرة أخرى

إذا أردت إضافة التغييرات مرة أخرى:

```bash
git add .
```

ثم أنشئ Commit جديدًا:

```bash
git commit -m "Updated changes"
```

---

## 💡 متى نستخدمه؟

استخدم `git reset --mixed` عندما:

- تريد التراجع عن Commit
- تريد الاحتفاظ بالتغييرات
- تريد مراجعة التغييرات قبل إضافتها إلى Staging
- تريد تحديد الملفات التي سيتم تضمينها في الـ Commit القادم

---

## 📝 الخلاصة

```bash
git reset --mixed HEAD~1
```

ينقل الفرع إلى الوراء مع إبقاء التغييرات في مجلد العمل وإزالتها من Staging.
