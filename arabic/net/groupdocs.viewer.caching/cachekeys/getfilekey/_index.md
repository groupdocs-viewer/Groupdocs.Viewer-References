---
title: "GetFileKey"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يعيد معرفًا فريدًا لمدخل الذاكرة المؤقتة الذي يمثل الملف."
type: docs
weight: 40
url: /ar/net/groupdocs.viewer.caching/cachekeys/getfilekey/
---

## CacheKeys.GetFileKey method

يعيد معرفًا فريدًا لمدخل الذاكرة المؤقتة الذي يمثل الملف.

```csharp
public static string GetFileKey(string extension)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| extension | String | لاحقة اسم الملف (بما في ذلك النقطة \".\") مثال: \".doc\". |

### قيمة الإرجاع

معرف فريد لمدخل الذاكرة المؤقتة الذي يمثل الملف.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما تكون *extension* فارغة أو null. |

### انظر أيضًا

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
