# ⚙️ Git Installation and Setup

## 🌐 English

Before using Git, you need to install it on your computer and configure your basic identity.

This setup usually only needs to be done once on your computer.

---

## 🔹 Step 1: Check if Git Is Already Installed

Open your Terminal, Command Prompt, or Git Bash and run:

```bash
git --version
```

If Git is already installed, you will see something similar to:

```text
git version 2.x.x
```

The version number may be different depending on the version installed on your computer.

If the command works and displays a Git version, Git is already installed and you can continue to the next step.

If you see a message saying that Git is not recognized or the command cannot be found, you need to install Git.

---

## 🔹 Step 2: Install Git

If Git is not installed on your computer, download it from the official Git website and install it according to your operating system.

After the installation is complete, open your Terminal, Command Prompt, or Git Bash again.

Then run:

```bash
git --version
```

You should now see the installed Git version.

Example:

```text
git version 2.x.x
```

This confirms that Git has been installed successfully.

---

## 🔹 Step 3: Configure Your Username

After installing Git, you should configure your username.

Git uses this name to identify the person who creates commits.

Run:

```bash
git config --global user.name "Your Name"
```

Replace `Your Name` with your preferred name.

Example:

```bash
git config --global user.name "Doaa Alyazgi"
```

The `--global` option means that this username will be used for all Git repositories on your computer.

---

## 🔹 Step 4: Configure Your Email

Next, configure the email address associated with your Git identity.

Run:

```bash
git config --global user.email "your@email.com"
```

Example:

```bash
git config --global user.email "doaa@example.com"
```

It is recommended to use the same email address associated with your GitHub account.

This helps GitHub correctly associate your commits with your account when the email is verified.

---

## 🔹 Step 5: Verify Your Username

To check the username you configured, run:

```bash
git config --global user.name
```

Git will display the username you configured.

Example:

```text
Doaa Alyazgi
```

---

## 🔹 Step 6: Verify Your Email

To check your configured email, run:

```bash
git config --global user.email
```

Git will display the email address you configured.

Example:

```text
doaa@example.com
```

---

## 🔹 Step 7: View All Git Configuration

You can view your Git configuration using:

```bash
git config --list
```

This command displays the Git configuration values currently available on your computer.

You may see information such as:

```text
user.name=Doaa Alyazgi
user.email=doaa@example.com
```

---

## 🔹 Understanding `--global`

The `--global` option applies a configuration setting to all Git repositories for your current user account on the computer.

For example:

```bash
git config --global user.name "Your Name"
```

This means that the configured name will be used automatically when you create commits in different repositories.

You do not need to configure the username again for every repository unless you want to use a different identity for a specific project.

---

## 🔹 Local vs Global Configuration

Git supports different configuration levels.

### Global Configuration

Global configuration applies to all repositories for your user account.

Example:

```bash
git config --global user.name "Your Name"
```

### Local Configuration

Local configuration applies only to the current repository.

Example:

```bash
git config user.name "Project Name"
```

Local settings take priority over global settings for that specific repository.

This is useful when you need to use a different identity for a particular project.

---

## 💡 Important Note

Configuring your Git username and email does not mean that you are signing in to GitHub.

These settings only tell Git who is creating a commit.

Authentication with GitHub is a separate process and can be done using methods such as HTTPS or SSH.

Authentication and connecting Git to GitHub will be explained later in this handbook.

---

## 🧪 Quick Setup Example

Here is a complete example of the basic setup:

```bash
git --version

git config --global user.name "Your Name"

git config --global user.email "your@email.com"

git config --global user.name

git config --global user.email
```

After running these commands, Git should be installed and your basic identity should be configured.

---

## 🎯 Summary

After completing this setup, you should be able to:

- Check whether Git is installed.
- Install Git if necessary.
- Check the installed Git version.
- Configure your Git username.
- Configure your Git email.
- Verify your Git identity.
- View your Git configuration.
- Understand the purpose of `--global`.
- Understand the difference between global and local configuration.
- Understand that Git identity configuration is different from GitHub authentication.

Once Git is installed and configured, you are ready to start creating repositories and working with Git.

---

# 🇵🇸 العربية

قبل استخدام Git، تحتاج إلى تثبيته على جهاز الكمبيوتر الخاص بك وإعداد هويتك الأساسية.

عادةً ما تحتاج إلى إجراء هذا الإعداد مرة واحدة فقط على جهاز الكمبيوتر.

---

## 🔹 الخطوة 1: التحقق مما إذا كان Git مثبتًا بالفعل

افتح Terminal أو Command Prompt أو Git Bash، ثم نفّذ الأمر التالي:

```bash
git --version
```

إذا كان Git مثبتًا بالفعل، فستظهر لك نتيجة مشابهة لما يلي:

```text
git version 2.x.x
```

قد يختلف رقم الإصدار حسب إصدار Git المثبت على جهاز الكمبيوتر الخاص بك.

إذا تم تنفيذ الأمر بنجاح وظهر رقم إصدار Git، فهذا يعني أن Git مثبت بالفعل ويمكنك الانتقال إلى الخطوة التالية.

أما إذا ظهرت رسالة تفيد بأن Git غير معروف أو أن الأمر غير موجود، فهذا يعني أنك بحاجة إلى تثبيت Git.

---

## 🔹 الخطوة 2: تثبيت Git

إذا لم يكن Git مثبتًا على جهاز الكمبيوتر الخاص بك، قم بتنزيله من الموقع الرسمي لـ Git ثم ثبّته وفقًا لنظام التشغيل الخاص بك.

بعد اكتمال التثبيت، افتح Terminal أو Command Prompt أو Git Bash مرة أخرى.

ثم نفّذ:

