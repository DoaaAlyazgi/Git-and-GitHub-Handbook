# 🧭 Git Detached HEAD

## 🌐 English

A detached HEAD state occurs when `HEAD` points directly to a commit instead of pointing to a branch.

This can happen when you check out a specific commit.

---

## 🔹 Example

Suppose you have:

```text
A -- B -- C
```

If you check out commit `B`:

```bash
git switch --detach B
```

Git enters a detached HEAD state.

---

## 🔹 Check the Status

Run:

```bash
git status
```

Git will tell you that you are in a detached HEAD state.

---

## 🔹 Why Is This Important?

You can inspect files and test code in detached HEAD mode.

However, if you create new commits there, they may become difficult to find unless you create a branch.

---

## 🔹 Create a Branch

If you want to keep your work:

```bash
git switch -c new-branch
```

Your current commit becomes the starting point of the new branch.

---

## 🔹 Return to an Existing Branch

If you do not need the detached state:

```bash
git switch main
```

---

## 🔹 Example Workflow

Check out a commit:

```bash
git switch --detach commit-hash
```

Make changes and decide to keep them:

```bash
git switch -c my-new-branch
```

Now your work is associated with a branch.

---

## 📝 Summary

Detached HEAD means that `HEAD` is pointing directly to a commit instead of a branch.

To keep your work:

```bash
git switch -c new-branch
```

To return to an existing branch:

```bash
git switch main
```

---

# 🇵🇸 العربية

# 🧭 Git Detached HEAD

## العربية

تحدث حالة Detached HEAD عندما يشير `HEAD` مباشرةً إلى Commit بدلًا من الإشارة إلى Branch.

قد يحدث ذلك عندما تقوم بالانتقال إلى Commit محدد.

---

## 🔹 مثال

لنفترض أن لديك:

```text
A -- B -- C
```

إذا انتقلت إلى Commit `B`:

```bash
git switch --detach B
```

يدخل Git في حالة Detached HEAD.

---

## 🔹 التحقق من الحالة

نفذ:

```bash
git status
```

سيخبرك Git بأنك في حالة Detached HEAD.

---

## 🔹 لماذا هذا مهم؟

يمكنك في حالة Detached HEAD استعراض الملفات وتجربة الكود.

ولكن إذا أنشأت Commits جديدة في هذه الحالة، فقد يصبح من الصعب الوصول إليها لاحقًا إذا لم تنشئ Branch.

---

## 🔹 إنشاء Branch

إذا كنت تريد الاحتفاظ بعملك:

```bash
git switch -c new-branch
```

سيصبح الـ Commit الحالي نقطة البداية للفرع الجديد.

---

## 🔹 العودة إلى Branch موجود

إذا لم تعد بحاجة إلى حالة Detached HEAD:

```bash
git switch main
```

---

## 🔹 مثال على سير العمل

الانتقال إلى Commit محدد:

```bash
git switch --detach commit-hash
```

إجراء تغييرات ثم تقرير الاحتفاظ بها:

```bash
git switch -c my-new-branch
```

الآن أصبح عملك مرتبطًا بفرع.

---

## 📝 الخلاصة

تعني حالة Detached HEAD أن `HEAD` يشير مباشرةً إلى Commit بدلًا من Branch.

للاحتفاظ بعملك:

```bash
git switch -c new-branch
```

للعودة إلى Branch موجود:

```bash
git switch main
```
