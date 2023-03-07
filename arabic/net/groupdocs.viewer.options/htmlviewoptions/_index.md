---
title: HtmlViewOptions
second_title: GroupDocs.Viewer لمرجع .NET API
description: يوفر خيارات لعرض المستندات بتنسيق HTML .
type: docs
weight: 330
url: /ar/net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

يوفر خيارات لعرض المستندات بتنسيق HTML .

```csharp
public class HtmlViewOptions : ViewOptions
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | خيارات عرض ملفات الأرشيف . |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | خيارات عرض رسم CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | الخط الافتراضي الذي سيتم استخدامه عندما يتعذر العثور على خط معين مستخدم في المستند. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | خيارات عرض رسائل البريد الإلكتروني . |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | عند التمكين يمنع إضافة أي خطوط إلى مستند HTML. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | قائمة أسماء الخطوط المطلوب استبعادها من مستند HTML. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | يشير إلى ما إذا كان سيتم تحسين إخراج HTML للطباعة. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | ارتفاع صورة الإخراج بالبكسل. (عند تحويل صورة واحدة إلى HTML فقط) |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | أقصى ارتفاع لصورة الإخراج بالبكسل. (عند تحويل صورة واحدة إلى HTML فقط) |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | أقصى عرض لصورة الإخراج بالبكسل. (عند تحويل صورة واحدة إلى HTML فقط) |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | عرض صورة الإخراج بالبكسل. (عند تحويل صورة واحدة إلى HTML فقط) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | خيارات عرض ملفات بيانات تخزين البريد . |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | تمكين محتوى HTML وتصغير موارد HTML . |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | خيارات عرض ملفات بيانات MS Outlook . |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | خيارات عرض مستندات PDF . |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | خيارات عرض مستندات معالجة العرض التقديمي. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | خيارات عرض ملفات إدارة المشروع. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | تمكين عرض التعليقات . |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | تمكين عرض الصفحات المخفية. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | تمكين عرض الملاحظات . |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | تمكين العرض سريع الاستجابة ؛ عرض صفحات الويب المتجاوبة جيدًا على أجهزة ذات حجم شاشة مختلف . |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | يتيح عرض مستند بأكمله إلى ملف HTML واحد. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | خيارات عرض ملفات جدول البيانات. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | تقسيم الملفات النصية إلى خيارات الصفحات. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | خيارات عرض مستندات معالجة ملفات Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | العلامة المائية النصية المطبقة على كل صفحة. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | تتيح لك خيارات العرض هذه تخصيص مظهر الناتج HTML / PDF / PNG / JPEG عند عرض مستندات الويب. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | تتيح لك خيارات العرض هذه تخصيص مظهر الناتج HTML / PDF / PNG / JPEG عند عرض مستندات Word. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | تهيئة مثيل جديد لـ[`HtmlViewOptions`](../htmlviewoptions) فئة . |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | تهيئة مثيل جديد لـ[`HtmlViewOptions`](../htmlviewoptions) فئة للعرض في HTML مع الموارد المضمنة . |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | تهيئة مثيل جديد لـ[`HtmlViewOptions`](../htmlviewoptions) فئة للعرض في HTML مع الموارد المضمنة . |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | تهيئة مثيل جديد لـ[`HtmlViewOptions`](../htmlviewoptions) فئة . |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | تهيئة مثيل جديد لـ[`HtmlViewOptions`](../htmlviewoptions) فئة للعرض في HTML مع الموارد المضمنة . |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | تهيئة مثيل جديد لـ[`HtmlViewOptions`](../htmlviewoptions) فئة . |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | تهيئة مثيل جديد لـ[`HtmlViewOptions`](../htmlviewoptions) فئة للعرض في HTML مع الموارد الخارجية . |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | تهيئة مثيل جديد لـ[`HtmlViewOptions`](../htmlviewoptions) فئة للعرض في HTML مع الموارد الخارجية . |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | تهيئة مثيل جديد لـ[`HtmlViewOptions`](../htmlviewoptions) فئة . |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | تهيئة مثيل جديد لـ[`HtmlViewOptions`](../htmlviewoptions) فئة للعرض في HTML مع الموارد الخارجية . |
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
