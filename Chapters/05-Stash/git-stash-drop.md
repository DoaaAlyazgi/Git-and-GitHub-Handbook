# 🗑️ Git Stash Drop

## 🌐 English

`git stash drop` is used to delete a specific stash from the stash list.

It is useful when you no longer need a saved stash.

---

## 🔹 Basic Usage

To delete the latest stash:

```bash
git stash drop
```

---

## 🔹 Delete a Specific Stash

To delete a specific stash:

```bash
git stash drop stash@{1}
```

Git removes that stash from the stash list.

---

## 🔹 View Stashes Before Deleting

It is a good idea to check your stashes first:

```bash
git stash list
```

Then delete the stash you no longer need:

```bash
git stash drop stash@{1}
```

---

## ⚠️ Important Note

Deleting a stash removes it from the stash list.

Make sure you no longer need the changes before deleting the stash.

---

## 📝 Summary

Common commands:

```bash
git stash drop
```

Delete the latest stash.

```bash
git stash drop stash@{1}
```

Delete a specific stash.

---

# 🇵🇸 العربية

# 🗑️ Git Stash Drop

## العربية

يُستخدم الأمر `git stash drop` لحذف Stash محدد من قائمة Stashes.

يكون هذا مفيدًا عندما لا تعود بحاجة إلى Stash محفوظ.

---

## 🔹 الاستخدام الأساسي

لحذف أحدث Stash:

```bash
git stash drop
```

---

## 🔹 حذف Stash محدد

لحذف Stash محدد:

```bash
git stash drop stash@{1}
```

يقوم Git بإزالة الـ Stash من القائمة.

---

## 🔹 عرض Stashes قبل الحذف

من الأفضل التحقق من الـ Stashes أولًا:

```bash
git stash list
```

ثم حذف الـ Stash الذي لم تعد بحاجة إليه:

```bash
git stash drop stash@{1}
```

---

## ⚠️ ملاحظة مهمة

يؤدي حذف Stash إلى إزالته من قائمة Stashes.

تأكد من أنك لم تعد بحاجة إلى التغييرات الموجودة بداخله قبل حذفه.

---

## 📝 الخلاصة

الأوامر الشائعة:

```bash
git stash drop
```

لحذف أحدث Stash.

```bash
git stash drop stash@{1}
```

لحذف Stash محدد.
