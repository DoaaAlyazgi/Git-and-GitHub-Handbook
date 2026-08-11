# 🔀 Git Checkout

## 🌐 English

`git checkout` is used to switch between branches and restore files in a Git repository.

Although `git switch` is now preferred for switching branches, `git checkout` is still widely used and is an important Git command to understand.

---

## 🔹 Switch to an Existing Branch

To switch to an existing branch:

```bash
git checkout feature-login
```

This changes your current branch to `feature-login`.

---

## 🔹 Create and Switch to a New Branch

To create a new branch and switch to it:

```bash
git checkout -b feature-login
```

This is equivalent to:

```bash
git branch feature-login
git checkout feature-login
```

---

## 🔹 Switch Back to the Main Branch

To return to the `main` branch:

```bash
git checkout main
```

---

## 🔹 Restore a File

`git checkout` can also be used to restore a file to its previous state.

For example:

```bash
git checkout -- filename.txt
```

This discards the changes made to `filename.txt` since the last commit.

⚠️ Be careful when using this command because the discarded changes may not be recoverable.

---

## 🔹 Restore a File from a Specific Commit

You can restore a file from a specific commit:

```bash
git checkout commit-id -- filename.txt
```

Example:

```bash
git checkout abc1234 -- index.html
```

This retrieves the version of `index.html` from the specified commit.

---

## 🔹 Check Out a Specific Commit

You can also check out a specific commit:

```bash
git checkout commit-id
```

Example:

```bash
git checkout abc1234
```

This puts Git into a **detached HEAD** state.

In this state, you are not currently working on a branch.

If you want to keep new commits made from this point, create a new branch:

```bash
git switch -c new-branch
```

---

## 💡 `git checkout` vs `git switch`

For switching branches, modern Git recommends using:

```bash
git switch branch-name
```

instead of:

```bash
git checkout branch-name
```

`git checkout` still has additional uses, such as restoring files and checking out specific commits.

---

## 📝 Summary

Common `git checkout` commands include:

```bash
git checkout branch-name
```

Switch to an existing branch.

```bash
git checkout -b branch-name
```

Create a new branch and switch to it.

```bash
git checkout -- filename.txt
```

Restore a file to its previous state.

```bash
git checkout commit-id
```

Check out a specific commit.

Understanding `git checkout` is useful for working with older Git workflows and existing projects.

---

# 🇵🇸 العربية

# 🔀 Git Checkout

يُستخدم الأمر `git checkout` للتنقل بين الفروع واستعادة الملفات داخل مستودع Git.

وعلى الرغم من أن Git يوصي حاليًا باستخدام `git switch` للتنقل بين الفروع، فإن `git checkout` لا يزال مستخدمًا بشكل واسع ويُعد أمرًا مهمًا لفهمه.

---

## 🔹 الانتقال إلى فرع موجود

للانتقال إلى فرع موجود:

```bash
git checkout feature-login
```

ينقلك هذا الأمر إلى الفرع `feature-login`.

---

## 🔹 إنشاء فرع جديد والانتقال إليه

لإنشاء فرع جديد والانتقال إليه:

```bash
git checkout -b feature-login
```

وهذا يعادل تنفيذ:

```bash
git branch feature-login
git checkout feature-login
```

---

## 🔹 العودة إلى الفرع الرئيسي

للعودة إلى فرع `main`:

```bash
git checkout main
```

---

## 🔹 استعادة ملف

يمكن استخدام `git checkout` أيضًا لاستعادة ملف إلى حالته السابقة.

مثال:

```bash
git checkout -- filename.txt
```

يقوم هذا الأمر بإلغاء التغييرات التي تم إجراؤها على `filename.txt` منذ آخر Commit.

⚠️ انتبه عند استخدام هذا الأمر، لأن التغييرات التي يتم التخلص منها قد لا يمكن استعادتها.

---

## 🔹 استعادة ملف من Commit محدد

يمكنك استعادة ملف من Commit معين:

```bash
git checkout commit-id -- filename.txt
```

مثال:

```bash
git checkout abc1234 -- index.html
```

يقوم هذا الأمر باسترجاع نسخة `index.html` الموجودة في الـ Commit المحدد.

---

## 🔹 الانتقال إلى Commit محدد

يمكنك أيضًا الانتقال إلى Commit معين:

```bash
git checkout commit-id
```

مثال:

```bash
git checkout abc1234
```

يضع هذا Git في حالة تسمى **Detached HEAD**.

في هذه الحالة، لا تكون حاليًا على أي فرع.

إذا أردت الاحتفاظ بأي Commits جديدة تقوم بإنشائها من هذه النقطة، يمكنك إنشاء فرع جديد:

```bash
git switch -c new-branch
```

---

## 💡 الفرق بين `git checkout` و `git switch`

عند التنقل بين الفروع، يوصي Git الحديث باستخدام:

```bash
git switch branch-name
```

بدلًا من:

```bash
git checkout branch-name
```

لكن `git checkout` لا يزال يمتلك استخدامات أخرى، مثل استعادة الملفات والانتقال إلى Commits محددة.

---

## 📝 الخلاصة

من أوامر `git checkout` الشائعة:

```bash
git checkout branch-name
```

للانتقال إلى فرع موجود.

```bash
git checkout -b branch-name
```

لإنشاء فرع جديد والانتقال إليه.

```bash
git checkout -- filename.txt
```

لاستعادة ملف إلى حالته السابقة.

```bash
git checkout commit-id
```

للانتقال إلى Commit محدد.

فهم `git checkout` مفيد عند التعامل مع سير العمل القديم في Git والمشاريع الموجودة مسبقًا.
