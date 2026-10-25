---
title: "ReleaseResourceStream"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يفرج عن الدفق الذي تم إنشاؤه بواسطة طريقة CreateResourceStreamgroupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream."
type: docs
weight: 30
url: /ar/net/groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream/
---

## IResourceStreamFactory.ReleaseResourceStream method

يفرج عن الدفق الذي تم إنشاؤه بواسطة طريقة [`CreateResourceStream`](../createresourcestream).

```csharp
public void ReleaseResourceStream(int pageNumber, Resource resource, Stream resourceStream)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة. |
| المورد | المورد | مورد HTML مثل الخط، النمط، الصورة أو الرسومات. |
| resourceStream | Stream | الدفق الذي تم إنشاؤه بواسطة طريقة [`CreateResourceStream`](../createresourcestream). |

### انظر أيضًا

* class [Resource](../../../groupdocs.viewer.results/resource)
* interface [IResourceStreamFactory](../../iresourcestreamfactory)
* namespace [GroupDocs.Viewer.Interfaces](../../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
