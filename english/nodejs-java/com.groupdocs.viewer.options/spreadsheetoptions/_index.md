---
title: SpreadsheetOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Provides options for rendering spreadsheets.
type: docs
weight: 29
url: /nodejs-java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Provides options for rendering spreadsheets.

The SpreadsheetOptions class encapsulates various settings and parameters that can be used to control the rendering of spreadsheet files (such as Excel or CSV files) in the GroupDocs.Viewer component.

Example usage:

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
## Methods

| Method | Description |
| --- | --- |
| [isRenderByPageBreaks()](#isRenderByPageBreaks--) | Determines whether the worksheet should be rendered by page breaks. |
| [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | Sets whether the worksheet should be rendered by page breaks. |
| [isDetectSeparator()](#isDetectSeparator--) | Detects the separator for CSV/TSV files. |
| [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | Sets whether to detect the separator for CSV/TSV files. |
| [forOnePagePerSheet()](#forOnePagePerSheet--) | Creates a new instance of  SpreadsheetOptions  class for rendering one sheet into one page. |
| [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Creates a new instance of  SpreadsheetOptions  class for rendering a sheet into multiple pages. |
| [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Initializes a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages. |
| [forRenderingPrintArea()](#forRenderingPrintArea--) | Initializes a new instance of the  SpreadsheetOptions  class for rendering print areas only. |
| [isOnePagePerSheet()](#isOnePagePerSheet--) | Indicates whether one sheet is rendered into one page. |
| [getCountRowsPerPage()](#getCountRowsPerPage--) | Gets the count of rows to include into each page when splitting the worksheet into pages. |
| [getCountColumnsPerPage()](#getCountColumnsPerPage--) | Gets the count of columns to include into each page when splitting the worksheet into pages. |
| [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | Sets the count of columns to include into each page when splitting the worksheet into pages. |
| [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Indicates whether only the print areas are rendered. |
| [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | When this option is enabled, a worksheet will be rendered by page breaks that fall within the print area. |
| [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | Sets whether to render a worksheet by page breaks that fall within the print area. |
| [isRenderGridLines()](#isRenderGridLines--) | Enables rendering of grid lines. |
| [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Enables or disables the rendering of grid lines. |
| [isSkipEmptyRows()](#isSkipEmptyRows--) | Indicates whether empty rows should be skipped during rendering. |
| [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Sets whether empty rows should be skipped during rendering. |
| [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Indicates whether empty columns should be skipped during rendering. |
| [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Sets whether empty columns should be skipped during rendering. |
| [isRenderHiddenRows()](#isRenderHiddenRows--) | Determines whether hidden rows should be rendered. |
| [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Sets whether hidden rows should be rendered. |
| [isRenderHeadings()](#isRenderHeadings--) | Checks if headings rendering is enabled. |
| [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | Enables headings rendering. |
| [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Enables hidden columns rendering. |
| [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Enables hidden columns rendering. |
| [getTextOverflowMode()](#getTextOverflowMode--) | Returns the text overflow mode for rendering spreadsheet documents into HTML. |
| [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | Sets the text overflow mode for rendering spreadsheet documents into HTML. |
| [getLeftMargin()](#getLeftMargin--) | To set left margin of the worksheet when converting to pdf if less than 0 then default convert value is used |
| [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | To set left margin of the worksheet when converting to pdf if less than 0 then default convert value is used |
| [getRightMargin()](#getRightMargin--) | To set right margin of the worksheet when converting to pdf if less than 0 then default convert value is used |
| [setRightMargin(double rightMargin)](#setRightMargin-double-) | To set right margin of the worksheet when converting to pdf if less than 0 then default convert value is used |
| [getTopMargin()](#getTopMargin--) | To set top margin of the worksheet when converting to pdf if less than 0 then default convert value is used |
| [setTopMargin(double topMargin)](#setTopMargin-double-) | To set top margin of the worksheet when converting to pdf if less than 0 then default convert value is used |
| [getBottomMargin()](#getBottomMargin--) | To set bottom margin of the worksheet when converting to pdf if less than 0 then default convert value is used |
| [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | To set bottom margin of the worksheet when converting to pdf if less than 0 then default convert value is used |
| [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | Initializes a new instance of  SpreadsheetOptions  for rendering print areas and page breaks. |
| [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Initializes a new instance of the  SpreadsheetOptions  class for rendering print areas only. |
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


Determines whether the worksheet should be rendered by page breaks.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Returns:**
boolean -  true  if the worksheet should be rendered by page breaks,  false  otherwise.
### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


Sets whether the worksheet should be rendered by page breaks.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| renderByPageBreaks | boolean |  true  if the worksheet should be rendered by page breaks,  false  otherwise. |

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


Detects the separator for CSV/TSV files.

**Returns:**
boolean -  true  if the separator should be automatically detected,  false  otherwise.
### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


Sets whether to detect the separator for CSV/TSV files.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| detectSeparator | boolean |  true  to automatically detect the separator,  false  otherwise. |

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Creates a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.
### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Creates a new instance of  SpreadsheetOptions  class for rendering a sheet into multiple pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| countRowsPerPage | int | The number of rows to include in each page. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.
### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Initializes a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| countRowsPerPage | int | The number of rows to include on each page. |
| countColumnsPerPage | int | The number of columns to include on each page. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.
### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Initializes a new instance of the  SpreadsheetOptions  class for rendering print areas only.

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.
### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


Indicates whether one sheet is rendered into one page.

**Returns:**
boolean -  true  if one sheet is rendered into one page;  false  otherwise.
### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


Gets the count of rows to include into each page when splitting the worksheet into pages.

**Returns:**
int - the count of rows to include into each page.
### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


Gets the count of columns to include into each page when splitting the worksheet into pages.

**Returns:**
int - the count of columns to include into each page.
### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


Sets the count of columns to include into each page when splitting the worksheet into pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| countColumnsPerPage | int | The count of columns to include into each page. |

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Indicates whether only the print areas are rendered.

**Returns:**
boolean -  true  if only the print areas are rendered,  false  otherwise.
### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


When this option is enabled, a worksheet will be rendered by page breaks that fall within the print area.

**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


Sets whether to render a worksheet by page breaks that fall within the print area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| renderingPrintAreaAndPageBreaks | boolean | Set to true to enable, false to disable. |

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Enables rendering of grid lines.

**Returns:**
boolean -  true  if grid lines are enabled,  false  otherwise.
### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Enables or disables the rendering of grid lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to enable grid lines rendering,  false  to disable it. |

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Indicates whether empty rows should be skipped during rendering.

**Returns:**
boolean -  true  if empty rows should be skipped,  false  otherwise.
### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Sets whether empty rows should be skipped during rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to skip empty rows,  false  otherwise. |

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Indicates whether empty columns should be skipped during rendering.

**Returns:**
boolean -  true  if empty columns are skipped,  false  otherwise.
### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Sets whether empty columns should be skipped during rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to skip empty columns,  false  otherwise. |

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Determines whether hidden rows should be rendered.

**Returns:**
boolean -  true  if hidden rows should be rendered,  false  otherwise.
### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Sets whether hidden rows should be rendered.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to enable rendering of hidden rows,  false  to disable it. |

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Checks if headings rendering is enabled.

**Returns:**
boolean -  true  if headings rendering is enabled,  false  otherwise.
### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


Enables headings rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| renderHeadings | boolean |  true  to enable headings rendering,  false  to disable. |

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Enables hidden columns rendering.

**Returns:**
boolean -  true  if hidden columns rendering is enabled,  false  otherwise.
### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Enables hidden columns rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  to enable hidden columns rendering,  false  to disable. |

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


Returns the text overflow mode for rendering spreadsheet documents into HTML.

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.
### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


Sets the text overflow mode for rendering spreadsheet documents into HTML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | The text overflow mode to be set. |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


To set left margin of the worksheet when converting to pdf if less than 0 then default convert value is used

**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


To set left margin of the worksheet when converting to pdf if less than 0 then default convert value is used

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


To set right margin of the worksheet when converting to pdf if less than 0 then default convert value is used

**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


To set right margin of the worksheet when converting to pdf if less than 0 then default convert value is used

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


To set top margin of the worksheet when converting to pdf if less than 0 then default convert value is used

**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


To set top margin of the worksheet when converting to pdf if less than 0 then default convert value is used

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


To set bottom margin of the worksheet when converting to pdf if less than 0 then default convert value is used

**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


To set bottom margin of the worksheet when converting to pdf if less than 0 then default convert value is used

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bottomMargin | double |  |

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


Initializes a new instance of  SpreadsheetOptions  for rendering print areas and page breaks.

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.
### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Initializes a new instance of the  SpreadsheetOptions  class for rendering print areas only.

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.
