---
title: "ICache"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحدد الطرق المطلوبة لتخزين المستند المعروض وموارد المستند في الذاكرة المؤقتة."
type: docs
weight: 1000
url: /ar/net/groupdocs.viewer.caching/icache/
---

## ICache interface

يحدد الطرق المطلوبة لتخزين المستند المعروض وموارد المستند في الذاكرة المؤقتة.

```csharp
public interface ICache
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/icache/getkeys)(string) | يعيد جميع المفاتيح التي تطابق الفلتر. |
| [Set](../../groupdocs.viewer.caching/icache/set)(string, object) | يدرج مدخلًا في الذاكرة المؤقتة. |
| [TryGetValue&lt;TEntry&gt;](../../groupdocs.viewer.caching/icache/trygetvalue)(string, out TEntry) | يحصل على المدخل المرتبط بهذا المفتاح إذا كان موجودًا. |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
