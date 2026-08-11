# 🔀 Chapter 08: Git Rebase

Welcome to Chapter 08 of the Git & GitHub Handbook.

In this chapter, we will learn how to use Git Rebase to reorganize commit history and keep branches up to date.

---

## 🌐 English

### 🎯 What You'll Learn

In this chapter, you will learn how to:

- Understand what Git Rebase is
- Rebase a branch onto another branch
- Keep a clean and linear commit history
- Use interactive rebase
- Reorder and edit commits
- Squash multiple commits
- Continue a rebase operation
- Abort a rebase operation
- Resolve rebase conflicts
- Understand when to use Rebase and when to use Merge

---

## 📚 Commands Covered

### 1. `git rebase`

Reapply commits from one branch on top of another branch.

📄 Documentation:

- `git-rebase.md`

---

### 2. `git rebase -i`

Start an interactive rebase to edit, reorder, combine, or remove commits.

📄 Documentation:

- `git-rebase-interactive.md`

---

### 3. `git rebase --onto`

Rebase a specific range of commits onto another base.

📄 Documentation:

- `git-rebase-onto.md`

---

### 4. `git rebase --continue`

Continue a rebase operation after resolving conflicts or making changes.

📄 Documentation:

- `git-rebase-continue.md`

---

### 5. `git rebase --abort`

Cancel an active rebase operation.

📄 Documentation:

- `git-rebase-abort.md`

---

### 6. Handling Rebase Conflicts

Resolve conflicts that occur during a rebase operation.

📄 Documentation:

- `git-rebase-conflicts.md`

---

## 🔄 Basic Rebase Workflow

A common rebase workflow looks like this:

```bash
git switch feature-branch
git rebase main
```

Git takes the commits from `feature-branch` and reapplies them on top of the latest `main`.

---

## 💡 Why Use Git Rebase?

Rebase is useful when:

- You want a cleaner commit history
- You want to update your branch with the latest changes
- You want to avoid unnecessary merge commits
- You want to organize commits before sharing your work
- You want to keep a more linear project history

---

## 🔄 Rebase vs Merge

Both Rebase and Merge can be used to integrate changes from one branch into another.

### Merge

Merge creates a new merge commit when the branches have diverged.

### Rebase

Rebase moves your commits and reapplies them on top of another branch.

This can create a cleaner and more linear history.

---

## ⚠️ Important Warning

Rebase rewrites commit history.

Avoid rebasing commits that have already been pushed to a shared branch unless you understand the consequences.

Rewriting shared history can cause problems for other developers.

---

## 📝 Summary

The main commands covered in this chapter are:

```bash
git rebase main
git rebase -i HEAD~3
git rebase --onto main old-base feature-branch
git rebase --continue
git rebase --abort
```

Git Rebase is a powerful tool for organizing commit history and keeping branches synchronized with the latest changes.

---

# 🇵🇸 العربية

# 🔀 الفصل 08: Git Rebase

مرحبًا بك في الفصل الثامن من دليل Git و GitHub.

في هذا الفصل، سنتعلم كيفية استخدام Git Rebase لإعادة تنظيم سجل الـ Commits وإبقاء الفروع محدثة.

---

## 🎯 ماذا ستتعلم؟

في هذا الفصل، ستتعلم كيفية:

- فهم مفهوم Git Rebase
- تنفيذ Rebase لفرع على فرع آخر
- الحفاظ على سجل Commits نظيف وخطي
- استخدام Interactive Rebase
- إعادة ترتيب وتعديل الـ Commits
- دمج عدة Commits في Commit واحد
- متابعة عملية Rebase
- إلغاء عملية Rebase
- حل تعارضات Rebase
- فهم الفرق بين Rebase و Merge ومتى نستخدم كل منهما

---

## 📚 الأوامر التي سنتعلمها

### 1. `git rebase`

إعادة تطبيق Commits الخاصة بفرع فوق فرع آخر.

📄 التوثيق:

- `git-rebase.md`

---

### 2. `git rebase -i`

بدء Interactive Rebase لتعديل أو إعادة ترتيب أو دمج أو حذف Commits.

📄 التوثيق:

- `git-rebase-interactive.md`

---

### 3. `git rebase --onto`

إعادة تطبيق مجموعة محددة من Commits فوق قاعدة أخرى.

📄 التوثيق:

- `git-rebase-onto.md`

---

### 4. `git rebase --continue`

متابعة عملية Rebase بعد حل التعارضات أو إجراء التعديلات المطلوبة.

📄 التوثيق:

- `git-rebase-continue.md`

---

### 5. `git rebase --abort`

إلغاء عملية Rebase قيد التنفيذ.

📄 التوثيق:

- `git-rebase-abort.md`

---

### 6. التعامل مع تعارضات Rebase

حل التعارضات التي تحدث أثناء عملية Rebase.

📄 التوثيق:

- `git-rebase-conflicts.md`

---

## 🔄 سير العمل الأساسي لـ Rebase

يمكن أن يكون سير العمل المعتاد بالشكل التالي:

```bash
git switch feature-branch
git rebase main
```

يقوم Git بأخذ الـ Commits الموجودة في `feature-branch` وإعادة تطبيقها فوق أحدث نسخة من `main`.

---

## 💡 لماذا نستخدم Git Rebase؟

يكون Rebase مفيدًا عندما:

- تريد سجل Commits أكثر نظافة
- تريد تحديث فرعك بأحدث التغييرات
- تريد تجنب Commits الدمج غير الضرورية
- تريد تنظيم Commits قبل مشاركة عملك
- تريد الحفاظ على سجل مشروع خطي ومنظم

---

## 🔄 الفرق بين Rebase و Merge

يمكن استخدام كل من Rebase و Merge لدمج التغييرات من فرع إلى فرع آخر.

### Merge

يقوم Merge بإنشاء Merge Commit جديد عندما تكون الفروع قد تفرعت عن بعضها.

### Rebase

يقوم Rebase بنقل Commits الخاصة بك وإعادة تطبيقها فوق فرع آخر.

وهذا يمكن أن ينتج سجلًا أكثر نظافة وخطية.

---

## ⚠️ تحذير مهم

يقوم Rebase بإعادة كتابة سجل الـ Commits.

تجنب تنفيذ Rebase على Commits تم رفعها مسبقًا إلى فرع مشترك إلا إذا كنت تفهم النتائج.

إعادة كتابة سجل مشترك قد تسبب مشاكل للمطورين الآخرين.

---

## 📝 الخلاصة

الأوامر الأساسية التي سنتعلمها في هذا الفصل هي:

```bash
git rebase main
git rebase -i HEAD~3
git rebase --onto main old-base feature-branch
git rebase --continue
git rebase --abort
```

يُعد Git Rebase أداة قوية لتنظيم سجل الـ Commits وإبقاء الفروع متزامنة مع أحدث التغييرات.
