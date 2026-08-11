# 🛑 Git Rebase Abort

## 🌐 English

`git rebase --abort` is used to cancel an active rebase operation.

It is useful when conflicts become difficult to resolve or when you decide that you do not want to continue the rebase.

---

## 🔹 Basic Usage

```bash
git rebase --abort
```

Git cancels the rebase and attempts to restore the repository to its previous state.

---

## 🔹 Example

Start a rebase:

```bash
git rebase main
```

If conflicts occur and you do not want to continue:

```bash
git rebase --abort
```

---

## 🔹 Check the Repository

After aborting:

```bash
git status
```

You can also inspect the history:

```bash
git log --oneline --graph
```

---

## 💡 When to Use It

Use `git rebase --abort` when:

- You selected the wrong branch
- Conflicts are too difficult to resolve
- You want to cancel the operation
- You want to return to the state before the rebase

---

## 📝 Summary

```bash
git rebase --abort
```

Cancels an active rebase operation.

---

# 🇵🇸 العربية

# 🛑 Git Rebase Abort

## العربية

يُستخدم `git rebase --abort` لإلغاء عملية Rebase قيد التنفيذ.

يكون هذا مفيدًا عندما تصبح التعارضات صعبة الحل أو عندما تقرر أنك لا تريد متابعة عملية Rebase.

---

## 🔹 الاستخدام الأساسي

```bash
git rebase --abort
```

يقوم Git بإلغاء عملية Rebase ومحاولة إعادة المستودع إلى حالته السابقة.

---

## 🔹 مثال

ابدأ عملية Rebase:

```bash
git rebase main
```

إذا حدثت تعارضات ولم تعد تريد المتابعة:

```bash
git rebase --abort
```

---

## 🔹 التحقق من المستودع

بعد الإلغاء:

```bash
git status
```

ويمكنك أيضًا مراجعة سجل Commits:

```bash
git log --oneline --graph
```

---

## 💡 متى نستخدمه؟

استخدم `git rebase --abort` عندما:

- اخترت الفرع الخطأ
- أصبحت التعارضات صعبة الحل
- تريد إلغاء العملية
- تريد العودة إلى الحالة التي كان عليها المستودع قبل Rebase

---

## 📝 الخلاصة

```bash
git rebase --abort
```

يلغي عملية Rebase قيد التنفيذ.
