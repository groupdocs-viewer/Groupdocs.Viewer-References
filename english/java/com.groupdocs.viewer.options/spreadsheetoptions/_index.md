---
title: SpreadsheetOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering spreadsheets.
type: docs
weight: 27
url: /java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Provides options for rendering spreadsheets.
## Methods

| Method | Description |
| --- | --- |
| [isRenderByPageBreaks()](#isRenderByPageBreaks--) | When this option is enabled a worksheet will be rendered by page breaks. |
| [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | When this option is enabled a worksheet will be rendered by page breaks. |
| [isDetectSeparator()](#isDetectSeparator--) | Detect separator (for CSV/TSV files). |
| [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | Detect separator (for CSV/TSV files). |
| [forOnePagePerSheet()](#forOnePagePerSheet--) | Initializes new instance of [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) class for rendering whole sheet into page. |
| [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Initializes new instance of [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) for rendering sheet into pages. |
| [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Initializes new instance of  for rendering sheet into pages. |
| [forRenderingPrintArea()](#forRenderingPrintArea--) | Initializes new instance of [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) for rendering print areas only. |
| [isOnePagePerSheet()](#isOnePagePerSheet--) | Indicates that one sheet is rendered into one page. |
| [getCountRowsPerPage()](#getCountRowsPerPage--) | The rows count to include into each page when splitting worksheet into pages. |
| [getCountColumnsPerPage()](#getCountColumnsPerPage--) | The columns count to include into each page when splitting worksheet into pages. |
| [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | The columns count to include into each page when splitting worksheet into pages. |
| [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Indicates that only print areas are rendered. |
| [isRenderGridLines()](#isRenderGridLines--) | Enables grid lines rendering. |
| [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Enables grid lines rendering. |
| [isSkipEmptyRows()](#isSkipEmptyRows--) | Disables empty rows rendering. |
| [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Disables empty rows rendering. |
| [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Disables empty columns rendering. |
| [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Disables empty columns rendering. |
| [isRenderHiddenRows()](#isRenderHiddenRows--) | Enables hidden rows rendering. |
| [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Enables hidden rows rendering. |
| [isRenderHeadings()](#isRenderHeadings--) | Is headings rendering enabled. |
| [setRenderHeadings(boolean mRenderHeadings)](#setRenderHeadings-boolean-) | Enables headings rendering. |
| [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Enables hidden columns rendering. |
| [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Enables hidden columns rendering. |
| [getTextOverflowMode()](#getTextOverflowMode--) | The text overflow mode for rendering spreadsheet documents into HTML. |
| [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | The text overflow mode for rendering spreadsheet documents into HTML. |
| [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Initializes new instance of  for rendering print areas only. |
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


When this option is enabled a worksheet will be rendered by page breaks. The behaviour is the same as you're printing a spreadsheet in Excel.

**Returns:**
boolean
### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


When this option is enabled a worksheet will be rendered by page breaks. The behaviour is the same as you're printing a spreadsheet in Excel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| renderByPageBreaks | boolean |  |

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


Detect separator (for CSV/TSV files).

**Returns:**
boolean
### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


Detect separator (for CSV/TSV files).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| detectSeparator | boolean |  |

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Initializes new instance of [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) class for rendering whole sheet into page.

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) class for rendering one sheet into one page.
### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Initializes new instance of [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) for rendering sheet into pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| countRowsPerPage | int | Rows count to include into each page. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) for rendering sheet into pages.
### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Initializes new instance of  for rendering sheet into pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| countRowsPerPage | int | Rows count to include into each page. |
| countColumnsPerPage | int | Columns count to include into each page. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  for rendering sheet into pages.
### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Initializes new instance of [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) for rendering print areas only.

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) for rendering print areas only.
### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


Indicates that one sheet is rendered into one page.

**Returns:**
boolean
### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


The rows count to include into each page when splitting worksheet into pages.

**Returns:**
int
### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


The columns count to include into each page when splitting worksheet into pages.

**Returns:**
int
### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


The columns count to include into each page when splitting worksheet into pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| countColumnsPerPage | int |  |

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Indicates that only print areas are rendered.

**Returns:**
boolean
### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Enables grid lines rendering.

**Returns:**
boolean
### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Enables grid lines rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Disables empty rows rendering.

**Returns:**
boolean
### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Disables empty rows rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Disables empty columns rendering.

**Returns:**
boolean
### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Disables empty columns rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Enables hidden rows rendering.

**Returns:**
boolean
### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Enables hidden rows rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Is headings rendering enabled.

**Returns:**
boolean - headings rendering enabled.
### setRenderHeadings(boolean mRenderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean mRenderHeadings)
```


Enables headings rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mRenderHeadings | boolean |  |

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Enables hidden columns rendering.

**Returns:**
boolean
### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Enables hidden columns rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


The text overflow mode for rendering spreadsheet documents into HTML.

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - The text overflow mode for rendering spreadsheet documents into HTML.
### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


The text overflow mode for rendering spreadsheet documents into HTML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | The text overflow mode for rendering spreadsheet documents into HTML. |

### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Initializes new instance of  for rendering print areas only.

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) for rendering by page breaks. The behaviour similar to printing in Excel.
