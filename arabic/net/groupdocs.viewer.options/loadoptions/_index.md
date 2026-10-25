---
title: "LoadOptions"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحتوي على الخيارات المستخدمة لفتح الملف. للحصول على تفاصيل راجع هذه الصفحةhttps//docs.groupdocs.com/viewer/net/loading/ وأقسامها الفرعية."
type: docs
weight: 360
url: /ar/net/groupdocs.viewer.options/loadoptions/
---

## LoadOptions class

يحتوي على خيارات تُستخدم لفتح الملف. للحصول على تفاصيل، راجع هذه [الصفحة](https://docs.groupdocs.com/viewer/net/loading/) وأقسامها الفرعية.

```csharp
public class LoadOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | يقوم بتهيئة نسخة من الفئة [`LoadOptions`](../loadoptions). |
| [LoadOptions](loadoptions#constructor_1)(FileType) | يقوم بتهيئة نسخة من الفئة [`LoadOptions`](../loadoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DetectEncoding](../../groupdocs.viewer.options/loadoptions/detectencoding) { get; set; } | يفعل اكتشاف الترميز للملفات [`TXT`](../../groupdocs.viewer/filetype/txt)، [`CSV`](../../groupdocs.viewer/filetype/csv) و[`TSV`](../../groupdocs.viewer/filetype/tsv). |
| [Encoding](../../groupdocs.viewer.options/loadoptions/encoding) { get; set; } | يضبط الترميز المستخدم عند فتح الملفات النصية أو رسائل البريد الإلكتروني مثل [`CSV`](../../groupdocs.viewer/filetype/csv)، [`TXT`](../../groupdocs.viewer/filetype/txt) و[`MSG`](../../groupdocs.viewer/filetype/msg). القيمة الافتراضية هي UTF8. |
| [FileType](../../groupdocs.viewer.options/loadoptions/filetype) { get; set; } | يضبط نوع الملف المراد فتحه. |
| [Password](../../groupdocs.viewer.options/loadoptions/password) { get; set; } | يضبط كلمة المرور لفتح الملف المشفر. |
| [ResourceLoadingTimeout](../../groupdocs.viewer.options/loadoptions/resourceloadingtimeout) { get; set; } | يضبط مهلة تحميل الموارد الخارجية. |
| [SkipExternalResources](../../groupdocs.viewer.options/loadoptions/skipexternalresources) { get; set; } | يعطل تحميل جميع الموارد الخارجية مثل الصور باستثناء [`WhitelistedResources`](./whitelistedresources). |
| [TryRepair](../../groupdocs.viewer.options/loadoptions/tryrepair) { get; set; } | عند التفعيل، يحاول GroupDocs.Viewer إصلاح الفساد الهيكلي في مستندات PDF. القيمة الافتراضية هي `false`. |
| [WhitelistedResources](../../groupdocs.viewer.options/loadoptions/whitelistedresources) { get; set; } | قائمة أجزاء URL المقابلة للموارد الخارجية التي يجب تحميلها عندما يتم ضبط [`SkipExternalResources`](./skipexternalresources) على `true`. |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
