---
title: "PdfOptions"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحتوي على خيارات لتصيير مستندات PDF. للحصول على التفاصيل راجع الوثائقhttps//docs.groupdocs.com/viewer/net/renderpdfdocuments/."
type: docs
weight: 410
url: /ar/net/groupdocs.viewer.options/pdfoptions/
---

## PdfOptions class

يحتوي على خيارات لتصيير مستندات PDF. للحصول على تفاصيل، راجع [الوثائق](https://docs.groupdocs.com/viewer/net/render-pdf-documents/).

```csharp
public class PdfOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfOptions](pdfoptions)() | يُنشئ مثيلاً جديدًا للفئة [`PdfOptions`](../pdfoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DisableCharsGrouping](../../groupdocs.viewer.options/pdfoptions/disablecharsgrouping) { get; set; } | يعطل تجميع الرموز لتحديد موضع الرموز بدقة أثناء تصيير الصفحة. |
| [DisableCopyProtection](../../groupdocs.viewer.options/pdfoptions/disablecopyprotection) { get; set; } | يعطل حماية نسخ المحتوى عند تصيير إلى HTML. |
| [DisableFontLicenseVerifications](../../groupdocs.viewer.options/pdfoptions/disablefontlicenseverifications) { get; set; } | يعطل أي قيود ترخيص لجميع الخطوط في مستند XPS/OXPS الحالي. |
| [EnableFontHinting](../../groupdocs.viewer.options/pdfoptions/enablefonthinting) { get; set; } | يفعل توجيه الخط. |
| [EnableLayeredRendering](../../groupdocs.viewer.options/pdfoptions/enablelayeredrendering) { get; set; } | يفعل تصيير النص والرسومات بترتيب Z الأصلي لمستند PDF عند تصيير إلى HTML. |
| [FixedLayout](../../groupdocs.viewer.options/pdfoptions/fixedlayout) { get; set; } | يفعل تصيير مستندات PDF و EPUB إلى HTML بتخطيط ثابت. |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptions/imagequality) { get; set; } | يضبط جودة صورة الإخراج للموارد الصورة عند تصيير إلى HTML. الجودة الافتراضية هي `Low`. |
| [RenderOriginalPageSize](../../groupdocs.viewer.options/pdfoptions/renderoriginalpagesize) { get; set; } | يضبط حجم صفحة الإخراج ليكون نفس حجم صفحة مستند PDF المصدر. |
| [RenderTextAsImage](../../groupdocs.viewer.options/pdfoptions/rendertextasimage) { get; set; } | يفعل تصيير النصوص في ملفات PDF كصورة في إخراج HTML. |
| [WrapImagesInSvg](../../groupdocs.viewer.options/pdfoptions/wrapimagesinsvg) { get; set; } | يفعل تغليف كل صورة في مستند HTML الناتج بوسم SVG لتحسين جودة الإخراج. |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
