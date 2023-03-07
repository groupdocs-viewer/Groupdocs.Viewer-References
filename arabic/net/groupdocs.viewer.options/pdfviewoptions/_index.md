---
title: PdfViewOptions
second_title: GroupDocs.Viewer لمرجع .NET API
description: يوفر خيارات لعرض المستندات بتنسيق PDF .
type: docs
weight: 420
url: /ar/net/groupdocs.viewer.options/pdfviewoptions/
---
## PdfViewOptions class

يوفر خيارات لعرض المستندات بتنسيق PDF .

```csharp
public class PdfViewOptions : ViewOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | تهيئة مثيل جديد لـ[`PdfViewOptions`](../pdfviewoptions) فئة . |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | تهيئة مثيل جديد لـ[`PdfViewOptions`](../pdfviewoptions) فئة . |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | تهيئة مثيل جديد لـ[`PdfViewOptions`](../pdfviewoptions) فئة . |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | تهيئة مثيل جديد لـ[`PdfViewOptions`](../pdfviewoptions) فئة . |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | تهيئة مثيل جديد لـ[`PdfViewOptions`](../pdfviewoptions) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | خيارات عرض ملفات الأرشيف . |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | خيارات عرض رسم CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | الخط الافتراضي الذي سيتم استخدامه عندما يتعذر العثور على خط معين مستخدم في المستند. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | خيارات عرض رسائل البريد الإلكتروني . |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | ارتفاع صورة الإخراج بالبكسل. (عند تحويل صورة واحدة إلى HTML فقط) |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | أقصى ارتفاع لصورة الإخراج بالبكسل. (عند تحويل صورة واحدة إلى HTML فقط) |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | أقصى عرض لصورة الإخراج بالبكسل. (عند تحويل صورة واحدة إلى HTML فقط) |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | عرض صورة الإخراج بالبكسل. (عند تحويل صورة واحدة إلى HTML فقط) |
| [JpgQuality](../../groupdocs.viewer.options/pdfviewoptions/jpgquality) { get; set; } | جودة صور JPG التي يحتوي عليها مستند PDF الناتج ؛ القيم الصالحة بين 1 و 100 ؛ القيمة الافتراضية هي 90. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | خيارات عرض ملفات بيانات تخزين البريد . |
| [Optimize](../../groupdocs.viewer.options/pdfviewoptions/optimize) { get; set; } | تقليل حجم ملف الإخراج عن طريق استبعاد الخطوط الشائعة مثل Times New Roman و Arial ، وتطبيق تقنيات التحسين الأخرى. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | خيارات عرض ملفات بيانات MS Outlook . |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | خيارات عرض مستندات PDF . |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | خيارات عرض مستندات معالجة العرض التقديمي. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | خيارات عرض ملفات إدارة المشروع. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | تمكين عرض التعليقات . |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | تمكين عرض الصفحات المخفية. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | تمكين عرض الملاحظات . |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | خيارات أمان مستند PDF الناتج. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | خيارات عرض ملفات جدول البيانات. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | تقسيم الملفات النصية إلى خيارات الصفحات. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | خيارات عرض مستندات معالجة ملفات Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | العلامة المائية النصية المطبقة على كل صفحة. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | تتيح لك خيارات العرض هذه تخصيص مظهر الناتج HTML / PDF / PNG / JPEG عند عرض مستندات الويب. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | تتيح لك خيارات العرض هذه تخصيص مظهر الناتج HTML / PDF / PNG / JPEG عند عرض مستندات Word. |

## طُرق

| اسم | وصف |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | لتطبيق استدارة في اتجاه عقارب الساعة على الصفحة. |

## مجالات

| اسم | وصف |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | تدوير الصفحة . |

### أنظر أيضا

* class [ViewOptions](../viewoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* المجسم [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
