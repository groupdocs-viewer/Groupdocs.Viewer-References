---
title: "FileLogger"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يكتب رسائل السجل إلى الملف."
type: docs
weight: 660
url: /ar/net/groupdocs.viewer.logging/filelogger/
---

## FileLogger class

يكتب رسائل السجل إلى الملف.

```csharp
public class FileLogger : ILogger
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FileLogger](filelogger)(string) | إنشاء مسجل إلى ملف. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Error](../../groupdocs.viewer.logging/filelogger/error)(string, Exception) | يكتب رسالة خطأ إلى وحدة التحكم. رسائل سجل الأخطاء توفر معلومات حول الأحداث غير القابلة للاسترداد في تدفق التطبيق. |
| [Trace](../../groupdocs.viewer.logging/filelogger/trace)(string) | يكتب رسالة تتبع إلى وحدة التحكم. رسائل سجل التتبع توفر معلومات عامة مفيدة حول تدفق التطبيق. |
| [Warning](../../groupdocs.viewer.logging/filelogger/warning)(string) | يكتب رسالة تحذير إلى وحدة التحكم. رسائل سجل التحذير توفر معلومات حول الأحداث غير المتوقعة والقابلة للاسترداد في تدفق التطبيق. |

### انظر أيضًا

* interface [ILogger](../ilogger)
* namespace [GroupDocs.Viewer.Logging](../../groupdocs.viewer.logging)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
