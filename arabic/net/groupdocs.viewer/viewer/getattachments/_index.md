---
title: GetAttachments
second_title: GroupDocs.Viewer لمرجع .NET API
description: إرجاع المرفقات التي يحتوي عليها المستند.
type: docs
weight: 30
url: /ar/net/groupdocs.viewer/viewer/getattachments/
---
## GetAttachments() {#getattachments}

إرجاع المرفقات التي يحتوي عليها المستند.

```csharp
public IList<Attachment> GetAttachments()
```

### قيمة الإرجاع

المرفقات الواردة في الوثيقة.

### استثناءات

| استثناء | حالة |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤها عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | ألقيت عندما تكون كلمة المرور التي تم تحديدها غير صحيحة. |

### ملاحظات

**يتعلم أكثر**

* تعرف على المزيد حول إحضار مرفقات المستندات في C #: [كيفية الحصول على قائمة بمرفقات المستندات باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* تعرف على المزيد حول حفظ مرفقات المستندات في C #: [كيفية حفظ مرفقات المستندات باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### أنظر أيضا

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## GetAttachments(CancellationToken) {#getattachments_1}

إرجاع المرفقات التي يحتوي عليها المستند.

```csharp
public IList<Attachment> GetAttachments(CancellationToken cancellationToken)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

المرفقات الواردة في الوثيقة.

### استثناءات

| استثناء | حالة |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤها عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | ألقيت عندما تكون كلمة المرور التي تم تحديدها غير صحيحة. |

### ملاحظات

**يتعلم أكثر**

* تعرف على المزيد حول إحضار مرفقات المستندات في C #: [كيفية الحصول على قائمة بمرفقات المستندات باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* تعرف على المزيد حول حفظ مرفقات المستندات في C #: [كيفية حفظ مرفقات المستندات باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### أنظر أيضا

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->