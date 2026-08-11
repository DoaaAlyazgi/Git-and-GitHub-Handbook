# 🛠️ Git Interactive Rebase

## 🌐 English

`git rebase -i` starts an interactive rebase.

It allows you to edit, reorder, combine, or remove commits before sharing your work.

---

## 🔹 Basic Usage

To interactively rebase the last three commits:

```bash
git rebase -i HEAD~3
```

Git opens an editor containing the selected commits.

---

## 🔹 Common Actions

Interactive Rebase provides several actions.

### `pick`

Keep the commit as it is.

```text
pick a1b2c3d Add login page
```

### `reword`

Change the commit message.

```text
reword a1b2c3d Add login page
```

### `edit`

Stop at the commit so you can modify it.

```text
edit a1b2c3d Add login page
```

### `squash`

Combine the commit with the previous commit.

```text
squash a1b2c3d Fix login button
```

### `drop`

Remove the commit.

```text
drop a1b2c3d Temporary changes
```

---

## 🔹 Example

Suppose your history is:

```text
A -- B -- C -- D
```

You can run:

```bash
git rebase -i HEAD~3
```

Then combine or reorder `B`, `C`, and `D`.

---

## 💡 Why Use Interactive Rebase?

Interactive Rebase is useful for:

- Cleaning up commit history
- Combining small commits
- Fixing commit messages
- Removing unnecessary commits
- Reordering commits

---

## ⚠️ Important Warning

Do not rewrite shared history unless you understand the consequences.

Interactive Rebase changes commit IDs.

---

## 📝 Summary

```bash
git rebase -i HEAD~3
```

Use Interactive Rebase to organize and clean up recent commits.

---

# 🇵🇸 العربية

# 🛠️ Git Interactive Rebase

## العربية

يبدأ `git rebase -i` عملية Rebase تفاعلية.

يسمح لك بتعديل أو إعادة ترتيب أو دمج أو حذف Commits قبل مشاركة عملك.

---

## 🔹 الاستخدام الأساسي

لعمل Interactive Rebase لآخر ثلاثة Commits:

```bash
git rebase -i HEAD~3
```

يقوم Git بفتح محرر يحتوي على الـ Commits المحددة.

---

## 🔹 الأوامر الشائعة

يوفر Interactive Rebase عدة خيارات.

### `pick`

الإبقاء على الـ Commit كما هو.

```text
pick a1b2c3d Add login page
```

### `reword`

تعديل رسالة الـ Commit.

```text
reword a1b2c3d Add login page
```

### `edit`

التوقف عند الـ Commit للسماح بتعديله.

```text
edit a1b2c3d Add login page
```

### `squash`

دمج الـ Commit مع الـ Commit السابق.

```text
squash a1b2c3d Fix login button
```

### `drop`

حذف الـ Commit.

```text
drop a1b2c3d Temporary changes
```

---

## 🔹 مثال

لنفترض أن سجل Commits لديك:

```text
A -- B -- C -- D
```

يمكنك تنفيذ:

```bash
git rebase -i HEAD~3
```

ثم دمج أو إعادة ترتيب `B` و `C` و `D`.

---

## 💡 لماذا نستخدم Interactive Rebase؟

يكون Interactive Rebase مفيدًا من أجل:

- تنظيف سجل Commits
- دمج الـ Commits الصغيرة
- إصلاح رسائل الـ Commits
- حذف Commits غير الضرورية
- إعادة ترتيب Commits

---

## ⚠️ تحذير مهم

لا تقم بإعادة كتابة سجل مشترك إلا إذا كنت تفهم النتائج.

يقوم Interactive Rebase بتغيير Commit IDs.

---

## 📝 الخلاصة

```bash
git rebase -i HEAD~3
```

استخدم Interactive Rebase لتنظيم وتنظيف الـ Commits الأخيرة.
