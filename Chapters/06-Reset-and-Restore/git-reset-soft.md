# 🟢 Git Reset Soft

## 🌐 English

`git reset --soft` moves the current branch to another commit while keeping the changes from the removed commits staged.

This is useful when you want to undo one or more commits but keep all their changes ready to commit again.

---

## 🔹 Basic Usage

To move back one commit:

```bash
git reset --soft HEAD~1
```

The commit is removed from the current branch history, but its changes remain staged.

---

## 🔹 Example

Suppose your history looks like this:

```text
A -- B -- C
```

If you run:

```bash
git reset --soft HEAD~1
```

The branch moves from `C` back to `B`.

The changes introduced by `C` remain staged.

---

## 🔹 Create a New Commit

After the soft reset, you can review the changes:

```bash
git status
```

Then create a new commit:

```bash
git commit -m "Updated commit"
```

---

## 💡 When to Use It

Use `git reset --soft` when:

- You want to undo a commit
- You want to modify the commit message
- You want to combine commits
- You want to keep the changes staged

---

## 📝 Summary

```bash
git reset --soft HEAD~1
```

Moves the branch backward while keeping the changes staged.

---

# 🇵🇸 العربية

# 🟢 Git Reset Soft

## العربية

يقوم `git reset --soft` بنقل الفرع الحالي إلى Commit آخر مع إبقاء التغييرات الناتجة عن الـ Commits التي تمت إزالتها في منطقة Staging.

يكون هذا مفيدًا عندما تريد التراجع عن Commit أو أكثر مع الاحتفاظ بجميع التغييرات وتجهيزها لإنشاء Commit جديد.

---

## 🔹 الاستخدام الأساسي

للعودة إلى Commit واحد سابق:

```bash
git reset --soft HEAD~1
```

يتم إزالة الـ Commit من سجل الفرع الحالي، ولكن تبقى التغييرات في منطقة Staging.

---

## 🔹 مثال

لنفترض أن سجل Commits لديك بالشكل التالي:

```text
A -- B -- C
```

إذا نفذت:

```bash
git reset --soft HEAD~1
```

سينتقل الفرع من `C` إلى `B`.

وتبقى التغييرات التي أضافها `C` في منطقة Staging.

---

## 🔹 إنشاء Commit جديد

بعد تنفيذ Soft Reset، يمكنك مراجعة التغييرات:

```bash
git status
```

ثم إنشاء Commit جديد:

```bash
git commit -m "Updated commit"
```

---

## 💡 متى نستخدمه؟

استخدم `git reset --soft` عندما:

- تريد التراجع عن Commit
- تريد تعديل رسالة Commit
- تريد دمج عدة Commits
- تريد إبقاء التغييرات في Staging

---

## 📝 الخلاصة

```bash
git reset --soft HEAD~1
```

ينقل الفرع إلى الوراء مع إبقاء التغييرات في منطقة Staging.
