---
title: View
second_title: GroupDocs.Viewer لمرجع .NET API
description: إنشاء عرض لكافة صفحات المستند.
type: docs
weight: 70
url: /ar/net/groupdocs.viewer/viewer/view/
---
## View(ViewOptions) {#view}

إنشاء عرض لكافة صفحات المستند.

```csharp
public void View(ViewOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| options | ViewOptions | خيارات العرض. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*options* باطل. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤها عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | ألقيت عندما تكون كلمة المرور التي تم تحديدها غير صحيحة. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | تم إلقاؤه عند تعذر العثور على المرفق. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول خيارات العرض المختلفة باتباع هذا الدليل: [كيفية تخصيص إخراج عرض المستند باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### أنظر أيضا

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

إنشاء عرض لكافة صفحات المستند.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| options | ViewOptions | خيارات العرض. |
| cancellationToken | CancellationToken | رمز الإلغاء لإرسال طلب لإلغاء عملية العرض الحالية. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*options* باطل. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤها عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | ألقيت عندما تكون كلمة المرور التي تم تحديدها غير صحيحة. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | تم إلقاؤه عند تعذر العثور على المرفق. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول خيارات العرض المختلفة باتباع هذا الدليل: [كيفية تخصيص إخراج عرض المستند باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### أنظر أيضا

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

إنشاء عرض لصفحات وثيقة معينة.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| options | ViewOptions | خيارات العرض. |
| pageNumbers | Int32[] | أرقام الصفحات لعرضها. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*options* باطل. |
| ArgumentNullException | عندما ألقيت*pageNumbers* باطل. |
| ArgumentException | عندما ألقيت*pageNumbers* فارغ. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤها عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | ألقيت عندما تكون كلمة المرور التي تم تحديدها غير صحيحة. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | تم إلقاؤه عند تعذر العثور على المرفق. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول خيارات العرض المختلفة باتباع هذا الدليل: [كيفية تخصيص إخراج عرض المستند باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### أنظر أيضا

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

إنشاء عرض لصفحات وثيقة معينة.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| options | ViewOptions | خيارات العرض. |
| pageNumbers | CancellationToken | أرقام الصفحات لعرضها. |
| cancellationToken | Int32[] | رمز الإلغاء لإلغاء المعالجة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*options* باطل. |
| ArgumentNullException | عندما ألقيت*pageNumbers* باطل. |
| ArgumentException | عندما ألقيت*pageNumbers* فارغ. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤها عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | ألقيت عندما تكون كلمة المرور التي تم تحديدها غير صحيحة. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | تم إلقاؤه عند تعذر العثور على المرفق. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول خيارات العرض المختلفة باتباع هذا الدليل: [كيفية تخصيص إخراج عرض المستند باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### أنظر أيضا

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
