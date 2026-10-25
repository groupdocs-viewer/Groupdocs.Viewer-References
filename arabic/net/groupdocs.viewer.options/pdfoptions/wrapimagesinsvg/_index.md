---
title: "WrapImagesInSvg"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يفعل تغليف كل صورة في مستند HTML الناتج بوسم SVG لتحسين جودة الإخراج."
type: docs
weight: 110
url: /ar/net/groupdocs.viewer.options/pdfoptions/wrapimagesinsvg/
---

## PdfOptions.WrapImagesInSvg property

يفعل تغليف كل صورة في مستند HTML الناتج بوسم SVG لتحسين جودة الإخراج.

```csharp
public bool WrapImagesInSvg { get; set; }
```

### ملاحظات

بشكل افتراضي، عند تحويل ملفات PDF وتنسيق الصفحات إلى HTML، يتم عرض جميع الصور كصورة PNG واحدة. تُستخدم صورة PNG الناتجة كخلفية لمستند HTML الناتج.

هذا الخيار متاح عند تحويل [صيغ ملفات PDF وتنسيق الصفحات](https://docs.groupdocs.com/viewer/net/supported-document-formats/#pdf-and-page-layout-file-formats) إلى HTML مع الموارد المدمجة والخارجية. يتيح تغليف كل صورة في مستند HTML الناتج بوسم SVG. القيمة الافتراضية هي `false`.

للحصول على مثال شفرة، راجع [التوثيق](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#enclose-images-in-svg-when-rendering-pdf-and-page-layout-files).

### انظر أيضًا

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
