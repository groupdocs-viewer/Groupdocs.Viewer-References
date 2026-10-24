---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "提供用于渲染电子表格的选项。"
type: docs
weight: 31
url: /zh/java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

提供用于渲染电子表格的选项。


SpreadsheetOptions 类封装了可用于的各种设置和参数
用于控制在 GroupDocs.Viewer 组件中渲染电子表格文件（如 Excel 或 CSV 文件）。
有关详细信息，请参阅 [Render spreadsheet files](../https://docs.groupdocs.com/viewer/java/render-spreadsheets/) 主题的子项。


示例用法：

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


## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isRenderByPageBreaks()](#isRenderByPageBreaks--) | 确定工作表是否应按分页符进行渲染。 |
|
|  | [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | 设置工作表是否应按分页符进行渲染。 |
|
|  | [isDetectSeparator()](#isDetectSeparator--) | 检测 CSV/TSV 文件的分隔符。 |
|
|  | [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | 设置是否检测 CSV/TSV 文件的分隔符。 |
|
|  | [forOnePagePerSheet()](#forOnePagePerSheet--) | 创建一个新的实例 |
SpreadsheetOptions
用于将单个工作表渲染为单页的类。
|
|  | [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | 创建一个新的实例 |
SpreadsheetOptions
用于将工作表渲染为多页的类。
|
|  | [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | 初始化一个新的实例 |
SpreadsheetOptions
用于将工作表渲染为页面的类。
|
|  | [forRenderingPrintArea()](#forRenderingPrintArea--) | 初始化一个新的实例 |
SpreadsheetOptions
仅用于渲染打印区域的类。
|
|  | [isOnePagePerSheet()](#isOnePagePerSheet--) | 指示是否将单个工作表渲染为单页。 |
|
|  | [getCountRowsPerPage()](#getCountRowsPerPage--) | 获取在将工作表拆分为页面时，每页包含的行数。 |
|
|  | [getCountColumnsPerPage()](#getCountColumnsPerPage--) | 获取在将工作表拆分为页面时，每页包含的列数。 |
|
|  | [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | 设置在将工作表拆分为页面时，每页包含的列数。 |
|
|  | [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | 指示是否仅渲染打印区域。 |
|
|  | [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | 启用此选项后，工作表将按位于打印区域内的分页符进行渲染。 |
|
|  | [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | 设置是否按位于打印区域内的分页符渲染工作表。 |
|
|  | [isRenderGridLines()](#isRenderGridLines--) | 启用网格线渲染。 |
|
|  | [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | 启用或禁用网格线渲染。 |
|
|  | [isSkipEmptyRows()](#isSkipEmptyRows--) | 指示在渲染过程中是否应跳过空行。 |
|
|  | [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | 设置在渲染过程中是否跳过空行。 |
|
|  | [isSkipEmptyColumns()](#isSkipEmptyColumns--) | 指示在渲染过程中是否应跳过空列。 |
|
|  | [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | 设置在渲染过程中是否跳过空列。 |
|
|  | [isRenderHiddenRows()](#isRenderHiddenRows--) | 确定是否应渲染隐藏行。 |
|
|  | [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | 设置是否渲染隐藏行。 |
|
|  | [isRenderHeadings()](#isRenderHeadings--) | 检查是否已启用标题渲染。 |
|
|  | [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | 启用标题渲染。 |
|
|  | [isRenderHiddenColumns()](#isRenderHiddenColumns--) | 启用隐藏列渲染。 |
|
|  | [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | 启用隐藏列渲染。 |
|
|  | [getTextOverflowMode()](#getTextOverflowMode--) | 返回将电子表格文档渲染为 HTML 的文本溢出模式。 |
|
|  | [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | 设置将电子表格文档渲染为 HTML 的文本溢出模式。 |
|
|  | [getLeftMargin()](#getLeftMargin--) | 设置工作表转换为 PDF 时的左边距，如果小于 0，则使用默认转换值。 |
|
|  | [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | 设置工作表转换为 PDF 时的左边距，如果小于 0，则使用默认转换值。 |
|
|  | [getRightMargin()](#getRightMargin--) | 设置工作表转换为 PDF 时的右边距，如果小于 0，则使用默认转换值。如果参数小于 0，则使用默认值。 |
|
|  | [setRightMargin(double rightMargin)](#setRightMargin-double-) | 设置工作表转换为 PDF 时的右边距，如果小于 0，则使用默认转换值。如果参数小于 0，则使用默认值。 |
|
|  | [getTopMargin()](#getTopMargin--) | 设置工作表转换为 PDF 时的上边距，如果小于 0，则使用默认转换值。如果参数小于 0，则使用默认值。 |
|
|  | [setTopMargin(double topMargin)](#setTopMargin-double-) | 设置工作表转换为 PDF 时的上边距，如果小于 0，则使用默认转换值。如果参数小于 0，则使用默认值。 |
|
|  | [getBottomMargin()](#getBottomMargin--) | 设置工作表转换为 PDF 时的下边距，如果小于 0，则使用默认转换值。如果参数小于 0，则使用默认值。 |
|
|  | [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | 设置工作表转换为 PDF 时的下边距，如果小于 0，则使用默认转换值。如果参数小于 0，则使用默认值。 |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | 获取或设置生成图像的水平分辨率（每英寸点数）。 |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | 设置生成图像的水平分辨率（每英寸点数）。 |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | 获取或设置生成图像的垂直分辨率（每英寸点数）。 |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | 设置生成图像的垂直分辨率（每英寸点数）。 |
|
|  | [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | 初始化  SpreadsheetOptions  的新实例，用于渲染打印区域和分页符。 |
|
|  | [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | 初始化  SpreadsheetOptions  类的新实例，仅用于渲染打印区域。 |
|
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


确定工作表是否应按分页符进行渲染。


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Returns:**
布尔型 -  true  如果工作表应按分页符渲染，则为 true；否则为 false。

### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


设置工作表是否应按分页符进行渲染。


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | renderByPageBreaks | boolean | true  如果工作表应按分页符渲染，则为 true；否则为 false。 |
|

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


检测 CSV/TSV 文件的分隔符。


有关详细信息，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator)。


**Returns:**
布尔型 -  true  如果应自动检测分隔符，则为 true；否则为 false。

### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


设置是否检测 CSV/TSV 文件的分隔符。


有关详细信息，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | detectSeparator | boolean | true  自动检测分隔符，false  否则。 |
|

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


创建一个新的实例
SpreadsheetOptions
用于将单个工作表渲染为单页的类。
有关详细信息，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page)。


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.

### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


创建一个新的实例
SpreadsheetOptions
用于将工作表渲染为多页的类。
有关详细信息，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | countRowsPerPage | int | 每页包含的行数。 |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.

### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


初始化一个新的实例
SpreadsheetOptions
用于将工作表渲染为页面的类。
有关详细信息，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | countRowsPerPage | int | 每页包含的行数。 |
|
|  | countColumnsPerPage | int | 每页包含的列数。 |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.

### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


初始化一个新的实例
SpreadsheetOptions
仅用于渲染打印区域的类。
有关详细信息，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area)。


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.

### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


指示是否将单个工作表渲染为单页。


**Returns:**
布尔型 -  true  如果一张工作表渲染为一页，则为 true；否则为 false。

### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


获取在将工作表拆分为页面时，每页包含的行数。


有关详细信息，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows)。


**Returns:**
int - 每页包含的行数。

### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


获取在将工作表拆分为页面时，每页包含的列数。


有关详细信息，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns)。


**Returns:**
int - 每页包含的列数。

### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


设置在将工作表拆分为页面时，每页包含的列数。


有关详细信息，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | countColumnsPerPage | int | 每页包含的列数。 |
|

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


指示是否仅渲染打印区域。


**Returns:**
布尔型 -  true  如果仅渲染打印区域，则为 true；否则为 false。

### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


启用此选项后，工作表将按位于打印区域内的分页符进行渲染。


**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


设置是否按位于打印区域内的分页符渲染工作表。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | renderingPrintAreaAndPageBreaks | boolean | 设置为 true 以启用，false 以禁用。 |
|

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


启用网格线渲染。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines)。


**Returns:**
布尔 -  true  表示网格线已启用，  false  表示未启用。

### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


启用或禁用网格线渲染。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true  启用网格线渲染，  false  禁用它。 |
|

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


指示在渲染过程中是否应跳过空行。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns)。


**Returns:**
布尔 -  true  表示应跳过空行，  false  表示否则。

### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


设置在渲染过程中是否跳过空行。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true  跳过空行，  false  否则。 |
|

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


指示在渲染过程中是否应跳过空列。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns)。


**Returns:**
布尔 -  true  表示跳过空列，  false  表示否则。

### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


设置在渲染过程中是否跳过空列。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true  跳过空列，  false  否则。 |
|

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


确定是否应渲染隐藏行。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns)。


**Returns:**
布尔 -  true  表示应渲染隐藏行，  false  表示否则。

### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


设置是否渲染隐藏行。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true  启用隐藏行的渲染，  false  禁用它。 |
|

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


检查是否已启用标题渲染。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings)。


**Returns:**
布尔 -  true  表示标题渲染已启用，  false  表示否则。

### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


启用标题渲染。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | renderHeadings | boolean | true  启用标题渲染，  false  禁用。 |
|

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


启用隐藏列渲染。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns)。


**Returns:**
布尔 -  true  表示隐藏列渲染已启用，  false  表示否则。

### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


启用隐藏列渲染。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true  启用隐藏列渲染，  false  禁用。 |
|

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


返回将电子表格文档渲染为 HTML 的文本溢出模式。
有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow)。


**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.

### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


设置将电子表格文档渲染为 HTML 时的文本溢出模式。有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | 要设置的文本溢出模式。 |
|

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


设置工作表转换为 PDF 时的左边距，如果小于 0，则使用默认转换值。


如果参数小于 0，则使用默认值。有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages)。


**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


设置工作表转换为 PDF 时的左边距，如果小于 0，则使用默认转换值。


如果参数小于 0，则使用默认值。有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


在将工作表转换为 PDF 时设置右边距；如果小于 0，则使用默认转换值。如果参数小于 0，则使用默认值。有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages)。


**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


在将工作表转换为 PDF 时设置右边距；如果小于 0，则使用默认转换值。如果参数小于 0，则使用默认值。有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


在将工作表转换为 PDF 时设置上边距；如果小于 0，则使用默认转换值。如果参数小于 0，则使用默认值。有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages)。


**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


在将工作表转换为 PDF 时设置上边距；如果小于 0，则使用默认转换值。如果参数小于 0，则使用默认值。有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


在将工作表转换为 PDF 时设置底部边距，如果小于 0 则使用默认的转换值。如果参数小于 0，则使用默认值。有关详细信息，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


在将工作表转换为 PDF 时设置底部边距，如果小于 0 则使用默认的转换值。如果参数小于 0，则使用默认值。有关详细信息，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bottomMargin | double |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


获取或设置生成图像的水平分辨率（以每英寸点数为单位）。此选项仅在将电子表格渲染为 PNG 或 JPEG 格式时使用。


默认值为 96 DPI。最小可能值为 72 DPI，最大可能值为 600 DPI。
如果用户指定的值超出这些限制，将使用最小或最大可能值。


**Returns:**
int - 水平分辨率（单位为 DPI）。

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


设置生成图像的水平分辨率（以每英寸点数为单位）。此选项仅在将电子表格渲染为 PNG 或 JPEG 格式时使用。


默认值为 96 DPI。最小可能值为 72 DPI，最大可能值为 600 DPI。
如果用户指定的值超出这些限制，将使用最小或最大可能值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | horizontalResolution | int | 水平分辨率（单位为 DPI）。 |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


获取或设置生成图像的垂直分辨率（以每英寸点数为单位）。此选项仅在将电子表格渲染为 PNG 或 JPEG 格式时使用。


默认值为 96 DPI。最小可能值为 72 DPI，最大可能值为 600 DPI。
如果用户指定的值超出这些限制，将使用最小或最大可能值。


**Returns:**
int - 垂直分辨率（单位为 DPI）。

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


设置生成图像的垂直分辨率（以每英寸点数为单位）。此选项仅在将电子表格渲染为 PNG 或 JPEG 格式时使用。


默认值为 96 DPI。最小可能值为 72 DPI，最大可能值为 600 DPI。
如果用户指定的值超出这些限制，将使用最小或最大可能值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | verticalResolution | int | 垂直分辨率（单位为 DPI）。 |
|

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


初始化一个新的 SpreadsheetOptions 实例，用于渲染打印区域和分页符。有关详细信息，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.

### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


初始化一个新的 SpreadsheetOptions 类实例，仅用于渲染打印区域。有关详细信息，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.

