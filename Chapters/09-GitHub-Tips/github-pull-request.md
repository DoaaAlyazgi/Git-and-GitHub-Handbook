# 🔀 GitHub Pull Request

## 🌐 English

A Pull Request, commonly called a PR, is a request to merge changes from one branch into another repository branch.

Pull Requests are an important part of collaborative development on GitHub.

---

## 🔹 Basic Workflow

A common Pull Request workflow is:

```text
Create Branch
     ↓
Make Changes
     ↓
Commit Changes
     ↓
Push Branch
     ↓
Create Pull Request
     ↓
Code Review
     ↓
Merge
```

---

## 🔹 Create a Branch

Create a new branch:

```bash
git switch -c feature-branch
```

---

## 🔹 Make and Commit Changes

After making your changes:

```bash
git add .
git commit -m "Add new feature"
```

---

## 🔹 Push the Branch

```bash
git push -u origin feature-branch
```

---

## 🔹 Open a Pull Request

Go to your GitHub repository.

GitHub may show an option to create a Pull Request for the recently pushed branch.

Select:

```text
Compare & pull request
```

Then provide:

- Pull Request title
- Description
- Reviewers if needed

---

## 🔹 Code Review

Other developers can review your Pull Request.

They can:

- Leave comments
- Suggest changes
- Approve the Pull Request
- Request modifications

---

## 🔹 Merge the Pull Request

After the Pull Request is approved and checks pass, it can be merged into the target branch.

---

## 💡 Why Use Pull Requests?

Pull Requests help teams:

- Review code
- Discuss changes
- Catch bugs
- Improve code quality
- Collaborate safely
- Keep the main branch stable

---

## ⚠️ Important Note

A Pull Request does not automatically mean that changes are immediately merged.

The repository maintainers can review the changes before deciding whether to merge them.

---

## 📝 Summary

A Pull Request provides a structured way to propose and review changes before merging them into another branch.

Typical workflow:

```bash
git switch -c feature-branch
git add .
git commit -m "Add new feature"
git push -u origin feature-branch
```

Then create a Pull Request on GitHub.

---

# 🇵🇸 العربية

# 🔀 GitHub Pull Request

## العربية

الـ Pull Request، ويُختصر عادةً إلى PR، هو طلب لدمج التغييرات من فرع إلى فرع آخر داخل المستودع.

تُعد Pull Requests جزءًا أساسيًا من عملية التطوير الجماعي على GitHub.

---

## 🔹 سير العمل الأساسي

سير العمل المعتاد للـ Pull Request:

```text
Create Branch
     ↓
Make Changes
     ↓
Commit Changes
     ↓
Push Branch
     ↓
Create Pull Request
     ↓
Code Review
     ↓
Merge
```

---

## 🔹 إنشاء Branch

أنشئ فرعًا جديدًا:

```bash
git switch -c feature-branch
```

---

## 🔹 إجراء التغييرات وإنشاء Commit

بعد إجراء التغييرات:

```bash
git add .
git commit -m "Add new feature"
```

---

## 🔹 رفع الفرع

```bash
git push -u origin feature-branch
```

---

## 🔹 فتح Pull Request

اذهب إلى مستودعك على GitHub.

قد يعرض GitHub خيار إنشاء Pull Request للفرع الذي قمت برفعه مؤخرًا.

اختر:

```text
Compare & pull request
```

ثم أضف:

- عنوان Pull Request
- وصف التغييرات
- Reviewers إذا لزم الأمر

---

## 🔹 مراجعة الكود

يمكن للمطورين الآخرين مراجعة Pull Request.

ويمكنهم:

- إضافة تعليقات
- اقتراح تغييرات
- الموافقة على Pull Request
- طلب تعديلات

---

## 🔹 دمج Pull Request

بعد الموافقة على Pull Request ونجاح الفحوصات المطلوبة، يمكن دمجه في الفرع المستهدف.

---

## 💡 لماذا نستخدم Pull Requests؟

تساعد Pull Requests الفرق على:

- مراجعة الأكواد
- مناقشة التغييرات
- اكتشاف الأخطاء
- تحسين جودة الكود
- التعاون بطريقة آمنة
- الحفاظ على استقرار الفرع الرئيسي

---

## ⚠️ ملاحظة مهمة

إنشاء Pull Request لا يعني أن التغييرات سيتم دمجها مباشرة.

يمكن لمسؤولي المستودع مراجعة التغييرات قبل اتخاذ قرار دمجها.

---

## 📝 الخلاصة

يوفر Pull Request طريقة منظمة لاقتراح ومراجعة التغييرات قبل دمجها في فرع آخر.

سير العمل المعتاد:

```bash
git switch -c feature-branch
git add .
git commit -m "Add new feature"
git push -u origin feature-branch
```

ثم قم بإنشاء Pull Request على GitHub.
