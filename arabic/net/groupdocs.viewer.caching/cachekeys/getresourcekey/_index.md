---
title: "GetResourceKey"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يرجع معرفًا فريدًا لمدخل الذاكرة المؤقتة الذي يمثل كائن Resourcegroupdocs.viewer.results/resource."
type: docs
weight: 70
url: /ar/net/groupdocs.viewer.caching/cachekeys/getresourcekey/
---

## CacheKeys.GetResourceKey method

يرجع معرفًا فريدًا لمدخل الذاكرة المؤقتة الذي يمثل كائن [`Resource`](../../../groupdocs.viewer.results/resource).

```csharp
public static string GetResourceKey(int pageNumber, Resource resource)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة. |
| المورد | المورد | مورد HTML. |

### قيمة الإرجاع

معرف فريد لمدخل الذاكرة المؤقتة الذي يمثل كائن [`Resource`](../../../groupdocs.viewer.results/resource).

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم إلقاؤه عندما تكون *pageNumber* أقل أو مساوية للصفر. |
| ArgumentNullException | يتم إلقاؤه عندما يكون *resource* null. |

### انظر أيضًا

* class [Resource](../../../groupdocs.viewer.results/resource)
* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
