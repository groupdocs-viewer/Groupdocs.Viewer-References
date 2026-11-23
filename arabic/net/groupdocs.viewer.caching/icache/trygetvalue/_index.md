---
title: "TryGetValue"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحصل على المدخل المرتبط بهذا المفتاح إذا كان موجودًا."
type: docs
weight: 30
url: /ar/net/groupdocs.viewer.caching/icache/trygetvalue/
---

## ICache.TryGetValue&lt;TEntry&gt; method

يحصل على المدخل المرتبط بهذا المفتاح إذا كان موجودًا.

```csharp
public bool TryGetValue<TEntry>(string key, out TEntry value)
```

| Parameter | الوصف |
| --- | --- |
| TEntry | نوع المدخل. |
| المفتاح | مفتاح يحدد الإدخال المطلوب. |
| value | القيمة الموجودة أو فارغ. |

### قيمة الإرجاع

```csharp
True
```

إذا تم العثور على المفتاح.

### انظر أيضًا

* interface [ICache](../../icache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
