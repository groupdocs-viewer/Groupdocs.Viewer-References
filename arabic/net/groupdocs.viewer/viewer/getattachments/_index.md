---
title: "GetAttachments"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يرجع المرفقات الموجودة في المستند."
type: docs
weight: 40
url: /ar/net/groupdocs.viewer/viewer/getattachments/
---

## GetAttachments() {#getattachments}

يرجع المرفقات الموجودة في المستند.

```csharp
public IList<Attachment> GetAttachments()
```

### قيمة الإرجاع

المرفقات الموجودة في المستند.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤه عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | يتم إلقاؤه عندما تكون كلمة المرور المحددة غير صحيحة. |

### ملاحظات

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### انظر أيضًا

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## GetAttachments(CancellationToken) {#getattachments_1}

يرجع المرفقات الموجودة في المستند.

```csharp
public IList<Attachment> GetAttachments(CancellationToken cancellationToken)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

المرفقات الموجودة في المستند.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤه عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | يتم إلقاؤه عندما تكون كلمة المرور المحددة غير صحيحة. |

### ملاحظات

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### انظر أيضًا

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
