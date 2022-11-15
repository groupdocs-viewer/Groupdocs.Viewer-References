---
title: ICache
second_title: GroupDocs.Viewer لمرجع .NET API
description: يحدد الطرق المطلوبة لتخزين المستندات المقدمة وموارد المستندات сache.
type: docs
weight: 30
url: /ar/net/groupdocs.viewer.caching/icache/
---
## ICache interface

يحدد الطرق المطلوبة لتخزين المستندات المقدمة وموارد المستندات сache.

```csharp
public interface ICache
```

## طُرق

| اسم | وصف |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/icache/getkeys)(string) | إرجاع جميع المفاتيح المطابقة لعامل التصفية. |
| [Set](../../groupdocs.viewer.caching/icache/set)(string, object) | يقوم بإدراج إدخال ذاكرة التخزين المؤقت في ذاكرة التخزين المؤقت . |
| [TryGetValue&lt;TEntry&gt;](../../groupdocs.viewer.caching/icache/trygetvalue)(string, out TEntry) | يحصل على الإدخال المرتبط بهذا المفتاح إذا كان موجودًا. |

### أنظر أيضا

* مساحة الاسم [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* المجسم [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->