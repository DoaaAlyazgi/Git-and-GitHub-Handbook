# 🌿 Chapter 03: Git Branching

Welcome to Chapter 03 of the Git & GitHub Handbook.

In this chapter, we will learn how Git branches work and how to create, switch, manage, and merge branches.

---

## 🌐 English

### 🎯 What You'll Learn

In this chapter, you will learn how to:

- Understand what a Git branch is
- Create new branches
- View existing branches
- Switch between branches
- Create and switch to a new branch
- Rename branches
- Delete branches
- Merge branches
- Understand basic branch workflows

---

## 📚 Commands Covered

### 1. `git branch`

Used to create, view, rename, and delete branches.

📄 Documentation:

- `git-branch.md`

---

### 2. `git switch`

Used to switch between branches and create new branches.

📄 Documentation:

- `git-switch.md`

---

### 3. `git checkout`

Used to switch branches and restore files.

📄 Documentation:

- `git-checkout.md`

---

### 4. `git merge`

Used to combine changes from one branch into another.

📄 Documentation:

- `git-merge.md`

---

## 🌳 What Is a Branch?

A branch is an independent line of development in a Git repository.

Branches allow you to work on new features, fixes, or experiments without directly changing the main branch.

A common default branch is:

```bash
main
```

You can create another branch for a new feature:

```bash
git branch feature-login
```

---

## 🔄 Basic Branch Workflow

A common branching workflow looks like this:

```bash
git branch feature-login
git switch feature-login
git add .
git commit -m "Add login feature"
git switch main
git merge feature-login
```

The process is:

1. Create a new branch
2. Switch to the new branch
3. Make changes
4. Commit the changes
5. Switch back to the main branch
6. Merge the feature branch

---

## 💡 Why Use Branches?

Branches are useful because they allow you to:

- Work on features independently
- Test new ideas safely
- Fix bugs without affecting the main branch
- Work with other developers
- Keep the main branch stable

---

## 📝 Summary

Git branches provide a safe way to work on different versions or features of a project.

The main commands covered in this chapter are:

```bash
git branch
git switch
git checkout
git merge
```

Understanding branches is an important step toward working effectively with Git and GitHub.

---

# 🇵🇸 العربية

# 🌿 الفصل 03: الفروع في Git

مرحبًا بك في الفصل الثالث من دليل Git و GitHub.

في هذا الفصل، سنتعلم كيفية عمل الفروع في Git، وكيفية إنشاء الفروع والتنقل بينها وإدارتها ودمجها.

---

## 🎯 ماذا ستتعلم؟

في هذا الفصل، ستتعلم كيفية:

- فهم ما هو Branch في Git
- إنشاء فروع جديدة
- عرض الفروع الموجودة
- التنقل بين الفروع
- إنشاء فرع جديد والانتقال إليه
- إعادة تسمية الفروع
- حذف الفروع
- دمج الفروع
- فهم سير العمل الأساسي للفروع

---

## 📚 الأوامر التي سنتعلمها

### 1. `git branch`

يُستخدم الأمر لإنشاء الفروع وعرضها وإعادة تسميتها وحذفها.

📄 التوثيق:

- `git-branch.md`

---

### 2. `git switch`

يُستخدم الأمر للتنقل بين الفروع وإنشاء فروع جديدة.

📄 التوثيق:

- `git-switch.md`

---

### 3. `git checkout`

يُستخدم الأمر للتنقل بين الفروع واستعادة الملفات.

📄 التوثيق:

- `git-checkout.md`

---

### 4. `git merge`

يُستخدم الأمر لدمج التغييرات من فرع إلى فرع آخر.

📄 التوثيق:

- `git-merge.md`

---

## 🌳 ما هو الـ Branch؟

الـ Branch هو مسار مستقل للتطوير داخل مستودع Git.

تسمح لك الفروع بالعمل على ميزات جديدة أو إصلاحات أو تجارب دون التأثير مباشرة على الفرع الرئيسي.

ومن أشهر أسماء الفروع الرئيسية:

```bash
main
```

يمكنك إنشاء فرع جديد لميزة معينة:

```bash
git branch feature-login
```

---

## 🔄 سير العمل الأساسي للفروع

يمكن أن يكون سير العمل المعتاد للفروع بالشكل التالي:

```bash
git branch feature-login
git switch feature-login
git add .
git commit -m "Add login feature"
git switch main
git merge feature-login
```

وتكون العملية كالتالي:

1. إنشاء فرع جديد
2. الانتقال إلى الفرع الجديد
3. إجراء التغييرات
4. إنشاء Commit للتغييرات
5. العودة إلى الفرع الرئيسي
6. دمج فرع الميزة مع الفرع الرئيسي

---

## 💡 لماذا نستخدم الفروع؟

الفروع مفيدة لأنها تسمح لك بـ:

- العمل على الميزات بشكل مستقل
- تجربة أفكار جديدة بأمان
- إصلاح الأخطاء دون التأثير على الفرع الرئيسي
- العمل مع مطورين آخرين
- الحفاظ على استقرار الفرع الرئيسي

---

## 📝 الخلاصة

توفر فروع Git طريقة آمنة للعمل على إصدارات أو ميزات مختلفة من المشروع.

الأوامر الأساسية التي سنتعلمها في هذا الفصل هي:

```bash
git branch
git switch
git checkout
git merge
```

ويُعتبر فهم الفروع خطوة مهمة للعمل بشكل فعال باستخدام Git و GitHub.
