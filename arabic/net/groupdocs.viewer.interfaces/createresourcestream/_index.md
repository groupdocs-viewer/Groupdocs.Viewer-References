---
title: CreateResourceStream
second_title: GroupDocs.Viewer لمرجع .NET API
description: يمثل الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات مورد HTML.
type: docs
weight: 140
url: /ar/net/groupdocs.viewer.interfaces/createresourcestream/
---
## CreateResourceStream delegate

يمثل الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات مورد HTML.

```csharp
public delegate Stream CreateResourceStream(int pageNumber, Resource resource);
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة. |
| resource | Resource | مورد HTML مثل الخط أو النمط أو الصورة أو الرسومات. |

### قيمة الإرجاع

الدفق المستخدم لكتابة بيانات مورد HTML.

### أنظر أيضا

* class [Resource](../../groupdocs.viewer.results/resource)
* مساحة الاسم [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* المجسم [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->