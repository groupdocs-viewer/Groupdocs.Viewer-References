---
title: "GetResourceFilter"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يرجع سلسلة الفلتر للبحث عن مداخل الذاكرة المؤقتة التي تمثل كائنات Resourcegroupdocs.viewer.results/resource."
type: docs
weight: 60
url: /ar/net/groupdocs.viewer.caching/cachekeys/getresourcefilter/
---

## CacheKeys.GetResourceFilter method

يرجع سلسلة الفلتر للبحث عن مداخل الذاكرة المؤقتة التي تمثل كائنات [`Resource`](../../../groupdocs.viewer.results/resource).

```csharp
public static string GetResourceFilter(int pageNumber)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | عدد الصفحة. |

### قيمة الإرجاع

سلسلة الفلتر للبحث عن مداخل الذاكرة المؤقتة التي تمثل كائنات [`Resource`](../../../groupdocs.viewer.results/resource).

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم إلقاؤه عندما تكون *pageNumber* أقل أو مساوية للصفر. |

### انظر أيضًا

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
