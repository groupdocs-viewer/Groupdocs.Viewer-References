---
title: "ReleasePageStream"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يطلق التدفق الذي تم إنشاؤه بواسطة الطريقة المرتبطة بـ CreatePageStream./createpagestream delegate."
type: docs
weight: 710
url: /ar/net/groupdocs.viewer.interfaces/releasepagestream/
---

## ReleasePageStream delegate

يطلق التدفق الذي تم إنشاؤه بواسطة الطريقة المرتبطة بـ [`CreatePageStream`](../createpagestream) delegate.

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة. |
| pageStream | Stream | التدفق الذي أنشأته الطريقة المرتبطة بـ [`CreatePageStream`](../createpagestream) delegate. |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
