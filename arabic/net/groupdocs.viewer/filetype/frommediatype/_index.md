---
title: "FromMediaType"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يُطابق نوع وسائط الملف إلى نوع الملف مثال: application/pdf سيُطابق إلى PDFgroupdocs.viewer/filetype/pdf."
type: docs
weight: 1990
url: /ar/net/groupdocs.viewer/filetype/frommediatype/
---

## FileType.FromMediaType method

يُطابق نوع وسائط الملف إلى نوع الملف مثال: 'application/pdf' سيُطابق إلى [`PDF`](../pdf).

```csharp
public static FileType FromMediaType(string mediaType)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| mediaType | String | نوع وسائط الملف مثال: application/pdf. |

### قيمة الإرجاع

يرجع نوع الوسائط المقابل عند العثور عليه، وإلا يرجع نوع الملف الافتراضي [`Unknown`](../unknown).

### انظر أيضًا

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
