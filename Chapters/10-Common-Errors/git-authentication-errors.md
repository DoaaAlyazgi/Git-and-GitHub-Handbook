# 🔐 Git Authentication Errors

## 🌐 English

Authentication errors can occur when Git cannot authenticate you with a remote repository.

This can happen when using HTTPS or SSH to communicate with a remote repository.

---

## 🔹 Common Authentication Error

You may see messages such as:

```text
Authentication failed
```

or:

```text
Permission denied
```

---

## 🔹 Check the Remote URL

First, check your remote:

```bash
git remote -v
```

Make sure the URL points to the correct repository.

---

## 🔹 HTTPS Authentication

When using HTTPS, GitHub no longer accepts account passwords for Git operations.

You may need to authenticate using a Personal Access Token or Git Credential Manager.

---

## 🔹 SSH Authentication

You can also use SSH to authenticate with GitHub.

Check whether your remote uses SSH:

```bash
git remote -v
```

An SSH URL usually looks like:

```text
git@github.com:username/project.git
```

---

## 🔹 Check SSH Connection

You can test your SSH connection with:

```bash
ssh -T git@github.com
```

A successful connection should confirm that GitHub recognized your authentication.

---

## 🔹 Permission Problems

Authentication can succeed while authorization fails.

For example, you may be authenticated but not have permission to push to a repository.

In that case, verify:

- You are using the correct GitHub account
- You have access to the repository
- The remote URL is correct
- You are pushing to a branch you are allowed to modify

---

## ⚠️ Important Security Note

Never share your Personal Access Token or private SSH key.

Treat authentication credentials like passwords.

---

## 📝 Summary

Useful commands:

```bash
git remote -v
ssh -T git@github.com
```

Authentication problems can usually be traced to incorrect credentials, incorrect remote URLs, or insufficient repository permissions.

---

# 🇵🇸 العربية

# 🔐 Git Authentication Errors

## العربية

قد تحدث أخطاء المصادقة عندما لا يستطيع Git التحقق من هويتك عند الاتصال بمستودع بعيد.

قد يحدث ذلك عند استخدام HTTPS أو SSH للتواصل مع المستودع البعيد.

---

## 🔹 خطأ مصادقة شائع

قد تظهر رسائل مثل:

```text
Authentication failed
```

أو:

```text
Permission denied
```

---

## 🔹 التحقق من رابط Remote

أولًا، تحقق من الـ Remote:

```bash
git remote -v
```

تأكد من أن الرابط يشير إلى المستودع الصحيح.

---

## 🔹 المصادقة باستخدام HTTPS

عند استخدام HTTPS، لا يقبل GitHub كلمات مرور الحساب لتنفيذ عمليات Git.

قد تحتاج إلى استخدام Personal Access Token أو Git Credential Manager للمصادقة.

---

## 🔹 المصادقة باستخدام SSH

يمكنك أيضًا استخدام SSH للمصادقة مع GitHub.

تحقق مما إذا كان الـ Remote يستخدم SSH:

```bash
git remote -v
```

عادةً يكون رابط SSH بهذا الشكل:

```text
git@github.com:username/project.git
```

---

## 🔹 اختبار اتصال SSH

يمكنك اختبار اتصال SSH باستخدام:

```bash
ssh -T git@github.com
```

عند نجاح الاتصال، سيؤكد GitHub أن عملية المصادقة تمت بنجاح.

---

## 🔹 مشاكل الصلاحيات

قد تنجح المصادقة ولكن تفشل الصلاحيات.

على سبيل المثال، قد تكون مصادقًا بنجاح ولكن لا تملك صلاحية Push إلى المستودع.

في هذه الحالة، تحقق من:

- أنك تستخدم حساب GitHub الصحيح
- أنك تملك صلاحية الوصول إلى المستودع
- أن رابط Remote صحيح
- أنك تقوم بالـ Push إلى فرع يسمح لك بتعديله

---

## ⚠️ ملاحظة أمنية مهمة

لا تشارك Personal Access Token أو مفتاح SSH الخاص بك مع أي شخص.

تعامل مع بيانات المصادقة مثل كلمات المرور.

---

## 📝 الخلاصة

أوامر مفيدة:

```bash
git remote -v
ssh -T git@github.com
```

غالبًا يمكن إرجاع مشاكل المصادقة إلى بيانات اعتماد غير صحيحة، أو رابط Remote غير صحيح، أو عدم امتلاك الصلاحيات اللازمة للمستودع.
