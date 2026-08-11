# ⚔️ Git Cherry Pick Conflicts

## 🌐 English

A cherry-pick conflict occurs when Git cannot automatically apply the changes from a commit to the current branch.

This usually happens when the same parts of a file have changed differently on the two branches.

---

## 🔹 Start a Cherry Pick

```bash
git cherry-pick commit-hash
```

If Git cannot apply the changes automatically, it will stop and report a conflict.

---

## 🔹 Check the Conflict

Run:

```bash
git status
```

Git will show the files that contain conflicts.

---

## 🔹 Resolve the Conflict

Open the conflicted files and look for conflict markers:

```text
<<<<<<< HEAD
Current branch changes
=======
Cherry-picked changes
>>>>>>> commit-hash
```

Choose the correct changes or combine them.

Then remove the conflict markers.

---

## 🔹 Stage the Resolved Files

After resolving the conflicts:

```bash
git add .
```

---

## 🔹 Continue Cherry Pick

Continue the operation:

```bash
git cherry-pick --continue
```

Git will complete the cherry-pick operation.

---

## 🔹 Abort the Operation

If you do not want to continue:

```bash
git cherry-pick --abort
```

This cancels the current cherry-pick operation.

---

## 🔄 Complete Conflict Workflow

A typical workflow looks like this:

```bash
git cherry-pick commit-hash
git status
```

Resolve the conflicts, then:

```bash
git add .
git cherry-pick --continue
```

Or cancel the operation:

```bash
git cherry-pick --abort
```

---

## ⚠️ Important Note

Always review the resolved files before continuing.

You should make sure that the final content is correct and that no unwanted changes remain.

---

## 📝 Summary

```bash
git status
git add .
git cherry-pick --continue
```

To cancel:

```bash
git cherry-pick --abort
```

Cherry-pick conflicts require you to manually resolve conflicting changes before Git can complete the operation.

---

# 🇵🇸 العربية

# ⚔️ Git Cherry Pick Conflicts

## العربية

يحدث تعارض أثناء Cherry Pick عندما لا يستطيع Git تطبيق التغييرات الموجودة في Commit تلقائيًا على الفرع الحالي.

يحدث ذلك عادةً عندما تكون الأجزاء نفسها من أحد الملفات قد تغيرت بطريقة مختلفة في الفرعين.

---

## 🔹 بدء عملية Cherry Pick

```bash
git cherry-pick commit-hash
```

إذا لم يتمكن Git من تطبيق التغييرات تلقائيًا، فسيتوقف ويعرض وجود تعارض.

---

## 🔹 التحقق من التعارض

نفذ:

```bash
git status
```

سيعرض Git الملفات التي تحتوي على تعارضات.

---

## 🔹 حل التعارض

افتح الملفات التي تحتوي على تعارض وابحث عن علامات التعارض:

```text
<<<<<<< HEAD
Current branch changes
=======
Cherry-picked changes
>>>>>>> commit-hash
```

اختر التغييرات الصحيحة أو ادمج بينها.

ثم احذف علامات التعارض.

---

## 🔹 إضافة الملفات التي تم حلها إلى Staging

بعد حل التعارضات:

```bash
git add .
```

---

## 🔹 متابعة Cherry Pick

تابع العملية باستخدام:

```bash
git cherry-pick --continue
```

سيقوم Git بإكمال عملية Cherry Pick.

---

## 🔹 إلغاء العملية

إذا كنت لا تريد المتابعة:

```bash
git cherry-pick --abort
```

يقوم هذا بإلغاء عملية Cherry Pick الحالية.

---

## 🔄 سير العمل الكامل عند حدوث تعارض

يمكن أن يكون سير العمل المعتاد:

```bash
git cherry-pick commit-hash
git status
```

قم بحل التعارضات، ثم:

```bash
git add .
git cherry-pick --continue
```

أو قم بإلغاء العملية:

```bash
git cherry-pick --abort
```

---

## ⚠️ ملاحظة مهمة

راجع الملفات التي قمت بحل التعارضات فيها قبل متابعة العملية.

تأكد من أن المحتوى النهائي صحيح وأنه لا توجد تغييرات غير مرغوبة.

---

## 📝 الخلاصة

```bash
git status
git add .
git cherry-pick --continue
```

ولإلغاء العملية:

```bash
git cherry-pick --abort
```

تحتاج تعارضات Cherry Pick إلى حل التغييرات المتعارضة يدويًا قبل أن يتمكن Git من إكمال العملية.
