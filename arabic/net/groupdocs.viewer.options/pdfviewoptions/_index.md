---
title: "PdfViewOptions"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحتوي على خيارات لتصيير المستندات إلى تنسيق PDF. لمزيد من التفاصيل راجع الوثائقhttps//docs.groupdocs.com/viewer/net/renderingtopdf/."
type: docs
weight: 420
url: /ar/net/groupdocs.viewer.options/pdfviewoptions/
---

## PdfViewOptions class

يحتوي على خيارات لتصيير المستندات إلى صيغة PDF. للحصول على تفاصيل، راجع [الوثائق](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

```csharp
public class PdfViewOptions : ViewOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | ينشئ مثيلاً من الفئة [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | ينشئ مثيلاً من الفئة [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | ينشئ مثيلاً من الفئة [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | ينشئ مثيلاً من الفئة [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | ينشئ مثيلاً من الفئة [`PdfViewOptions`](../pdfviewoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | خيارات عرض ملفات الأرشيف. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | خيارات عرض رسومات CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | يضبط الخط الافتراضي للمستند. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | خيارات عرض رسائل البريد الإلكتروني. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | يضبط ارتفاع الصورة الناتجة (بالبكسل). |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | يضبط الحد الأقصى لارتفاع صورة الإخراج (بالبكسل). |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | يضبط الحد الأقصى لعرض صورة الإخراج (بالبكسل). |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | يضبط عرض صورة الإخراج (بالبكسل). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | خيارات عرض ملفات بيانات تخزين البريد. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | خيارات عرض ملفات بيانات Microsoft Outlook. |
| [PdfOptimizationOptions](../../groupdocs.viewer.options/pdfviewoptions/pdfoptimizationoptions) { get; set; } | يقلل حجم ملف PDF الناتج بتطبيق تقنيات تحسين مع خيارات مختلفة. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | خيارات عرض مستند PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | خيارات عرض ملفات العروض التقديمية. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | خيارات عرض ملفات إدارة المشاريع. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | يعطل عرض التعليقات عند تعيينه إلى `true`. بشكل افتراضي يكون `false` — جميع التعليقات تُعرض. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | يفعل عرض الصفحات المخفية. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | يفعل عرض الملاحظات والتعليقات التوضيحية لبعض الصيغ |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | يضبط خيارات أمان مستند PDF الناتج. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | خيارات عرض ملفات الجداول الإلكترونية. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | خيارات عرض ملفات النص. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | خيارات عرض ملفات Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | علامة مائية نصية تُطبق على كل صفحة. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | خيارات عرض ملفات الويب. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | خيارات عرض ملفات معالجة النصوص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | يطبق الدوران في اتجاه عقارب الساعة على الصفحة. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | دوران الصفحة. |

### انظر أيضًا

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
