---
title: "FileCache"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يمثل ذاكرة مؤقتة محلية على القرص."
type: docs
weight: 990
url: /ar/net/groupdocs.viewer.caching/filecache/
---

## FileCache class

يمثل ذاكرة مؤقتة محلية على القرص.

```csharp
public class FileCache : ICache
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FileCache](filecache#constructor)(string) | ينشئ نسخة جديدة من الفئة [`FileCache`](../filecache). |
| [FileCache](filecache#constructor_1)(string, string) | ينشئ نسخة جديدة من الفئة [`FileCache`](../filecache). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CachePath](../../groupdocs.viewer.caching/filecache/cachepath) { get; } | المسار النسبي أو المطلق لمجلد الذاكرة المؤقتة. |
| [CacheSubFolder](../../groupdocs.viewer.caching/filecache/cachesubfolder) { get; } | المجلد الفرعي لإضافته إلى [`CachePath`](./cachepath). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/filecache/getkeys)(string) | يعيد جميع أسماء الملفات التي تحتوي على الفلتر في اسم الملف. |
| [Set](../../groupdocs.viewer.caching/filecache/set)(string, object) | يسلسل البيانات إلى القرص المحلي. |
| [TryGetValue&lt;T&gt;](../../groupdocs.viewer.caching/filecache/trygetvalue)(string, out T) | يفك تسلسل البيانات المرتبطة بهذا المفتاح إذا كانت موجودة. |

### انظر أيضًا

* interface [ICache](../icache)
* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
