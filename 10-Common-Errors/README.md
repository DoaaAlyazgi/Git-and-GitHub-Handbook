# ⚠️ Chapter 10: Common Git Errors

Welcome to Chapter 10 of the Git & GitHub Handbook.

In this chapter, we will learn about common Git errors, why they happen, and how to solve them.

---

## 🌐 English

### 🎯 What You'll Learn

In this chapter, you will learn how to:

- Understand common Git errors
- Identify the cause of Git errors
- Fix repository-related errors
- Resolve merge conflicts
- Fix rejected pushes
- Troubleshoot branch-related errors
- Understand detached HEAD state
- Fix Git authentication problems

---

## 📚 Errors Covered

### 1. Not a Git Repository

Learn how to solve:

```text
fatal: not a git repository
```

📄 Documentation:

- `git-not-a-repository.md`

---

### 2. Merge Conflicts

Learn how to identify and resolve conflicts during a merge.

📄 Documentation:

- `git-merge-conflict.md`

---

### 3. Push Rejected

Learn why Git may reject a push and how to resolve it.

📄 Documentation:

- `git-push-rejected.md`

---

### 4. Branch Errors

Learn how to troubleshoot common branch-related problems.

📄 Documentation:

- `git-branch-errors.md`

---

### 5. Detached HEAD

Learn what a detached HEAD state means and how to return to a normal branch.

📄 Documentation:

- `git-detached-head.md`

---

### 6. Authentication Errors

Learn how to troubleshoot authentication problems when connecting to remote repositories.

📄 Documentation:

- `git-authentication-errors.md`

---

## 🔄 General Troubleshooting Workflow

When Git shows an error, start by checking the repository status:

```bash
git status
```

Then inspect your branches:

```bash
git branch
```

Check your remotes:

```bash
git remote -v
```

If necessary, inspect the commit history:

```bash
git log --oneline --graph
```

---

## 💡 Important Tip

Do not ignore Git error messages.

Git usually provides useful information about what went wrong.

Read the error carefully and identify:

1. What operation failed
2. Which file or branch is involved
3. What Git expects you to do next

---

## 📝 Summary

Common Git problems include:

```text
Not a Git Repository
Merge Conflicts
Push Rejected
Branch Errors
Detached HEAD
Authentication Errors
```

Learning how to understand and solve Git errors is an important part of becoming comfortable with Git.

---

# 🇵🇸 العربية

# ⚠️ الفصل 10: أخطاء Git الشائعة

مرحبًا بك في الفصل العاشر من دليل Git و GitHub.

في هذا الفصل، سنتعلم عن أخطاء Git الشائعة، وأسباب حدوثها، وكيفية حلها.

---

## 🎯 ماذا ستتعلم؟

في هذا الفصل، ستتعلم كيفية:

- فهم أخطاء Git الشائعة
- تحديد سبب الخطأ
- حل الأخطاء المتعلقة بالمستودع
- حل تعارضات الدمج
- حل مشكلة رفض Push
- التعامل مع أخطاء الفروع
- فهم حالة Detached HEAD
- حل مشاكل المصادقة في Git

---

## 📚 الأخطاء التي سنتعلمها

### 1. المستودع ليس مستودع Git

سنتعلم كيفية حل الخطأ:

```text
fatal: not a git repository
```

📄 التوثيق:

- `git-not-a-repository.md`

---

### 2. تعارضات Merge

سنتعلم كيفية اكتشاف وحل التعارضات أثناء عملية Merge.

📄 التوثيق:

- `git-merge-conflict.md`

---

### 3. رفض Push

سنتعلم لماذا قد يرفض Git عملية Push وكيفية حل المشكلة.

📄 التوثيق:

- `git-push-rejected.md`

---

### 4. أخطاء الفروع

سنتعلم كيفية التعامل مع المشاكل الشائعة المتعلقة بالفروع.

📄 التوثيق:

- `git-branch-errors.md`

---

### 5. Detached HEAD

سنتعلم معنى حالة Detached HEAD وكيفية العودة إلى فرع طبيعي.

📄 التوثيق:

- `git-detached-head.md`

---

### 6. أخطاء المصادقة

سنتعلم كيفية التعامل مع مشاكل المصادقة عند الاتصال بالمستودعات البعيدة.

📄 التوثيق:

- `git-authentication-errors.md`

---

## 🔄 طريقة عامة لاستكشاف الأخطاء

عندما يعرض Git خطأ، ابدأ بالتحقق من حالة المستودع:

```bash
git status
```

ثم تحقق من الفروع:

```bash
git branch
```

وتحقق من الـ Remotes:

```bash
git remote -v
```

وإذا احتجت، راجع سجل الـ Commits:

```bash
git log --oneline --graph
```

---

## 💡 نصيحة مهمة

لا تتجاهل رسائل الخطأ التي يعرضها Git.

عادةً يقدم Git معلومات مفيدة حول المشكلة.

اقرأ رسالة الخطأ بعناية وحدد:

1. ما العملية التي فشلت
2. ما الملف أو الفرع المتعلق بالمشكلة
3. ماذا يتوقع Git منك أن تفعل بعد ذلك

---

## 📝 الخلاصة

من أخطاء Git الشائعة:

```text
Not a Git Repository
Merge Conflicts
Push Rejected
Branch Errors
Detached HEAD
Authentication Errors
```

تعلم فهم أخطاء Git وحلها جزء مهم من إتقان استخدام Git والتعامل معه بثقة.
