---
title: "ViewInfoOptions"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحتوي على خيارات لاسترجاع معلومات حول العرض."
type: docs
weight: 580
url: /ar/net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

يحتوي على خيارات لاسترجاع معلومات حول العرض.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | خيارات عرض ملفات الأرشيف. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | خيارات عرض رسومات CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | يضبط الخط الافتراضي للمستند. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | خيارات عرض رسائل البريد الإلكتروني. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | يُمكّن استخراج النص. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | ارتفاع الصورة الناتجة (بالبكسل، لتصيير إلى PNG/JPG فقط). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | خيارات عرض ملفات بيانات تخزين البريد. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | يضبط الحد الأقصى لارتفاع الصورة الناتجة (بالبكسل، لتصيير إلى PNG/JPG فقط). |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | يضبط الحد الأقصى لعرض الصورة الناتجة (بالبكسل، لتصيير إلى PNG/JPG فقط). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | خيارات عرض ملفات بيانات Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | خيارات عرض مستند PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | خيارات عرض ملفات العروض التقديمية. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | خيارات عرض ملفات إدارة المشاريع. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | يعطل عرض التعليقات عند تعيينه إلى `true`. بشكل افتراضي يكون `false` — جميع التعليقات تُعرض. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | يفعل عرض الصفحات المخفية. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | يفعل عرض الملاحظات والتعليقات التوضيحية لبعض الصيغ |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | خيارات عرض ملفات الجداول الإلكترونية. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | خيارات عرض ملفات النص. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | خيارات عرض ملفات Visio. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | خيارات عرض ملفات الويب. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | عرض الصورة الناتجة (بالبكسل، لتصيير إلى PNG/JPG فقط). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | خيارات عرض ملفات معالجة النصوص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | يقوم بتهيئة نسخة من الفئة [`ViewInfoOptions`](../viewinfooptions) لاسترجاع معلومات العرض عند التصيير إلى HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | يقوم بتهيئة نسخة من الفئة [`ViewInfoOptions`](../viewinfooptions) لاسترجاع معلومات العرض عند التصيير إلى HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | يقوم بتهيئة نسخة من الفئة [`ViewInfoOptions`](../viewinfooptions) لاسترجاع معلومات العرض عند التصيير إلى JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | يقوم بتهيئة نسخة من الفئة [`ViewInfoOptions`](../viewinfooptions) لاسترجاع معلومات العرض عند التصيير إلى JPG. |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | يقوم بتهيئة نسخة من الفئة [`ViewInfoOptions`](../viewinfooptions) لاسترجاع معلومات العرض عند التصيير إلى PDF. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | يقوم بتهيئة نسخة من الفئة [`ViewInfoOptions`](../viewinfooptions) لاسترجاع معلومات العرض عند التصيير إلى PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | يقوم بتهيئة نسخة من الفئة [`ViewInfoOptions`](../viewinfooptions) لاسترجاع معلومات العرض عند التصيير إلى PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | يقوم بتهيئة نسخة من الفئة [`ViewInfoOptions`](../viewinfooptions) بناءً على كائن [`HtmlViewOptions`](../htmlviewoptions). |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | يقوم بتهيئة نسخة من الفئة [`ViewInfoOptions`](../viewinfooptions) بناءً على كائن [`JpgViewOptions`](../jpgviewoptions). |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | يقوم بتهيئة نسخة من الفئة [`ViewInfoOptions`](../viewinfooptions) بناءً على كائن [`PdfViewOptions`](../pdfviewoptions). |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | يقوم بتهيئة نسخة من الفئة [`ViewInfoOptions`](../viewinfooptions) بناءً على كائن [`PngViewOptions`](../pngviewoptions). |

### انظر أيضًا

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
