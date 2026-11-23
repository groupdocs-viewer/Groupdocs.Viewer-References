---
title: "CreateResourceStream"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يمثل الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات مورد HTML للإخراج."
type: docs
weight: 720
url: /ar/net/groupdocs.viewer.interfaces/createresourcestream/
---

## CreateResourceStream delegate

يمثل الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات مورد HTML للإخراج.

```csharp
public delegate Stream CreateResourceStream(int pageNumber, Resource resource);
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة. |
| المورد | المورد | مورد HTML مثل الخط أو النمط أو الصورة أو الرسومات. |

### قيمة الإرجاع

التدفق المستخدم لكتابة بيانات مورد HTML الناتج.

### انظر أيضًا

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
