---
title: ReleaseResourceStream
second_title: GroupDocs.Viewer لمرجع .NET API
description: يقوم بإصدار الدفق الذي تم إنشاؤه بواسطةCreateResourceStreamgroupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream طريقة .
type: docs
weight: 30
url: /ar/net/groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream/
---
## IResourceStreamFactory.ReleaseResourceStream method

يقوم بإصدار الدفق الذي تم إنشاؤه بواسطة[`CreateResourceStream`](../createresourcestream) طريقة .

```csharp
public void ReleaseResourceStream(int pageNumber, Resource resource, Stream resourceStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة. |
| resource | Resource | مورد HTML مثل الخط أو النمط أو الصورة أو الرسومات. |
| resourceStream | Stream | تم إنشاء الدفق بواسطة[`CreateResourceStream`](../createresourcestream) طريقة. |

### أنظر أيضا

* class [Resource](../../../groupdocs.viewer.results/resource)
* interface [IResourceStreamFactory](../../iresourcestreamfactory)
* مساحة الاسم [GroupDocs.Viewer.Interfaces](../../iresourcestreamfactory)
* المجسم [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
