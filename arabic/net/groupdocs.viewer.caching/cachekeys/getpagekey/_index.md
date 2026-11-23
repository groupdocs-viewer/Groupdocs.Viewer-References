---
title: "GetPageKey"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يعيد معرفًا فريدًا لمدخل الذاكرة المؤقتة الذي يمثل ملف الصفحة."
type: docs
weight: 50
url: /ar/net/groupdocs.viewer.caching/cachekeys/getpagekey/
---

## CacheKeys.GetPageKey method

يعيد معرفًا فريدًا لمدخل الذاكرة المؤقتة الذي يمثل ملف الصفحة.

```csharp
public static string GetPageKey(int pageNumber, string extension)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة. |
| extension | String | لاحقة اسم الملف (بما في ذلك النقطة \".\") مثال: \".doc\". |

### قيمة الإرجاع

معرف فريد لمدخل الذاكرة المؤقتة الذي يمثل ملف الصفحة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم إلقاؤه عندما تكون *pageNumber* أقل أو مساوية للصفر. |
| ArgumentException | يُرمى عندما تكون *extension* فارغة أو null. |

### انظر أيضًا

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
