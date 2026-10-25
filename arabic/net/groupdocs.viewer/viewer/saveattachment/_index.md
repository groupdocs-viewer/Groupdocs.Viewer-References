---
title: "SaveAttachment"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحفظ ملف المرفق إلى تدفق الوجهة."
type: docs
weight: 70
url: /ar/net/groupdocs.viewer/viewer/saveattachment/
---

## SaveAttachment(Attachment, Stream, CancellationToken) {#saveattachment_1}

يحفظ ملف المرفق إلى تدفق *الوجهة*.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination, 
    CancellationToken cancellationToken)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| المرفق | Attachment | المرفق. |
| الوجهة | تدفق | التدفق القابل للكتابة. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم رميه عندما يكون *attachment* هو `null`. |
| ArgumentNullException | يتم رميه عندما يكون *destination* هو `null`. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤه عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | يتم إلقاؤه عندما تكون كلمة المرور المحددة غير صحيحة. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | يتم رميه عندما لا يمكن العثور على المرفق. |

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

## SaveAttachment(Attachment, Stream) {#saveattachment}

يحفظ ملف المرفق إلى تدفق *الوجهة*.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| المرفق | Attachment | المرفق. |
| الوجهة | تدفق | التدفق القابل للكتابة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم رميه عندما يكون *attachment* هو `null`. |
| ArgumentNullException | يتم رميه عندما يكون *destination* هو `null`. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | يتم إلقاؤه عندما تكون كلمة المرور مطلوبة لفتح المستند. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | يتم إلقاؤه عندما تكون كلمة المرور المحددة غير صحيحة. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | يتم رميه عندما لا يمكن العثور على المرفق. |

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
