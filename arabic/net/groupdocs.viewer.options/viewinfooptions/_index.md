---
title: ViewInfoOptions
second_title: GroupDocs.Viewer لمرجع .NET API
description: توفير الخيارات المستخدمة لاسترداد المعلومات حول طريقة العرض.
type: docs
weight: 570
url: /ar/net/groupdocs.viewer.options/viewinfooptions/
---
## ViewInfoOptions class

توفير الخيارات المستخدمة لاسترداد المعلومات حول طريقة العرض.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | خيارات عرض ملفات الأرشيف . |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | خيارات عرض رسم CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | الخط الافتراضي الذي سيتم استخدامه عندما يتعذر العثور على خط معين مستخدم في المستند. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | خيارات عرض رسائل البريد الإلكتروني . |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | يشير إلى تمكين استخراج النص . |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | ارتفاع الصورة (للعرض على PNG / JPG فقط) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | خيارات عرض ملفات بيانات تخزين البريد . |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | أقصى ارتفاع للصورة الناتجة (للعرض على PNG / JPG فقط) |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | أقصى عرض للصورة الناتجة (للعرض على PNG / JPG فقط) |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | خيارات عرض ملفات بيانات MS Outlook . |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | خيارات عرض مستندات PDF . |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | خيارات عرض مستندات معالجة العرض التقديمي. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | خيارات عرض ملفات إدارة المشروع. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | تمكين عرض التعليقات . |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | تمكين عرض الصفحات المخفية. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | تمكين عرض الملاحظات . |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | خيارات عرض ملفات جدول البيانات. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | تقسيم الملفات النصية إلى خيارات الصفحات. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | خيارات عرض مستندات معالجة ملفات Visio. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | تتيح لك خيارات العرض هذه تخصيص مظهر الناتج HTML / PDF / PNG / JPEG عند عرض مستندات الويب. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | عرض الصورة (للعرض على PNG / JPG فقط) |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | تتيح لك خيارات العرض هذه تخصيص مظهر الناتج HTML / PDF / PNG / JPEG عند عرض مستندات Word. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | تهيئة مثيل جديد لـ[`ViewInfoOptions`](../viewinfooptions) فئة لاسترداد معلومات حول العرض عند التقديم إلى HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | تهيئة مثيل جديد لـ[`ViewInfoOptions`](../viewinfooptions) فئة لاسترداد معلومات حول العرض عند التقديم إلى HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | تهيئة مثيل جديد لـ[`ViewInfoOptions`](../viewinfooptions) فئة لاسترداد معلومات حول العرض عند التقديم بتنسيق JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | تهيئة مثيل جديد لـ[`ViewInfoOptions`](../viewinfooptions) فئة لاسترداد معلومات حول العرض عند التقديم بتنسيق JPG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | تهيئة مثيل جديد لـ[`ViewInfoOptions`](../viewinfooptions) فئة لاسترداد معلومات حول العرض عند التقديم إلى PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | تهيئة مثيل جديد لـ[`ViewInfoOptions`](../viewinfooptions) فئة لاسترداد معلومات حول العرض عند التقديم إلى PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | تهيئة مثيل جديد لـ[`ViewInfoOptions`](../viewinfooptions) فئة على أساس[`HtmlViewOptions`](../htmlviewoptions) الكائن . |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | تهيئة مثيل جديد لـ[`ViewInfoOptions`](../viewinfooptions) فئة على أساس[`JpgViewOptions`](../jpgviewoptions) الكائن . |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | تهيئة مثيل جديد لـ[`ViewInfoOptions`](../viewinfooptions) فئة على أساس[`PngViewOptions`](../pngviewoptions) الكائن . |

### أنظر أيضا

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* مساحة الاسم [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* المجسم [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
