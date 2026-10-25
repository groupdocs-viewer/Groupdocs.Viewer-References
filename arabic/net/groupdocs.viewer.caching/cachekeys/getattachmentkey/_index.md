---
title: "GetAttachmentKey"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يعيد معرفًا فريدًا لمدخل الذاكرة المؤقتة الذي يمثل ملف المرفق."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.caching/cachekeys/getattachmentkey/
---

## CacheKeys.GetAttachmentKey method

يعيد معرفًا فريدًا لمدخل الذاكرة المؤقتة الذي يمثل ملف المرفق.

```csharp
public static string GetAttachmentKey(string attachmentId)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| attachmentId | String | معرف فريد (في سياق ملف واحد) للمرفق. |

### قيمة الإرجاع

معرف فريد لمدخل الذاكرة المؤقتة الذي يمثل ملف المرفق.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم إلقاؤه عندما يكون *attachmentId* null أو فارغ. |

### انظر أيضًا

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
