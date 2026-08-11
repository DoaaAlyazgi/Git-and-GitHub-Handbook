# 🔄 Git Basic Workflow

## 🌐 English

The Git workflow is the basic process developers use to track, save, and manage changes in a project.

The workflow usually follows these steps:

```text
Working Directory → Staging Area → Commit → Repository
```

Understanding this workflow is essential before learning more advanced Git commands.

---

## 🔹 Step 1: Working Directory

The **Working Directory** is the folder containing your project files.

When you create, edit, or delete a file, the changes first exist in your Working Directory.

For example:

```text
project/
├── index.html
├── style.css
└── script.js
```

If you modify `index.html`, Git detects that the file has changed.

You can check the current state using:

```bash
git status
```

---

## 🔹 Step 2: Staging Area

The **Staging Area** is where you select the changes that you want to include in your next commit.

To stage a specific file:

```bash
git add index.html
```

To stage all changed files:

```bash
git add .
```

You can check the staged changes with:

```bash
git status
```

---

## 🔹 Step 3: Commit

A **commit** saves the staged changes as a new version in Git.

Create a commit using:

```bash
git commit -m "Add homepage"
```

A good commit message should clearly describe what was changed.

For example:

```bash
git commit -m "Fix login form validation"
```

---

## 🔹 Step 4: Repository

The **Git Repository** stores the project's commit history.

After creating a commit, Git records the changes in the repository.

You can view the commit history using:

```bash
git log
```

A shorter version is:

```bash
git log --oneline
```

---

## 🔹 The Complete Workflow

A typical Git workflow looks like this:

```bash
git status
git add .
git commit -m "Update project"
```

The process can be visualized as:

```text
Edit Files
    ↓
Working Directory
    ↓
git add
    ↓
Staging Area
    ↓
git commit
    ↓
Git Repository
```

---

## 💡 Example

Imagine you are working on a website and modify the homepage.

First, check the changes:

```bash
git status
```

Then stage the file:

```bash
git add index.html
```

Create a commit:

```bash
git commit -m "Update homepage"
```

Finally, check the history:

```bash
git log --oneline
```

Now your changes are safely recorded in Git.

---

## ⚠️ Important Notes

- `git status` shows the current state of your files.
- `git add` moves changes to the Staging Area.
- `git commit` saves staged changes in the repository.
- A commit should represent a meaningful change.
- You can create multiple commits as you work.
- Git allows you to return to previous versions when needed.

---

# 🔄 سير العمل الأساسي في Git

## 🌐 العربية

سير العمل في Git هو العملية الأساسية التي يستخدمها المطورون لتتبع التغييرات وحفظها وإدارتها داخل المشروع.

عادةً يمر سير العمل بالمراحل التالية:

```text
Working Directory → Staging Area → Commit → Repository
```

فهم هذا السير ضروري قبل الانتقال إلى أوامر Git المتقدمة.

---

## 🔹 الخطوة 1: Working Directory

الـ **Working Directory** هو المجلد الذي يحتوي على ملفات المشروع.

عندما تقوم بإنشاء ملف أو تعديله أو حذفه، فإن التغييرات تكون في البداية داخل الـ Working Directory.

على سبيل المثال:

```text
project/
├── index.html
├── style.css
└── script.js
```

إذا قمت بتعديل ملف `index.html`، سيكتشف Git أن الملف قد تغير.

يمكنك معرفة حالة الملفات باستخدام:

```bash
git status
```

---

## 🔹 الخطوة 2: Staging Area

الـ **Staging Area** هي المنطقة التي تختار فيها التغييرات التي تريد تضمينها في الـ commit القادم.

لإضافة ملف محدد إلى الـ Staging Area:

```bash
git add index.html
```

لإضافة جميع الملفات التي تحتوي على تغييرات:

```bash
git add .
```

يمكنك التحقق من الملفات التي تمت إضافتها باستخدام:

```bash
git status
```

---

## 🔹 الخطوة 3: Commit

الـ **Commit** يقوم بحفظ التغييرات الموجودة في الـ Staging Area كنسخة جديدة داخل Git.

لإنشاء Commit:

```bash
git commit -m "Add homepage"
```

يجب أن تكون رسالة الـ commit واضحة وتصف التغيير الذي قمت به.

مثال:

```bash
git commit -m "Fix login form validation"
```

---

## 🔹 الخطوة 4: Repository

الـ **Git Repository** هو المكان الذي يتم فيه حفظ سجل التغييرات والـ commits الخاصة بالمشروع.

بعد إنشاء Commit، يقوم Git بتسجيل التغييرات داخل الـ Repository.

لعرض سجل الـ commits استخدم:

```bash
git log
```

ويمكنك استخدام نسخة مختصرة:

```bash
git log --oneline
```

---

## 🔹 سير العمل الكامل

يبدو سير العمل المعتاد في Git بهذا الشكل:

```bash
git status
git add .
git commit -m "Update project"
```

ويمكن توضيح العملية بالشكل التالي:

```text
تعديل الملفات
    ↓
Working Directory
    ↓
git add
    ↓
Staging Area
    ↓
git commit
    ↓
Git Repository
```

---

## 💡 مثال عملي

لنفترض أنك تعمل على موقع إلكتروني وقمت بتعديل الصفحة الرئيسية.

أولًا، تحقق من التغييرات:

```bash
git status
```

ثم أضف الملف إلى الـ Staging Area:

```bash
git add index.html
```

بعد ذلك أنشئ Commit:

```bash
git commit -m "Update homepage"
```

وأخيرًا اعرض سجل التغييرات:

```bash
git log --oneline
```

الآن أصبحت تغييراتك محفوظة ومسجلة بأمان داخل Git.

---

## ⚠️ ملاحظات مهمة

- الأمر `git status` يعرض الحالة الحالية لملفات المشروع.
- الأمر `git add` ينقل التغييرات إلى الـ Staging Area.
- الأمر `git commit` يحفظ التغييرات الموجودة في الـ Staging Area داخل الـ Repository.
- من الأفضل أن يمثل كل Commit تغييرًا واضحًا ومفيدًا.
- يمكنك إنشاء عدة Commits أثناء العمل على المشروع.
- يسمح لك Git بالرجوع إلى إصدارات سابقة عند الحاجة.
