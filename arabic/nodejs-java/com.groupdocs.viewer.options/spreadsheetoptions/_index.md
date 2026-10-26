---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يوفر خيارات لتصيير جداول البيانات."
type: docs
weight: 31
url: /ar/nodejs-java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

يوفر خيارات لتصيير جداول البيانات.

تُجسّد فئة SpreadsheetOptions إعدادات ومعلمات مختلفة يمكن استخدامها للتحكم في عرض ملفات الجداول (مثل ملفات Excel أو CSV) في مكوّن GroupDocs.Viewer. للتفاصيل، راجع الفروع التابعة لموضوع [Render spreadsheet files][].

مثال على الاستخدام:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 SpreadsheetOptions spreadsheetOptions = pngViewOptions.getSpreadsheetOptions();
 spreadsheetOptions.setRenderHeadings(true);
 spreadsheetOptions.setCountColumnsPerPage(24);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[Render spreadsheet files]: https://docs.groupdocs.com/viewer/java/render-spreadsheets/
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isRenderByPageBreaks()](#isRenderByPageBreaks--) | يحدد ما إذا كان يجب عرض ورقة العمل وفقًا لفواصل الصفحات. |
| [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | يحدد ما إذا كان يجب عرض ورقة العمل وفقًا لفواصل الصفحات. |
| [isDetectSeparator()](#isDetectSeparator--) | يكتشف الفاصل لملفات CSV/TSV. |
| [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | يحدد ما إذا كان يجب اكتشاف الفاصل لملفات CSV/TSV. |
| [forOnePagePerSheet()](#forOnePagePerSheet--) | ينشئ نسخة جديدة من فئة SpreadsheetOptions لتصوير ورقة واحدة في صفحة واحدة. |
| [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | ينشئ نسخة جديدة من فئة SpreadsheetOptions لتصوير ورقة في صفحات متعددة. |
| [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | يُهيئ نسخة جديدة من فئة SpreadsheetOptions لتصوير ورقة في صفحات. |
| [forRenderingPrintArea()](#forRenderingPrintArea--) | يُهيئ نسخة جديدة من فئة SpreadsheetOptions لتصوير مناطق الطباعة فقط. |
| [isOnePagePerSheet()](#isOnePagePerSheet--) | يشير إلى ما إذا كانت ورقة واحدة تُصوَّر في صفحة واحدة. |
| [getCountRowsPerPage()](#getCountRowsPerPage--) | يحصل على عدد الصفوف التي يجب تضمينها في كل صفحة عند تقسيم ورقة العمل إلى صفحات. |
| [getCountColumnsPerPage()](#getCountColumnsPerPage--) | يحصل على عدد الأعمدة التي يجب تضمينها في كل صفحة عند تقسيم ورقة العمل إلى صفحات. |
| [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | يحدد عدد الأعمدة التي يجب تضمينها في كل صفحة عند تقسيم ورقة العمل إلى صفحات. |
| [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | يشير إلى ما إذا كانت مناطق الطباعة فقط هي التي تُصوَّر. |
| [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | عند تمكين هذا الخيار، سيتم تصوير ورقة العمل وفقًا لفواصل الصفحات التي تقع داخل منطقة الطباعة. |
| [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | يحدد ما إذا كان يجب تصوير ورقة العمل وفقًا لفواصل الصفحات التي تقع داخل منطقة الطباعة. |
| [isRenderGridLines()](#isRenderGridLines--) | يفعل تصوير خطوط الشبكة. |
| [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | يفعل أو يعطل تصوير خطوط الشبكة. |
| [isSkipEmptyRows()](#isSkipEmptyRows--) | يشير إلى ما إذا كان يجب تخطي الصفوف الفارغة أثناء التصوير. |
| [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | يحدد ما إذا كان يجب تخطي الصفوف الفارغة أثناء التصوير. |
| [isSkipEmptyColumns()](#isSkipEmptyColumns--) | يشير إلى ما إذا كان يجب تخطي الأعمدة الفارغة أثناء التصوير. |
| [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | يحدد ما إذا كان يجب تخطي الأعمدة الفارغة أثناء التصوير. |
| [isRenderHiddenRows()](#isRenderHiddenRows--) | يحدد ما إذا كان يجب تصوير الصفوف المخفية. |
| [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | يحدد ما إذا كان يجب تصوير الصفوف المخفية. |
| [isRenderHeadings()](#isRenderHeadings--) | يتحقق مما إذا كان تصوير العناوين مفعلاً. |
| [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | يفعل تصوير العناوين. |
| [isRenderHiddenColumns()](#isRenderHiddenColumns--) | يفعل تصوير الأعمدة المخفية. |
| [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | يفعل تصوير الأعمدة المخفية. |
| [getTextOverflowMode()](#getTextOverflowMode--) | يعيد وضع تجاوز النص لتصوير مستندات الجداول الإلكترونية إلى HTML. |
| [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | يضبط وضع تجاوز النص لتصوير مستندات الجداول الإلكترونية إلى HTML. |
| [getLeftMargin()](#getLeftMargin--) | لتعيين الهامش الأيسر لورقة العمل عند التحويل إلى PDF إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل |
| [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | لتعيين الهامش الأيسر لورقة العمل عند التحويل إلى PDF إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل |
| [getRightMargin()](#getRightMargin--) | لتعيين الهامش الأيمن لورقة العمل عند التحويل إلى PDF إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. |
| [setRightMargin(double rightMargin)](#setRightMargin-double-) | لتعيين الهامش الأيمن لورقة العمل عند التحويل إلى PDF إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. |
| [getTopMargin()](#getTopMargin--) | لتعيين الهامش العلوي لورقة العمل عند التحويل إلى PDF إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. |
| [setTopMargin(double topMargin)](#setTopMargin-double-) | لتعيين الهامش العلوي لورقة العمل عند التحويل إلى PDF إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. |
| [getBottomMargin()](#getBottomMargin--) | لتعيين الهامش السفلي لورقة العمل عند التحويل إلى PDF إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. |
| [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | لتعيين الهامش السفلي لورقة العمل عند التحويل إلى PDF إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. |
| [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | يُنشئ مثيلاً جديدًا من  SpreadsheetOptions  لتصوير مناطق الطباعة وفواصل الصفحات. |
| [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | يُهيئ نسخة جديدة من فئة SpreadsheetOptions لتصوير مناطق الطباعة فقط. |
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


يحدد ما إذا كان يجب عرض ورقة العمل وفقًا لفواصل الصفحات.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Returns:**
منطقي -  true  إذا كان يجب تصوير ورقة العمل بواسطة فواصل الصفحات،  false  غير ذلك.
### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


يحدد ما إذا كان يجب عرض ورقة العمل وفقًا لفواصل الصفحات.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderByPageBreaks | boolean | true  إذا كان يجب تصوير ورقة العمل بواسطة فواصل الصفحات،  false  غير ذلك. |

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


يكتشف الفاصل لملفات CSV/TSV.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Returns:**
منطقي -  true  إذا كان يجب اكتشاف الفاصل تلقائيًا،  false  غير ذلك.
### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


يحدد ما إذا كان يجب اكتشاف الفاصل لملفات CSV/TSV.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| detectSeparator | boolean | true  لاكتشاف الفاصل تلقائيًا،  false  غير ذلك. |

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


ينشئ نسخة جديدة من فئة SpreadsheetOptions لتصوير ورقة واحدة في صفحة واحدة.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.
### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


ينشئ نسخة جديدة من فئة SpreadsheetOptions لتصوير ورقة في صفحات متعددة.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| countRowsPerPage | int | عدد الصفوف التي يجب تضمينها في كل صفحة. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.
### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


يُهيئ نسخة جديدة من فئة SpreadsheetOptions لتصوير ورقة في صفحات.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| countRowsPerPage | int | عدد الصفوف التي يجب تضمينها في كل صفحة. |
| countColumnsPerPage | int | عدد الأعمدة التي يجب تضمينها في كل صفحة. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.
### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


يُهيئ نسخة جديدة من فئة SpreadsheetOptions لتصوير مناطق الطباعة فقط.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.
### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


يشير إلى ما إذا كانت ورقة واحدة تُصوَّر في صفحة واحدة.

**Returns:**
منطقي -  true  إذا تم تصوير ورقة واحدة في صفحة واحدة؛  false  غير ذلك.
### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


يحصل على عدد الصفوف التي يجب تضمينها في كل صفحة عند تقسيم ورقة العمل إلى صفحات.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Returns:**
عدد صحيح - عدد الصفوف التي يجب تضمينها في كل صفحة.
### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


يحصل على عدد الأعمدة التي يجب تضمينها في كل صفحة عند تقسيم ورقة العمل إلى صفحات.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Returns:**
عدد صحيح - عدد الأعمدة التي يجب تضمينها في كل صفحة.
### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


يحدد عدد الأعمدة التي يجب تضمينها في كل صفحة عند تقسيم ورقة العمل إلى صفحات.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| countColumnsPerPage | int | عدد الأعمدة التي يجب تضمينها في كل صفحة. |

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


يشير إلى ما إذا كانت مناطق الطباعة فقط هي التي تُصوَّر.

**Returns:**
منطقي -  true  إذا تم تصوير مناطق الطباعة فقط،  false  غير ذلك.
### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


عند تمكين هذا الخيار، سيتم تصوير ورقة العمل وفقًا لفواصل الصفحات التي تقع داخل منطقة الطباعة.

**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


يحدد ما إذا كان يجب تصوير ورقة العمل وفقًا لفواصل الصفحات التي تقع داخل منطقة الطباعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderingPrintAreaAndPageBreaks | boolean | اضبطه على true للتفعيل، false للتعطيل. |

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


يفعل تصوير خطوط الشبكة.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Returns:**
منطقي -  true  إذا تم تمكين خطوط الشبكة،  false  خلاف ذلك.
### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


يفعل أو يعطل تصوير خطوط الشبكة.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | true  لتمكين عرض خطوط الشبكة،  false  لتعطيله. |

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


يشير إلى ما إذا كان يجب تخطي الصفوف الفارغة أثناء التصوير.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
منطقي -  true  إذا كان يجب تخطي الصفوف الفارغة،  false  خلاف ذلك.
### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


يحدد ما إذا كان يجب تخطي الصفوف الفارغة أثناء التصوير.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | true  لتخطي الصفوف الفارغة،  false  خلاف ذلك. |

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


يشير إلى ما إذا كان يجب تخطي الأعمدة الفارغة أثناء التصوير.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
منطقي -  true  إذا تم تخطي الأعمدة الفارغة،  false  خلاف ذلك.
### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


يحدد ما إذا كان يجب تخطي الأعمدة الفارغة أثناء التصوير.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | true  لتخطي الأعمدة الفارغة،  false  خلاف ذلك. |

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


يحدد ما إذا كان يجب تصوير الصفوف المخفية.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
منطقي -  true  إذا كان يجب عرض الصفوف المخفية،  false  خلاف ذلك.
### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


يحدد ما إذا كان يجب تصوير الصفوف المخفية.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | true  لتمكين عرض الصفوف المخفية،  false  لتعطيله. |

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


يتحقق مما إذا كان تصوير العناوين مفعلاً.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Returns:**
منطقي -  true  إذا تم تمكين عرض العناوين،  false  خلاف ذلك.
### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


يفعل تصوير العناوين.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderHeadings | boolean | true  لتمكين عرض العناوين،  false  لتعطيله. |

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


يفعل تصوير الأعمدة المخفية.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
منطقي -  true  إذا تم تمكين عرض الأعمدة المخفية،  false  خلاف ذلك.
### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


يفعل تصوير الأعمدة المخفية.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | true  لتمكين عرض الأعمدة المخفية،  false  لتعطيله. |

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


يعيد وضع تجاوز النص لتصوير مستندات الجداول الإلكترونية إلى HTML.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.
### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


يضبط وضع تجاوز النص لعرض مستندات الجداول الإلكترونية إلى HTML. للحصول على تفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | وضع تجاوز النص الذي سيتم ضبطه. |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


لتعيين الهامش الأيسر لورقة العمل عند التحويل إلى PDF إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل

إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للحصول على تفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


لتعيين الهامش الأيسر لورقة العمل عند التحويل إلى PDF إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل

إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للحصول على تفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


لتعيين الهامش الأيمن لورقة العمل عند التحويل إلى pdf؛ إذا كان أقل من 0 فسيتم استخدام قيمة التحويل الافتراضية. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للحصول على تفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


لتعيين الهامش الأيمن لورقة العمل عند التحويل إلى pdf؛ إذا كان أقل من 0 فسيتم استخدام قيمة التحويل الافتراضية. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للحصول على تفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


لتعيين الهامش العلوي لورقة العمل عند التحويل إلى pdf؛ إذا كان أقل من 0 فسيتم استخدام قيمة التحويل الافتراضية. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للحصول على تفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


لتعيين الهامش العلوي لورقة العمل عند التحويل إلى pdf؛ إذا كان أقل من 0 فسيتم استخدام قيمة التحويل الافتراضية. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للحصول على تفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


لتعيين الهامش السفلي لورقة العمل عند التحويل إلى pdf؛ إذا كان أقل من 0 فسيتم استخدام قيمة التحويل الافتراضية. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للحصول على تفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


لتعيين الهامش السفلي لورقة العمل عند التحويل إلى pdf؛ إذا كان أقل من 0 فسيتم استخدام قيمة التحويل الافتراضية. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للحصول على تفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bottomMargin | double |  |

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


ينشئ مثيلاً جديدًا من  SpreadsheetOptions  لعرض مناطق الطباعة وفواصل الصفحات. للحصول على تفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.
### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


ينشئ مثيلاً جديدًا من الفئة  SpreadsheetOptions  لعرض مناطق الطباعة فقط. للحصول على تفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.
