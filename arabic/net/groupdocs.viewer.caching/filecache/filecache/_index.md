---
title: "FileCache"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "ينشئ نسخة جديدة من الفئة FileCachegroupdocs.viewer.caching/filecache."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.caching/filecache/filecache/
---

## FileCache(string) {#constructor}

ينشئ نسخة جديدة من الفئة [`FileCache`](../../filecache).

```csharp
public FileCache(string cachePath)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| cachePath | String | المسار النسبي أو المطلق حيث سيتم تخزين التخزين المؤقت للمستند. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *cachePath* فارغًا. |

### انظر أيضًا

* class [FileCache](../../filecache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

---

## FileCache(string, string) {#constructor_1}

ينشئ نسخة جديدة من الفئة [`FileCache`](../../filecache).

```csharp
public FileCache(string cachePath, string cacheSubFolder)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| cachePath | String | المسار النسبي أو المطلق حيث سيتم تخزين التخزين المؤقت للمستند. |
| cacheSubFolder | String | المجلد الفرعي لإضافته إلى *cachePath*. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُرمى عندما يكون *cachePath* فارغًا. |
| ArgumentNullException | يُرمى عندما يكون *cacheSubFolder* فارغًا. |

### انظر أيضًا

* class [FileCache](../../filecache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
