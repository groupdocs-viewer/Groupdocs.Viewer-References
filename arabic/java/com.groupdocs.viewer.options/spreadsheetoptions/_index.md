---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر خيارات لتصيير جداول البيانات."
type: docs
weight: 31
url: /ar/java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

يوفر خيارات لتصيير جداول البيانات.


فئة SpreadsheetOptions تضم إعدادات ومعلمات مختلفة يمكن استخدامها
للتحكم في عرض ملفات الجداول (مثل ملفات Excel أو CSV) في مكوّن GroupDocs.Viewer.
للتفاصيل، راجع الفروع التابعة لموضوع [Render spreadsheet files](../https://docs.groupdocs.com/viewer/java/render-spreadsheets/).


مثال على الاستخدام:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 SpreadsheetOptions spreadsheetOptions = pngViewOptions.getSpreadsheetOptions();
 spreadsheetOptions.setRenderHeadings(true);
 spreadsheetOptions.setCountColumnsPerPage(24);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isRenderByPageBreaks()](#isRenderByPageBreaks--) | يحدد ما إذا كان يجب عرض ورقة العمل باستخدام فواصل الصفحات. |
|
|  | [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | يضبط ما إذا كان يجب عرض ورقة العمل باستخدام فواصل الصفحات. |
|
|  | [isDetectSeparator()](#isDetectSeparator--) | يكتشف الفاصل لملفات CSV/TSV. |
|
|  | [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | يضبط ما إذا كان يجب اكتشاف الفاصل لملفات CSV/TSV. |
|
|  | [forOnePagePerSheet()](#forOnePagePerSheet--) | ينشئ مثيلاً جديداً لـ |
SpreadsheetOptions
فئة لعرض ورقة واحدة في صفحة واحدة.
|
|  | [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | ينشئ مثيلاً جديداً لـ |
SpreadsheetOptions
فئة لعرض ورقة في عدة صفحات.
|
|  | [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | ينشئ مثلاً جديداً من |
SpreadsheetOptions
فئة لعرض ورقة في صفحات.
|
|  | [forRenderingPrintArea()](#forRenderingPrintArea--) | ينشئ مثلاً جديداً من |
SpreadsheetOptions
فئة لعرض مناطق الطباعة فقط.
|
|  | [isOnePagePerSheet()](#isOnePagePerSheet--) | يشير إلى ما إذا كانت ورقة واحدة تُعرض في صفحة واحدة. |
|
|  | [getCountRowsPerPage()](#getCountRowsPerPage--) | يحصل على عدد الصفوف التي يجب تضمينها في كل صفحة عند تقسيم ورقة العمل إلى صفحات. |
|
|  | [getCountColumnsPerPage()](#getCountColumnsPerPage--) | يحصل على عدد الأعمدة التي يجب تضمينها في كل صفحة عند تقسيم ورقة العمل إلى صفحات. |
|
|  | [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | يضبط عدد الأعمدة التي يتم تضمينها في كل صفحة عند تقسيم ورقة العمل إلى صفحات. |
|
|  | [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | يشير إلى ما إذا كانت مناطق الطباعة فقط هي التي يتم عرضها. |
|
|  | [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | عند تمكين هذا الخيار، سيتم عرض ورقة العمل حسب فواصل الصفحات التي تقع داخل منطقة الطباعة. |
|
|  | [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | يضبط ما إذا كان سيتم عرض ورقة العمل حسب فواصل الصفحات التي تقع داخل منطقة الطباعة. |
|
|  | [isRenderGridLines()](#isRenderGridLines--) | يفعل عرض خطوط الشبكة. |
|
|  | [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | يفعل أو يعطل عرض خطوط الشبكة. |
|
|  | [isSkipEmptyRows()](#isSkipEmptyRows--) | يشير إلى ما إذا كان يجب تخطي الصفوف الفارغة أثناء العرض. |
|
|  | [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | يضبط ما إذا كان يجب تخطي الصفوف الفارغة أثناء العرض. |
|
|  | [isSkipEmptyColumns()](#isSkipEmptyColumns--) | يشير إلى ما إذا كان يجب تخطي الأعمدة الفارغة أثناء العرض. |
|
|  | [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | يضبط ما إذا كان يجب تخطي الأعمدة الفارغة أثناء العرض. |
|
|  | [isRenderHiddenRows()](#isRenderHiddenRows--) | يحدد ما إذا كان يجب عرض الصفوف المخفية. |
|
|  | [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | يضبط ما إذا كان يجب عرض الصفوف المخفية. |
|
|  | [isRenderHeadings()](#isRenderHeadings--) | يتحقق مما إذا كان عرض العناوين مفعلاً. |
|
|  | [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | يفعل عرض العناوين. |
|
|  | [isRenderHiddenColumns()](#isRenderHiddenColumns--) | يفعل عرض الأعمدة المخفية. |
|
|  | [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | يفعل عرض الأعمدة المخفية. |
|
|  | [getTextOverflowMode()](#getTextOverflowMode--) | يرجع وضع تجاوز النص لعرض مستندات الجداول الإلكترونية إلى HTML. |
|
|  | [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | يضبط وضع تجاوز النص لعرض مستندات الجداول الإلكترونية إلى HTML. |
|
|  | [getLeftMargin()](#getLeftMargin--) | لتعيين الهامش الأيسر لورقة العمل عند التحويل إلى PDF، إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. |
|
|  | [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | لتعيين الهامش الأيسر لورقة العمل عند التحويل إلى PDF، إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. |
|
|  | [getRightMargin()](#getRightMargin--) | لتعيين الهامش الأيمن لورقة العمل عند التحويل إلى PDF، إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. |
|
|  | [setRightMargin(double rightMargin)](#setRightMargin-double-) | لتعيين الهامش الأيمن لورقة العمل عند التحويل إلى PDF، إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. |
|
|  | [getTopMargin()](#getTopMargin--) | لتعيين الهامش العلوي لورقة العمل عند التحويل إلى PDF، إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. |
|
|  | [setTopMargin(double topMargin)](#setTopMargin-double-) | لتعيين الهامش العلوي لورقة العمل عند التحويل إلى PDF، إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. |
|
|  | [getBottomMargin()](#getBottomMargin--) | لتعيين الهامش السفلي لورقة العمل عند التحويل إلى PDF، إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. |
|
|  | [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | لتعيين الهامش السفلي لورقة العمل عند التحويل إلى PDF، إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | يحصل أو يضبط الدقة الأفقية للصور المولدة بوحدة النقاط في البوصة. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | يضبط الدقة الأفقية للصور المولدة بوحدة النقاط في البوصة. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | يحصل أو يضبط الدقة العمودية للصور المولدة بوحدة النقاط في البوصة. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | يضبط الدقة العمودية للصور المولدة بوحدة النقاط في البوصة. |
|
|  | [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | يُنشئ مثيلاً جديدًا من  SpreadsheetOptions  لتصيير مناطق الطباعة وفواصل الصفحات. |
|
|  | [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | يُنشئ مثيلاً جديدًا من فئة  SpreadsheetOptions  لتصيير مناطق الطباعة فقط. |
|
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


يحدد ما إذا كان يجب عرض ورقة العمل باستخدام فواصل الصفحات.


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Returns:**
منطقي -  true  إذا كان يجب تصيير ورقة العمل بفواصل الصفحات،  false  خلاف ذلك.

### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


يضبط ما إذا كان يجب عرض ورقة العمل باستخدام فواصل الصفحات.


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | renderByPageBreaks | boolean | true  إذا كان يجب تصيير ورقة العمل بفواصل الصفحات،  false  خلاف ذلك. |
|

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


يكتشف الفاصل لملفات CSV/TSV.


للتفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator).


**Returns:**
منطقي -  true  إذا كان يجب اكتشاف الفاصل تلقائيًا،  false  خلاف ذلك.

### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


يضبط ما إذا كان يجب اكتشاف الفاصل لملفات CSV/TSV.


للتفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | detectSeparator | boolean | true  لاكتشاف الفاصل تلقائيًا،  false  خلاف ذلك. |
|

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


ينشئ مثيلاً جديداً لـ
SpreadsheetOptions
فئة لعرض ورقة واحدة في صفحة واحدة.
للتفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.

### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


ينشئ مثيلاً جديداً لـ
SpreadsheetOptions
فئة لعرض ورقة في عدة صفحات.
للتفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | countRowsPerPage | int | عدد الصفوف التي يجب تضمينها في كل صفحة. |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.

### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


ينشئ مثلاً جديداً من
SpreadsheetOptions
فئة لعرض ورقة في صفحات.
للتفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | countRowsPerPage | int | عدد الصفوف التي يجب تضمينها في كل صفحة. |
|
|  | countColumnsPerPage | int | عدد الأعمدة التي يجب تضمينها في كل صفحة. |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.

### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


ينشئ مثلاً جديداً من
SpreadsheetOptions
فئة لعرض مناطق الطباعة فقط.
للتفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.

### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


يشير إلى ما إذا كانت ورقة واحدة تُعرض في صفحة واحدة.


**Returns:**
منطقي -  true  إذا تم تصيير ورقة واحدة في صفحة واحدة؛  false  خلاف ذلك.

### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


يحصل على عدد الصفوف التي يجب تضمينها في كل صفحة عند تقسيم ورقة العمل إلى صفحات.


للتفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Returns:**
عدد صحيح - عدد الصفوف التي يجب تضمينها في كل صفحة.

### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


يحصل على عدد الأعمدة التي يجب تضمينها في كل صفحة عند تقسيم ورقة العمل إلى صفحات.


للتفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).


**Returns:**
عدد صحيح - عدد الأعمدة التي يجب تضمينها في كل صفحة.

### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


يضبط عدد الأعمدة التي يتم تضمينها في كل صفحة عند تقسيم ورقة العمل إلى صفحات.


للتفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | countColumnsPerPage | int | عدد الأعمدة التي يجب تضمينها في كل صفحة. |
|

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


يشير إلى ما إذا كانت مناطق الطباعة فقط هي التي يتم عرضها.


**Returns:**
منطقي -  true  إذا تم تصيير مناطق الطباعة فقط،  false  خلاف ذلك.

### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


عند تمكين هذا الخيار، سيتم عرض ورقة العمل حسب فواصل الصفحات التي تقع داخل منطقة الطباعة.


**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


يضبط ما إذا كان سيتم عرض ورقة العمل حسب فواصل الصفحات التي تقع داخل منطقة الطباعة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | renderingPrintAreaAndPageBreaks | boolean | عيّن إلى true للتفعيل، false للتعطيل. |
|

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


يفعل عرض خطوط الشبكة.


للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines).


**Returns:**
منطقي -  true  إذا تم تمكين خطوط الشبكة،  false  خلاف ذلك.

### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


يفعل أو يعطل عرض خطوط الشبكة.


للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  لتمكين عرض خطوط الشبكة،  false  لتعطيله. |
|

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


يشير إلى ما إذا كان يجب تخطي الصفوف الفارغة أثناء العرض.


للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Returns:**
منطقي -  true  إذا كان يجب تخطي الصفوف الفارغة،  false  خلاف ذلك.

### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


يضبط ما إذا كان يجب تخطي الصفوف الفارغة أثناء العرض.


للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  لتخطي الصفوف الفارغة،  false  خلاف ذلك. |
|

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


يشير إلى ما إذا كان يجب تخطي الأعمدة الفارغة أثناء العرض.


للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Returns:**
منطقي -  true  إذا تم تخطي الأعمدة الفارغة،  false  خلاف ذلك.

### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


يضبط ما إذا كان يجب تخطي الأعمدة الفارغة أثناء العرض.


للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  لتخطي الأعمدة الفارغة،  false  خلاف ذلك. |
|

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


يحدد ما إذا كان يجب عرض الصفوف المخفية.


للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Returns:**
منطقي -  true  إذا كان يجب عرض الصفوف المخفية،  false  خلاف ذلك.

### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


يضبط ما إذا كان يجب عرض الصفوف المخفية.


للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  لتمكين عرض الصفوف المخفية،  false  لتعطيله. |
|

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


يتحقق مما إذا كان عرض العناوين مفعلاً.


للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings).


**Returns:**
منطقي -  true  إذا كان عرض العناوين مفعلاً،  false  خلاف ذلك.

### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


يفعل عرض العناوين.


للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | renderHeadings | boolean | true  لتمكين عرض العناوين،  false  لتعطيله. |
|

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


يفعل عرض الأعمدة المخفية.


للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Returns:**
منطقي -  true  إذا كان عرض الأعمدة المخفية مفعلاً،  false  خلاف ذلك.

### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


يفعل عرض الأعمدة المخفية.


للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  لتمكين عرض الأعمدة المخفية،  false  لتعطيله. |
|

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


يرجع وضع تجاوز النص لعرض مستندات الجداول الإلكترونية إلى HTML.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.

### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


يضبط وضع تجاوز النص لتصوير مستندات الجداول إلى HTML. للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | وضع تجاوز النص الذي سيتم ضبطه. |
|

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


لتعيين الهامش الأيسر لورقة العمل عند التحويل إلى PDF، إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل.


إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


لتعيين الهامش الأيسر لورقة العمل عند التحويل إلى PDF، إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل.


إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


لتعيين الهامش الأيمن للورقة عند التحويل إلى pdf إذا كان أقل من 0 فسيتم استخدام قيمة التحويل الافتراضية إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


لتعيين الهامش الأيمن للورقة عند التحويل إلى pdf إذا كان أقل من 0 فسيتم استخدام قيمة التحويل الافتراضية إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


لتعيين الهامش العلوي للورقة عند التحويل إلى pdf إذا كان أقل من 0 فسيتم استخدام قيمة التحويل الافتراضية إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


لتعيين الهامش العلوي للورقة عند التحويل إلى pdf إذا كان أقل من 0 فسيتم استخدام قيمة التحويل الافتراضية إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


لتعيين الهامش السفلي لورقة العمل عند التحويل إلى PDF إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


لتعيين الهامش السفلي لورقة العمل عند التحويل إلى PDF إذا كان أقل من 0 فسيتم استخدام القيمة الافتراضية للتحويل. إذا كان المعامل أقل من 0، فسيتم استخدام القيمة الافتراضية. للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bottomMargin | double |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


يحصل أو يضبط الدقة الأفقية للصور المولدة بوحدة النقاط في البوصة. يُستخدم هذا الخيار عند تصيير جداول البيانات إلى صيغ PNG أو JPEG فقط.


القيمة الافتراضية هي 96 DPI. الحد الأدنى الممكن هو 72 DPI، والحد الأقصى الممكن هو 600 DPI.
إذا كانت القيمة المحددة من قبل المستخدم خارج هذه الحدود، سيتم تطبيق الحد الأدنى أو الحد الأقصى الممكن.


**Returns:**
int - الدقة الأفقية بوحدة DPI.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


يضبط الدقة الأفقية للصور المولدة بوحدة النقاط في البوصة. يُستخدم هذا الخيار عند تصيير جداول البيانات إلى صيغ PNG أو JPEG فقط.


القيمة الافتراضية هي 96 DPI. الحد الأدنى الممكن هو 72 DPI، والحد الأقصى الممكن هو 600 DPI.
إذا كانت القيمة المحددة من قبل المستخدم خارج هذه الحدود، سيتم تطبيق الحد الأدنى أو الحد الأقصى الممكن.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | horizontalResolution | int | الدقة الأفقية بوحدة DPI. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


يحصل أو يضبط الدقة العمودية للصور المولدة بوحدة النقاط في البوصة. يُستخدم هذا الخيار عند تصيير جداول البيانات إلى صيغ PNG أو JPEG فقط.


القيمة الافتراضية هي 96 DPI. الحد الأدنى الممكن هو 72 DPI، والحد الأقصى الممكن هو 600 DPI.
إذا كانت القيمة المحددة من قبل المستخدم خارج هذه الحدود، سيتم تطبيق الحد الأدنى أو الحد الأقصى الممكن.


**Returns:**
int - الدقة العمودية بوحدة DPI.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


يضبط الدقة العمودية للصور المولدة بوحدة النقاط في البوصة. يُستخدم هذا الخيار عند تصيير جداول البيانات إلى صيغ PNG أو JPEG فقط.


القيمة الافتراضية هي 96 DPI. الحد الأدنى الممكن هو 72 DPI، والحد الأقصى الممكن هو 600 DPI.
إذا كانت القيمة المحددة من قبل المستخدم خارج هذه الحدود، سيتم تطبيق الحد الأدنى أو الحد الأقصى الممكن.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | verticalResolution | int | الدقة العمودية بوحدة DPI. |
|

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


ينشئ مثيلاً جديدًا من  SpreadsheetOptions  لتصrender مناطق الطباعة وفواصل الصفحات. للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.

### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


ينشئ مثيلاً جديدًا من الفئة  SpreadsheetOptions  لتصrender مناطق الطباعة فقط. للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.

