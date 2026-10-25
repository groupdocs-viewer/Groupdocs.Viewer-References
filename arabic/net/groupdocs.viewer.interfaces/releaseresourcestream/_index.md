---
title: "ReleaseResourceStream"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يطلق الدفق الذي تم إنشاؤه بواسطة الطريقة المرتبطة بـ CreateResourceStream./createresourcestream delegate."
type: docs
weight: 730
url: /ar/net/groupdocs.viewer.interfaces/releaseresourcestream/
---

## ReleaseResourceStream delegate

يطلق الدفق الذي تم إنشاؤه بواسطة الطريقة المرتبطة بـ [`CreateResourceStream`](../createresourcestream) delegate.

```csharp
public delegate void ReleaseResourceStream(int pageNumber, Resource resource, 
    Stream resourceStream);
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة. |
| المورد | المورد | مورد HTML مثل الخط أو النمط أو الصورة أو الرسومات. |
| resourceStream | Stream | الدفق الذي تم إنشاؤه بواسطة الطريقة المرتبطة بـ [`CreateResourceStream`](../createresourcestream) delegate. |

### انظر أيضًا

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
