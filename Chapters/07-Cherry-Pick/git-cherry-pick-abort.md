# 🛑 Git Cherry Pick Abort

## 🌐 English

`git cherry-pick --abort` is used to cancel an active cherry-pick operation.

It is especially useful when a cherry-pick causes conflicts and you decide that you do not want to continue.

---

## 🔹 Basic Usage

```bash
git cherry-pick --abort
```

Git stops the cherry-pick operation and attempts to return the repository to the state it was in before the operation started.

---

## 🔹 When to Use It

Use `git cherry-pick --abort` when:

- A conflict occurs
- You do not want to resolve the conflict
- You selected the wrong commit
- You want to cancel the current cherry-pick operation

---

## 🔹 Example

Start a cherry-pick:

```bash
git cherry-pick commit-hash
```

If a conflict occurs, you can cancel the operation:

```bash
git cherry-pick --abort
```

---

## 🔹 Check the Repository

After aborting, check the status:

```bash
git status
```

---

## 📝 Summary

```bash
git cherry-pick --abort
```

Cancels an active cherry-pick operation and restores the repository as closely as possible to its previous state.

---

# 🇵🇸 العربية

# 🛑 Git Cherry Pick Abort

## العربية

يُستخدم `git cherry-pick --abort` لإلغاء عملية Cherry Pick قيد التنفيذ.

يكون هذا مفيدًا بشكل خاص عندما يتسبب Cherry Pick في حدوث تعارضات وتقرر أنك لا تريد المتابعة.

---

## 🔹 الاستخدام الأساسي

```bash
git cherry-pick --abort
```

يقوم Git بإيقاف عملية Cherry Pick ومحاولة إعادة المستودع إلى الحالة التي كان عليها قبل بدء العملية.

---

## 🔹 متى نستخدمه؟

استخدم `git cherry-pick --abort` عندما:

- يحدث تعارض
- لا تريد حل التعارض
- اخترت Commit خاطئًا
- تريد إلغاء عملية Cherry Pick الحالية

---

## 🔹 مثال

ابدأ عملية Cherry Pick:

```bash
git cherry-pick commit-hash
```

إذا حدث تعارض، يمكنك إلغاء العملية:

```bash
git cherry-pick --abort
```

---

## 🔹 التحقق من المستودع

بعد الإلغاء، تحقق من الحالة:

```bash
git status
```

---

## 📝 الخلاصة

```bash
git cherry-pick --abort
```

يلغي عملية Cherry Pick قيد التنفيذ ويحاول إعادة المستودع إلى حالته السابقة قدر الإمكان.
