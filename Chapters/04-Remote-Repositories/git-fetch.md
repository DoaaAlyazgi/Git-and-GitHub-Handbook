# 🔄 Git Fetch

## 🌐 English

`git fetch` is used to download changes and information from a remote repository without automatically merging those changes into your current branch.

It allows you to inspect remote updates before deciding whether to merge them.

---

## 🔹 Basic Usage

To fetch changes from the default remote:

```bash
git fetch
```

Git downloads information about remote changes but does not modify your current working files.

---

## 🔹 Fetch from a Specific Remote

To fetch from a specific remote:

```bash
git fetch origin
```

Here, `origin` is the name of the remote repository.

---

## 🔹 Fetch a Specific Branch

To fetch a specific branch:

```bash
git fetch origin main
```

This downloads information about the `main` branch from the `origin` remote.

---

## 🔹 What Happens After `git fetch`?

After fetching, Git updates your remote-tracking branches.

For example:

```text
origin/main
```

This represents the state of the `main` branch on the remote repository.

Your local `main` branch does not automatically move.

---

## 🔹 Compare Local and Remote Changes

After fetching, you can compare your local branch with the remote branch:

```bash
git diff main origin/main
```

You can also inspect the commits:

```bash
git log main..origin/main
```

This can help you understand what changed on the remote before merging those changes.

---

## 🔹 Fetch and Then Merge

If you want to download changes first and merge them later:

```bash
git fetch origin
git merge origin/main
```

This gives you more control than using `git pull` directly.

---

## 🔄 `git fetch` vs `git pull`

The main difference is:

```text
git fetch
```

Downloads changes without merging them.

```text
git pull
```

Downloads changes and integrates them into the current branch.

A simple way to remember it:

**Fetch → Inspect → Merge**

---

## 💡 Example Workflow

Fetch the latest remote information:

```bash
git fetch origin
```

Check the differences:

```bash
git diff main origin/main
```

If you are ready to integrate the changes:

```bash
git merge origin/main
```

---

## 📝 Summary

The most common commands are:

```bash
git fetch
```

Fetch updates from the default remote.

```bash
git fetch origin
```

Fetch updates from a specific remote.

```bash
git fetch origin main
```

Fetch updates for a specific branch.

`git fetch` is useful when you want to inspect remote changes before integrating them into your local branch.

---

# 🇵🇸 العربية

# 🔄 Git Fetch

يُستخدم الأمر `git fetch` لتنزيل التغييرات والمعلومات من المستودع البعيد دون دمج هذه التغييرات تلقائيًا مع الفرع المحلي الحالي.

يسمح لك ذلك بفحص التحديثات الموجودة على المستودع البعيد قبل اتخاذ قرار بدمجها.

---

## 🔹 الاستخدام الأساسي

لجلب التغييرات من المستودع البعيد الافتراضي:

```bash
git fetch
```

يقوم Git بتنزيل معلومات التغييرات البعيدة، لكنه لا يقوم بتعديل ملفات العمل الحالية.

---

## 🔹 الجلب من مستودع بعيد محدد

للجلب من مستودع بعيد محدد:

```bash
git fetch origin
```

هنا `origin` هو اسم المستودع البعيد.

---

## 🔹 جلب فرع محدد

لجلب فرع محدد:

```bash
git fetch origin main
```

يقوم هذا بتنزيل معلومات فرع `main` من المستودع البعيد `origin`.

---

## 🔹 ماذا يحدث بعد `git fetch`؟

بعد تنفيذ Fetch، يقوم Git بتحديث الفروع التي تتتبع المستودعات البعيدة.

مثال:

```text
origin/main
```

يمثل هذا حالة فرع `main` الموجودة على المستودع البعيد.

لكن فرع `main` المحلي لا ينتقل تلقائيًا.

---

## 🔹 مقارنة التغييرات المحلية والبعيدة

بعد تنفيذ Fetch، يمكنك مقارنة الفرع المحلي مع الفرع البعيد:

```bash
git diff main origin/main
```

ويمكنك أيضًا فحص الـ Commits:

```bash
git log main..origin/main
```

يساعدك ذلك على معرفة ما الذي تغير في المستودع البعيد قبل دمج التغييرات.

---

## 🔹 Fetch ثم Merge

إذا أردت تنزيل التغييرات أولًا ثم دمجها لاحقًا:

```bash
git fetch origin
git merge origin/main
```

يعطيك هذا تحكمًا أكبر مقارنة باستخدام `git pull` مباشرة.

---

## 🔄 الفرق بين `git fetch` و `git pull`

الفرق الأساسي هو:

```text
git fetch
```

يقوم بتنزيل التغييرات دون دمجها.

```text
git pull
```

يقوم بتنزيل التغييرات ودمجها مع الفرع الحالي.

طريقة بسيطة لتذكر الفرق:

**Fetch → فحص → Merge**

---

## 💡 مثال على سير العمل

اجلب أحدث معلومات من المستودع البعيد:

```bash
git fetch origin
```

تحقق من الاختلافات:

```bash
git diff main origin/main
```

إذا كنت مستعدًا لدمج التغييرات:

```bash
git merge origin/main
```

---

## 📝 الخلاصة

الأوامر الأكثر استخدامًا هي:

```bash
git fetch
```

لجلب التحديثات من المستودع البعيد الافتراضي.

```bash
git fetch origin
```

لجلب التحديثات من مستودع بعيد محدد.

```bash
git fetch origin main
```

لجلب التحديثات الخاصة بفرع محدد.

يُعد `git fetch` مفيدًا عندما تريد فحص التغييرات الموجودة على المستودع البعيد قبل دمجها مع الفرع المحلي.
