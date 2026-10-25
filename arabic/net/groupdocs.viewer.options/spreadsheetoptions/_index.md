---
title: "SpreadsheetOptions"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحتوي على خيارات لتصيير جداول البيانات. للحصول على التفاصيل راجع الفروع التابعة لموضوع ملفات تصيير جداول البيانات https//docs.groupdocs.com/viewer/net/renderspreadsheets/."
type: docs
weight: 530
url: /ar/net/groupdocs.viewer.options/spreadsheetoptions/
---

## SpreadsheetOptions class

يحتوي على خيارات لتصيير جداول البيانات. للحصول على تفاصيل، راجع أقسام موضوع [تصيير ملفات جداول البيانات](https://docs.groupdocs.com/viewer/net/render-spreadsheets/).

```csharp
public class SpreadsheetOptions
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/spreadsheetoptions/bottommargin) { get; set; } | يعيّن الهامش السفلي للصفحة عند التحويل إلى PDF. |
| [CountColumnsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countcolumnsperpage) { get; } | عدد الأعمدة التي سيتم تضمينها في كل صفحة عند تقسيم ورقة العمل إلى صفحات. |
| [CountRowsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countrowsperpage) { get; } | عدد الصفوف التي سيتم تضمينها في كل صفحة عند تقسيم ورقة العمل إلى صفحات. |
| [DetectSeparator](../../groupdocs.viewer.options/spreadsheetoptions/detectseparator) { get; set; } | اكتشاف الفاصل (لملفات CSV/TSV). |
| [HorizontalResolution](../../groupdocs.viewer.options/spreadsheetoptions/horizontalresolution) { get; set; } | يحصل أو يعيّن الدقة الأفقية للصور المولدة بوحدة النقاط في البوصة. يُستخدم هذا الخيار فقط عند تصيير جداول البيانات إلى صيغ PNG أو JPEG. |
| [LeftMargin](../../groupdocs.viewer.options/spreadsheetoptions/leftmargin) { get; set; } | يعيّن الهامش الأيسر للصفحة عند التحويل إلى PDF. |
| [RenderGridLines](../../groupdocs.viewer.options/spreadsheetoptions/rendergridlines) { get; set; } | يتيح تصيير خطوط الشبكة. |
| [RenderHeadings](../../groupdocs.viewer.options/spreadsheetoptions/renderheadings) { get; set; } | يتيح تصيير العناوين. |
| [RenderHiddenColumns](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddencolumns) { get; set; } | يتيح تصيير الأعمدة المخفية. |
| [RenderHiddenRows](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddenrows) { get; set; } | يتيح تصيير الصفوف المخفية. |
| [RightMargin](../../groupdocs.viewer.options/spreadsheetoptions/rightmargin) { get; set; } | يعيّن الهامش الأيمن للصفحة عند التحويل إلى PDF. |
| [SkipEmptyColumns](../../groupdocs.viewer.options/spreadsheetoptions/skipemptycolumns) { get; set; } | يعطل عرض الأعمدة الفارغة. |
| [SkipEmptyRows](../../groupdocs.viewer.options/spreadsheetoptions/skipemptyrows) { get; set; } | يعطل عرض الصفوف الفارغة. |
| [TextOverflowMode](../../groupdocs.viewer.options/spreadsheetoptions/textoverflowmode) { get; set; } | يضبط وضع تجاوز النص عند عرض مستندات الجداول الإلكترونية إلى HTML. بشكل افتراضي هو , والذي يحاكي سلوك MS Excel الافتراضي. |
| [TopMargin](../../groupdocs.viewer.options/spreadsheetoptions/topmargin) { get; set; } | يضبط الهامش العلوي للصفحة عند التحويل إلى PDF. |
| [VerticalResolution](../../groupdocs.viewer.options/spreadsheetoptions/verticalresolution) { get; set; } | يحصل أو يضبط الدقة العمودية للصور المُولدة بوحدة النقاط في البوصة. يُستخدم هذا الخيار فقط عند عرض الجداول الإلكترونية إلى صيغ PNG أو JPEG. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [ForOnePagePerSheet](../../groupdocs.viewer.options/spreadsheetoptions/foronepagepersheet)() | ينشئ مثيلاً من الفئة [`SpreadsheetOptions`](../spreadsheetoptions) لعرض الورقة كاملة في صفحة واحدة. |
| static [ForRenderingByPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingbypagebreaks)() | ينشئ مثيلاً من الفئة [`SpreadsheetOptions`](../spreadsheetoptions) لتقسيم الصفحات حسب فواصل الصفحات. |
| static [ForRenderingPrintArea](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintarea)() | ينشئ مثيلاً من الفئة [`SpreadsheetOptions`](../spreadsheetoptions) لعرض مناطق الطباعة فقط. |
| static [ForRenderingPrintAreaAndPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintareaandpagebreaks)() | ينشئ مثيلاً من الفئة [`SpreadsheetOptions`](../spreadsheetoptions) لعرض مناطق الطباعة وفواصل الصفحات. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages)(int) | ينشئ مثيلاً من الفئة [`SpreadsheetOptions`](../spreadsheetoptions) لعرض الورقة إلى صفحات. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages_1)(int, int) | ينشئ مثيلاً من الفئة [`SpreadsheetOptions`](../spreadsheetoptions) لعرض الورقة إلى صفحات. |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
