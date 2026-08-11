# 🚫 Git Push Rejected

## 🌐 English

A push can be rejected when the remote repository contains changes that are not present in your local repository.

A common message is:

```text
! [rejected] main -> main (non-fast-forward)
```

---

## 🔹 Why Does This Happen?

This can happen when:

- Someone else pushed changes to the remote repository
- The remote branch contains commits you do not have locally
- The local and remote histories have diverged

---

## 🔹 Check the Remote Changes

First, retrieve information from the remote repository:

```bash
git fetch origin
```

Then inspect the differences:

```bash
git log --oneline --graph --all
```

---

## 🔹 Pull the Remote Changes

You can update your local branch:

```bash
git pull origin main
```

If a merge conflict occurs, resolve it before pushing again.

---

## 🔹 Push Again

After updating your local branch:

```bash
git push origin main
```

---

## 🔹 Using Rebase

You can also update your branch using Rebase:

```bash
git pull --rebase origin main
```

Then:

```bash
git push origin main
```

---

## ⚠️ Avoid Force Push Unless Necessary

Do not immediately use:

```bash
git push --force
```

Force pushing can overwrite remote history.

If you absolutely need to force push, prefer:

```bash
git push --force-with-lease
```

and make sure you understand the consequences.

---

## 📝 Summary

When Push is rejected:

```bash
git fetch origin
git pull origin main
git push origin main
```

Or use:

```bash
git pull --rebase origin main
git push origin main
```

---

# 🇵🇸 العربية

# 🚫 Git Push Rejected

## العربية

قد يتم رفض عملية Push عندما يحتوي المستودع البعيد على تغييرات غير موجودة في المستودع المحلي.

ومن الرسائل الشائعة:

```text
! [rejected] main -> main (non-fast-forward)
```

---

## 🔹 لماذا يحدث ذلك؟

قد يحدث هذا عندما:

- قام شخص آخر برفع تغييرات إلى المستودع البعيد
- يحتوي الفرع البعيد على Commits غير موجودة لديك
- أصبح سجل المستودع المحلي والبعيد مختلفًا

---

## 🔹 التحقق من تغييرات المستودع البعيد

أولًا، احصل على معلومات المستودع البعيد:

```bash
git fetch origin
```

ثم راجع الاختلافات:

```bash
git log --oneline --graph --all
```

---

## 🔹 جلب التغييرات

يمكنك تحديث الفرع المحلي:

```bash
git pull origin main
```

إذا حدث Merge Conflict، قم بحله قبل تنفيذ Push مرة أخرى.

---

## 🔹 تنفيذ Push مرة أخرى

بعد تحديث الفرع المحلي:

```bash
git push origin main
```

---

## 🔹 استخدام Rebase

يمكنك أيضًا تحديث الفرع باستخدام Rebase:

```bash
git pull --rebase origin main
```

ثم:

```bash
git push origin main
```

---

## ⚠️ تجنب Force Push إلا عند الحاجة

لا تستخدم مباشرة:

```bash
git push --force
```

لأن Force Push قد يؤدي إلى الكتابة فوق سجل المستودع البعيد.

إذا كنت تحتاج فعلًا إلى Force Push، فمن الأفضل استخدام:

```bash
git push --force-with-lease
```

وتأكد من فهم النتائج قبل تنفيذ الأمر.

---

## 📝 الخلاصة

عندما يتم رفض Push:

```bash
git fetch origin
git pull origin main
git push origin main
```

أو استخدم:

```bash
git pull --rebase origin main
git push origin main
```
