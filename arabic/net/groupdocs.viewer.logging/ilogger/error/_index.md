---
title: "خطأ"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يكتب رسالة خطأ. رسائل سجل الأخطاء توفر معلومات حول الأحداث غير القابلة للاسترداد في تدفق التطبيق."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer.logging/ilogger/error/
---

## ILogger.Error method

يكتب رسالة خطأ. رسائل سجل الأخطاء توفر معلومات حول الأحداث غير القابلة للاسترداد في تدفق التطبيق.

```csharp
public void Error(string message, Exception exception)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| رسالة | String | رسالة الخطأ. |
| استثناء | استثناء | الاستثناء. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم الإلقاء عندما تكون *message* null. |
| ArgumentNullException | يتم الإلقاء عندما يكون *exception* null. |

### انظر أيضًا

* interface [ILogger](../../ilogger)
* namespace [GroupDocs.Viewer.Logging](../../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
