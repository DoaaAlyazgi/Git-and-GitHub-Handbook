# 🍒 Chapter 07: Git Cherry Pick

Welcome to Chapter 07 of the Git & GitHub Handbook.

In this chapter, we will learn how to apply specific commits from one branch to another using Git Cherry Pick.

---

## 🌐 English

### 🎯 What You'll Learn

In this chapter, you will learn how to:

- Understand what Git Cherry Pick is
- Apply a specific commit to another branch
- Cherry-pick multiple commits
- Handle cherry-pick conflicts
- Abort a cherry-pick operation
- Continue a cherry-pick operation after resolving conflicts
- Understand when Cherry Pick is useful

---

## 📚 Commands Covered

### 1. `git cherry-pick`

Apply the changes introduced by an existing commit to the current branch.

📄 Documentation:

- `git-cherry-pick.md`

---

### 2. `git cherry-pick <commit>`

Apply a specific commit to the current branch.

📄 Documentation:

- `git-cherry-pick-commit.md`

---

### 3. Cherry-Pick Multiple Commits

Apply multiple commits to the current branch.

📄 Documentation:

- `git-cherry-pick-multiple-commits.md`

---

### 4. `git cherry-pick --abort`

Cancel an active cherry-pick operation.

📄 Documentation:

- `git-cherry-pick-abort.md`

---

### 5. Handling Cherry-Pick Conflicts

Resolve conflicts that occur during a cherry-pick operation.

📄 Documentation:

- `git-cherry-pick-conflicts.md`

---

## 🔄 Basic Cherry-Pick Workflow

A common Cherry Pick workflow looks like this:

```bash
git switch main
git cherry-pick commit-hash
```

Git applies the changes from the selected commit to the current branch.

---

## 💡 Why Use Git Cherry Pick?

Cherry Pick is useful when:

- You need one specific change from another branch
- You do not want to merge the entire branch
- A bug fix exists on another branch
- You need to apply a small change to another branch
- You want to selectively move commits between branches

---

## ⚠️ Important Note

Cherry Pick creates a new commit on the current branch.

The new commit contains the same changes as the original commit, but it has a different commit ID.

---

## 📝 Summary

The main concepts covered in this chapter are:

```bash
git cherry-pick <commit>
git cherry-pick <commit1> <commit2>
git cherry-pick --abort
git cherry-pick --continue
```

Git Cherry Pick allows you to selectively apply specific commits from one branch to another.

---

# 🇵🇸 العربية

# 🍒 الفصل 07: Git Cherry Pick

مرحبًا بك في الفصل السابع من دليل Git و GitHub.

في هذا الفصل، سنتعلم كيفية تطبيق Commits محددة من فرع إلى فرع آخر باستخدام Git Cherry Pick.

---

## 🎯 ماذا ستتعلم؟

في هذا الفصل، ستتعلم كيفية:

- فهم مفهوم Git Cherry Pick
- تطبيق Commit محدد على فرع آخر
- تطبيق عدة Commits
- التعامل مع التعارضات أثناء Cherry Pick
- إلغاء عملية Cherry Pick
- متابعة عملية Cherry Pick بعد حل التعارضات
- فهم الحالات التي يكون فيها Cherry Pick مفيدًا

---

## 📚 الأوامر التي سنتعلمها

### 1. `git cherry-pick`

تطبيق التغييرات التي تم إدخالها بواسطة Commit موجود على الفرع الحالي.

📄 التوثيق:

- `git-cherry-pick.md`

---

### 2. `git cherry-pick <commit>`

تطبيق Commit محدد على الفرع الحالي.

📄 التوثيق:

- `git-cherry-pick-commit.md`

---

### 3. تطبيق عدة Commits

تطبيق عدة Commits على الفرع الحالي.

📄 التوثيق:

- `git-cherry-pick-multiple-commits.md`

---

### 4. `git cherry-pick --abort`

إلغاء عملية Cherry Pick قيد التنفيذ.

📄 التوثيق:

- `git-cherry-pick-abort.md`

---

### 5. التعامل مع تعارضات Cherry Pick

حل التعارضات التي قد تحدث أثناء عملية Cherry Pick.

📄 التوثيق:

- `git-cherry-pick-conflicts.md`

---

## 🔄 سير العمل الأساسي لـ Cherry Pick

يمكن أن يكون سير العمل المعتاد بالشكل التالي:

```bash
git switch main
git cherry-pick commit-hash
```

يقوم Git بتطبيق التغييرات الموجودة في الـ Commit المحدد على الفرع الحالي.

---

## 💡 لماذا نستخدم Git Cherry Pick؟

يكون Cherry Pick مفيدًا عندما:

- تحتاج إلى تغيير محدد من فرع آخر
- لا تريد دمج الفرع بالكامل
- يوجد إصلاح لمشكلة في فرع آخر
- تحتاج إلى تطبيق تغيير صغير على فرع آخر
- تريد نقل Commits محددة بين الفروع

---

## ⚠️ ملاحظة مهمة

يقوم Cherry Pick بإنشاء Commit جديد على الفرع الحالي.

يحتوي الـ Commit الجديد على نفس التغييرات الموجودة في الـ Commit الأصلي، ولكنه يحصل على Commit ID مختلف.

---

## 📝 الخلاصة

المفاهيم الأساسية التي سنتعلمها في هذا الفصل هي:

```bash
git cherry-pick <commit>
git cherry-pick <commit1> <commit2>
git cherry-pick --abort
git cherry-pick --continue
```

يسمح لك Git Cherry Pick بتطبيق Commits محددة بشكل انتقائي من فرع إلى فرع آخر.
