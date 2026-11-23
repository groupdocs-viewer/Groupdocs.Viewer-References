---
title: "HtmlViewOptions"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحتوي على خيارات لتصيير المستندات إلى تنسيق HTML. لمزيد من التفاصيل راجع topichttps//docs.groupdocs.com/viewer/net/renderingtohtml/ وأقسامه الفرعية."
type: docs
weight: 320
url: /ar/net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

يحتوي على خيارات لتصيير المستندات إلى صيغة HTML. للحصول على تفاصيل، راجع [الموضوع](https://docs.groupdocs.com/viewer/net/rendering-to-html/) وأقسامه الفرعية.

```csharp
public class HtmlViewOptions : ViewOptions
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | خيارات عرض ملفات الأرشيف. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | خيارات عرض رسومات CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | يضبط الخط الافتراضي للمستند. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | خيارات عرض رسائل البريد الإلكتروني. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | يعطل إضافة أي خطوط إلى مستند HTML. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | قائمة أسماء الخطوط التي يجب استبعادها من مستند HTML. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | يفعل تحسين HTML الناتج للطباعة. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | ارتفاع الصورة الناتجة (بالبيكسل). الخاصية متاحة عند تحويل صورة واحدة إلى HTML فقط. |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | الحد الأقصى لارتفاع صورة الإخراج (بالبكسل). الخاصية متاحة عند تحويل صورة واحدة إلى HTML فقط. |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | الحد الأقصى لعرض صورة الإخراج (بالبكسل). الخاصية متاحة عند تحويل صورة واحدة إلى HTML فقط. |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | عرض صورة الإخراج (بالبكسل). الخاصية متاحة عند تحويل صورة واحدة إلى HTML فقط. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | خيارات عرض ملفات بيانات تخزين البريد. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | يُمكّن تصغير محتوى HTML وموارد HTML. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | خيارات عرض ملفات بيانات Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | خيارات عرض مستند PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | خيارات عرض ملفات العروض التقديمية. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | خيارات عرض ملفات إدارة المشاريع. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | يعطل عرض التعليقات عند تعيينه إلى `true`. بشكل افتراضي يكون `false` — جميع التعليقات تُعرض. |
| [RemoveJavaScript](../../groupdocs.viewer.options/htmlviewoptions/removejavascript) { get; set; } | يسمح بإزالة شفرة JavaScript المصدرية من الروابط في مستندات HTML الناتجة، عند عرض المستندات المدخلة التي تحتوي على السكريبتات. بشكل افتراضي مُفعَّل (`true`). |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | يفعل عرض الصفحات المخفية. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | يفعل عرض الملاحظات والتعليقات التوضيحية لبعض الصيغ |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | يُمكّن العرض المتجاوب. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | يُمكّن عرض مستند كامل في ملف HTML واحد. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | خيارات عرض ملفات الجداول الإلكترونية. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | خيارات عرض ملفات النص. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | خيارات عرض ملفات Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | علامة مائية نصية تُطبق على كل صفحة. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | خيارات عرض ملفات الويب. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | خيارات عرض ملفات معالجة النصوص. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | يُنشئ مثيلاً من الفئة [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | يُنشئ مثيلاً من الفئة [`HtmlViewOptions`](../htmlviewoptions) للعرض إلى HTML مع موارد مدمجة. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | يُنشئ مثيلاً من الفئة [`HtmlViewOptions`](../htmlviewoptions) للعرض إلى HTML مع موارد مدمجة. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | يُنشئ مثيلاً من الفئة [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | يُنشئ مثيلاً من الفئة [`HtmlViewOptions`](../htmlviewoptions) للعرض إلى HTML مع موارد مدمجة. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | يُنشئ مثيلاً من الفئة [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | يُنشئ مثيلاً من الفئة [`HtmlViewOptions`](../htmlviewoptions) للعرض إلى HTML مع موارد خارجية. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | يُنشئ مثيلاً من الفئة [`HtmlViewOptions`](../htmlviewoptions) للعرض إلى HTML مع موارد خارجية. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | يُنشئ مثيلاً من الفئة [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | يُنشئ مثيلاً من الفئة [`HtmlViewOptions`](../htmlviewoptions) للعرض إلى HTML مع موارد خارجية. |
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