```bash
git --version
```

يجب أن يظهر الآن إصدار Git المثبت.

مثال:

```text
git version 2.x.x
```

ظهور رقم الإصدار يؤكد أن Git تم تثبيته بنجاح.

---

## 🔹 الخطوة 3: إعداد اسم المستخدم

بعد تثبيت Git، يجب عليك إعداد اسم المستخدم الخاص بك.

يستخدم Git هذا الاسم لتحديد الشخص الذي يقوم بإنشاء عمليات الحفظ (Commits).

نفّذ الأمر التالي:

```bash
git config --global user.name "Your Name"
```

استبدل `Your Name` بالاسم الذي تريد استخدامه.

مثال:

```bash
git config --global user.name "Doaa Alyazgi"
```

الخيار `--global` يعني أن اسم المستخدم هذا سيتم استخدامه مع جميع مستودعات Git الموجودة على جهاز الكمبيوتر الخاص بك.

---

## 🔹 الخطوة 4: إعداد البريد الإلكتروني

بعد ذلك، قم بإعداد عنوان البريد الإلكتروني المرتبط بهويتك في Git.

نفّذ:

```bash
git config --global user.email "your@email.com"
```

مثال:

```bash
git config --global user.email "doaa@example.com"
```

يفضل استخدام نفس البريد الإلكتروني المرتبط بحساب GitHub الخاص بك.

يساعد ذلك GitHub على ربط عمليات Commit بحسابك عندما يكون البريد الإلكتروني موثّقًا.

---

## 🔹 الخطوة 5: التحقق من اسم المستخدم

للتحقق من اسم المستخدم الذي قمت بإعداده، نفّذ:

```bash
git config --global user.name
```

سيعرض Git اسم المستخدم الذي قمت بإعداده.

مثال:

```text
Doaa Alyazgi
```

---

## 🔹 الخطوة 6: التحقق من البريد الإلكتروني

للتحقق من البريد الإلكتروني الذي قمت بإعداده، نفّذ:

```bash
git config --global user.email
```

سيعرض Git عنوان البريد الإلكتروني الذي قمت بإعداده.

مثال:

```text
doaa@example.com
```

---

## 🔹 الخطوة 7: عرض جميع إعدادات Git

يمكنك عرض إعدادات Git باستخدام:

```bash
git config --list
```

يعرض هذا الأمر قيم إعدادات Git المتوفرة حاليًا على جهاز الكمبيوتر الخاص بك.

قد ترى معلومات مثل:

```text
user.name=Doaa Alyazgi
user.email=doaa@example.com
```

---

## 🔹 فهم الخيار `--global`

الخيار `--global` يجعل إعداد Git مطبقًا على جميع مستودعات Git الخاصة بحساب المستخدم الحالي على جهاز الكمبيوتر.

على سبيل المثال:

```bash
git config --global user.name "Your Name"
```

هذا يعني أن الاسم الذي قمت بإعداده سيتم استخدامه تلقائيًا عند إنشاء عمليات Commit في المستودعات المختلفة.

لا تحتاج إلى إعداد اسم المستخدم مرة أخرى لكل مستودع، إلا إذا كنت تريد استخدام هوية مختلفة لمشروع معين.

---

## 🔹 الإعداد العام مقابل الإعداد المحلي

يدعم Git مستويات مختلفة من الإعدادات.

### الإعداد العام Global

الإعداد العام يتم تطبيقه على جميع مستودعات Git الخاصة بحساب المستخدم.

مثال:

```bash
git config --global user.name "Your Name"
```

### الإعداد المحلي Local

الإعداد المحلي يتم تطبيقه فقط على مستودع Git الحالي.

مثال:

```bash
git config user.name "Project Name"
```

الإعدادات المحلية لها الأولوية على الإعدادات العامة داخل ذلك المستودع المحدد.

يكون هذا مفيدًا عندما تحتاج إلى استخدام هوية مختلفة لمشروع معين.

---

## 💡 ملاحظة مهمة

إعداد اسم المستخدم والبريد الإلكتروني في Git لا يعني أنك قمت بتسجيل الدخول إلى GitHub.

هذه الإعدادات تخبر Git فقط بهوية الشخص الذي يقوم بإنشاء Commit.

أما المصادقة مع GitHub فهي عملية منفصلة، ويمكن تنفيذها باستخدام طرق مثل HTTPS أو SSH.

سيتم شرح المصادقة وربط Git مع GitHub لاحقًا في هذا الدليل.

---

## 🧪 مثال سريع على الإعداد

فيما يلي مثال كامل للإعداد الأساسي:

```bash
git --version

git config --global user.name "Your Name"

git config --global user.email "your@email.com"

git config --global user.name

git config --global user.email
```

بعد تنفيذ هذه الأوامر، يجب أن يكون Git مثبتًا وأن تكون هويتك الأساسية قد تم إعدادها.

---

## 🎯 الملخص

بعد الانتهاء من هذا الإعداد، يجب أن تكون قادرًا على:

- التحقق مما إذا كان Git مثبتًا.
- تثبيت Git إذا لم يكن مثبتًا.
- معرفة إصدار Git المثبت.
- إعداد اسم المستخدم في Git.
- إعداد البريد الإلكتروني في Git.
- التحقق من هوية Git الخاصة بك.
- عرض إعدادات Git.
- فهم وظيفة الخيار `--global`.
- فهم الفرق بين الإعداد العام والإعداد المحلي.
- فهم أن إعداد هوية Git يختلف عن المصادقة مع GitHub.

بعد تثبيت Git وإعداده بشكل صحيح، تصبح جاهزًا للبدء بإنشاء المستودعات والعمل باستخدام Git.
