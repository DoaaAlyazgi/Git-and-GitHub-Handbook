# ▶️ Git Rebase Continue

## 🌐 English

`git rebase --continue` is used to continue a rebase operation after resolving conflicts or making the required changes.

---

## 🔹 Basic Usage

After resolving a conflict:

```bash
git add .
```

Then continue the rebase:

```bash
git rebase --continue
```

---

## 🔹 Example Workflow

Start a rebase:

```bash
git rebase main
```

If a conflict occurs:

```bash
git status
```

Resolve the conflicted files.

Then stage them:

```bash
git add filename.txt
```

Continue:

```bash
git rebase --continue
```

---

## 🔹 Multiple Conflicts

A rebase can contain more than one conflict.

You may need to repeat:

```bash
git status
git add .
git rebase --continue
```

until the rebase is complete.

---

## 🔹 Abort Instead

If you decide not to continue:

```bash
git rebase --abort
```

---

## 📝 Summary

```bash
git rebase --continue
```

Use this command after resolving conflicts to continue the rebase operation.

---

# 🇵🇸 العربية

# ▶️ Git Rebase Continue

## العربية

يُستخدم `git rebase --continue` لمتابعة عملية Rebase بعد حل التعارضات أو إجراء التغييرات المطلوبة.

---

## 🔹 الاستخدام الأساسي

بعد حل التعارض:

```bash
git add .
```

ثم تابع عملية Rebase:

```bash
git rebase --continue
```

---

## 🔹 مثال على سير العمل

ابدأ عملية Rebase:

```bash
git rebase main
```

إذا حدث تعارض:

```bash
git status
```

قم بحل الملفات التي تحتوي على تعارضات.

ثم أضفها إلى Staging:

```bash
git add filename.txt
```

تابع العملية:

```bash
git rebase --continue
```

---

## 🔹 حدوث عدة تعارضات

قد تحتوي عملية Rebase على أكثر من تعارض.

قد تحتاج إلى تكرار:

```bash
git status
git add .
git rebase --continue
```

حتى تكتمل عملية Rebase.

---

## 🔹 الإلغاء بدلًا من المتابعة

إذا قررت عدم المتابعة:

```bash
git rebase --abort
```

---

## 📝 الخلاصة

```bash
git rebase --continue
```

استخدم هذا الأمر بعد حل التعارضات لمتابعة عملية Rebase.
