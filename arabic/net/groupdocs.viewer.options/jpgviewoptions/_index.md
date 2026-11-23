---
title: "خيارات عرض JPG"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يوفر خيارات لتحويل المستندات إلى صيغة JPG. للحصول على تفاصيل راجع هذه الصفحةhttps//docs.groupdocs.com/viewer/net/renderingtopngorjpeg/ وأقسامها الفرعية."
type: docs
weight: 350
url: /ar/net/groupdocs.viewer.options/jpgviewoptions/
---

## JpgViewOptions class

يوفر خيارات لتصيير المستندات إلى صيغة JPG. للحصول على تفاصيل، راجع هذه [الصفحة](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/) وأقسامها الفرعية.

```csharp
public class JpgViewOptions : ViewOptions, IMaxSizeOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [JpgViewOptions](jpgviewoptions#constructor)() | يقوم بتهيئة نسخة من الفئة [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_1)(CreatePageStream) | يقوم بتهيئة نسخة من الفئة [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_3)(IPageStreamFactory) | يقوم بتهيئة نسخة من الفئة [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_4)(string) | يقوم بتهيئة نسخة من الفئة [`JpgViewOptions`](../jpgviewoptions). |
| [JpgViewOptions](jpgviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | يقوم بتهيئة نسخة من الفئة [`JpgViewOptions`](../jpgviewoptions). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | خيارات عرض ملفات الأرشيف. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | خيارات عرض رسومات CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | يضبط الخط الافتراضي للمستند. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | خيارات عرض رسائل البريد الإلكتروني. |
| [ExtractText](../../groupdocs.viewer.options/jpgviewoptions/extracttext) { get; set; } | يُمكّن استخراج النص. |
| [Height](../../groupdocs.viewer.options/jpgviewoptions/height) { get; set; } | يضبط ارتفاع الصورة الناتجة (بالبكسل). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | خيارات عرض ملفات بيانات تخزين البريد. |
| [MaxHeight](../../groupdocs.viewer.options/jpgviewoptions/maxheight) { get; set; } | يضبط الحد الأقصى لارتفاع صورة الإخراج (بالبكسل). |
| [MaxWidth](../../groupdocs.viewer.options/jpgviewoptions/maxwidth) { get; set; } | يضبط الحد الأقصى لعرض صورة الإخراج (بالبكسل). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | خيارات عرض ملفات بيانات Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | خيارات عرض مستند PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | خيارات عرض ملفات العروض التقديمية. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | خيارات عرض ملفات إدارة المشاريع. |
| [Quality](../../groupdocs.viewer.options/jpgviewoptions/quality) { get; set; } | يضبط جودة الصورة الناتجة. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | يعطل عرض التعليقات عند تعيينه إلى `true`. بشكل افتراضي يكون `false` — جميع التعليقات تُعرض. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | يفعل عرض الصفحات المخفية. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | يفعل عرض الملاحظات والتعليقات التوضيحية لبعض الصيغ |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | خيارات عرض ملفات الجداول الإلكترونية. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | خيارات عرض ملفات النص. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | خيارات عرض ملفات Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | علامة مائية نصية تُطبق على كل صفحة. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | خيارات عرض ملفات الويب. |
| [Width](../../groupdocs.viewer.options/jpgviewoptions/width) { get; set; } | يضبط عرض الصورة الناتجة (بالبكسل). |
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
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
