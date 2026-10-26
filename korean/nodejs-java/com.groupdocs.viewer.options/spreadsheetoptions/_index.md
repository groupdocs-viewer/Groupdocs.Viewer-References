---
title: "SpreadsheetOptions"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "스프레드시트를 렌더링하기 위한 옵션을 제공합니다."
type: docs
weight: 31
url: /ko/nodejs-java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

스프레드시트를 렌더링하기 위한 옵션을 제공합니다.

SpreadsheetOptions 클래스는 GroupDocs.Viewer 구성 요소에서 스프레드시트 파일(예: Excel 또는 CSV 파일)의 렌더링을 제어하는 데 사용할 수 있는 다양한 설정 및 매개변수를 캡슐화합니다. 자세한 내용은 [Render spreadsheet files][] 항목의 하위 항목을 참조하십시오.

예시 사용법:

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
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isRenderByPageBreaks()](#isRenderByPageBreaks--) | 워크시트가 페이지 구분에 따라 렌더링되어야 하는지 여부를 결정합니다. |
| [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | 워크시트가 페이지 구분을 기준으로 렌더링될지 여부를 설정합니다. |
| [isDetectSeparator()](#isDetectSeparator--) | CSV/TSV 파일의 구분자를 감지합니다. |
| [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | CSV/TSV 파일의 구분자를 감지할지 여부를 설정합니다. |
| [forOnePagePerSheet()](#forOnePagePerSheet--) | 한 시트를 한 페이지로 렌더링하기 위해 SpreadsheetOptions 클래스를 새 인스턴스로 생성합니다. |
| [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | 시트를 여러 페이지로 렌더링하기 위해 SpreadsheetOptions 클래스를 새 인스턴스로 생성합니다. |
| [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | 시트를 페이지로 렌더링하기 위해 SpreadsheetOptions 클래스의 새 인스턴스를 초기화합니다. |
| [forRenderingPrintArea()](#forRenderingPrintArea--) | 인쇄 영역만 렌더링하기 위해 SpreadsheetOptions 클래스의 새 인스턴스를 초기화합니다. |
| [isOnePagePerSheet()](#isOnePagePerSheet--) | 한 시트를 한 페이지로 렌더링할지 여부를 나타냅니다. |
| [getCountRowsPerPage()](#getCountRowsPerPage--) | 워크시트를 페이지로 분할할 때 각 페이지에 포함할 행 수를 가져옵니다. |
| [getCountColumnsPerPage()](#getCountColumnsPerPage--) | 워크시트를 페이지로 분할할 때 각 페이지에 포함할 열 수를 가져옵니다. |
| [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | 워크시트를 페이지로 분할할 때 각 페이지에 포함할 열 수를 설정합니다. |
| [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | 인쇄 영역만 렌더링되는지 여부를 나타냅니다. |
| [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | 이 옵션을 활성화하면 워크시트가 인쇄 영역 내의 페이지 구분에 따라 렌더링됩니다. |
| [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | 인쇄 영역 내의 페이지 구분에 따라 워크시트를 렌더링할지 여부를 설정합니다. |
| [isRenderGridLines()](#isRenderGridLines--) | 그리드 라인 렌더링을 활성화합니다. |
| [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | 그리드 라인 렌더링을 활성화하거나 비활성화합니다. |
| [isSkipEmptyRows()](#isSkipEmptyRows--) | 렌더링 중에 빈 행을 건너뛸지 여부를 나타냅니다. |
| [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | 렌더링 중에 빈 행을 건너뛸지 여부를 설정합니다. |
| [isSkipEmptyColumns()](#isSkipEmptyColumns--) | 렌더링 중에 빈 열을 건너뛸지 여부를 나타냅니다. |
| [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | 렌더링 중에 빈 열을 건너뛸지 여부를 설정합니다. |
| [isRenderHiddenRows()](#isRenderHiddenRows--) | 숨겨진 행을 렌더링할지 여부를 결정합니다. |
| [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | 숨겨진 행을 렌더링할지 여부를 설정합니다. |
| [isRenderHeadings()](#isRenderHeadings--) | 헤딩 렌더링이 활성화되어 있는지 확인합니다. |
| [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | 헤딩 렌더링을 활성화합니다. |
| [isRenderHiddenColumns()](#isRenderHiddenColumns--) | 숨겨진 열 렌더링을 활성화합니다. |
| [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | 숨겨진 열 렌더링을 활성화합니다. |
| [getTextOverflowMode()](#getTextOverflowMode--) | 스프레드시트 문서를 HTML로 렌더링하기 위한 텍스트 오버플로 모드를 반환합니다. |
| [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | 스프레드시트 문서를 HTML로 렌더링하기 위한 텍스트 오버플로 모드를 설정합니다. |
| [getLeftMargin()](#getLeftMargin--) | 워크시트를 PDF로 변환할 때 왼쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. |
| [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | 워크시트를 PDF로 변환할 때 왼쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. |
| [getRightMargin()](#getRightMargin--) | 워크시트를 PDF로 변환할 때 오른쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본 값이 사용됩니다. |
| [setRightMargin(double rightMargin)](#setRightMargin-double-) | 워크시트를 PDF로 변환할 때 오른쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본 값이 사용됩니다. |
| [getTopMargin()](#getTopMargin--) | 워크시트를 PDF로 변환할 때 위쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본 값이 사용됩니다. |
| [setTopMargin(double topMargin)](#setTopMargin-double-) | 워크시트를 PDF로 변환할 때 위쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본 값이 사용됩니다. |
| [getBottomMargin()](#getBottomMargin--) | 워크시트를 PDF로 변환할 때 아래쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본 값이 사용됩니다. |
| [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | 워크시트를 PDF로 변환할 때 아래쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본 값이 사용됩니다. |
| [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | 인쇄 영역 및 페이지 구분을 렌더링하기 위해 SpreadsheetOptions의 새 인스턴스를 초기화합니다. |
| [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | 인쇄 영역만 렌더링하기 위해 SpreadsheetOptions 클래스의 새 인스턴스를 초기화합니다. |
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


워크시트가 페이지 구분에 따라 렌더링되어야 하는지 여부를 결정합니다.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Returns:**
boolean -  true  워크시트를 페이지 구분으로 렌더링해야 하는 경우 true, 그렇지 않은 경우 false.
### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


워크시트가 페이지 구분을 기준으로 렌더링될지 여부를 설정합니다.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| renderByPageBreaks | boolean | true  워크시트를 페이지 구분으로 렌더링해야 하면 true, 그렇지 않으면 false. |

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


CSV/TSV 파일의 구분자를 감지합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Returns:**
boolean -  true  구분자를 자동으로 감지해야 하면 true, 그렇지 않으면 false.
### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


CSV/TSV 파일의 구분자를 감지할지 여부를 설정합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| detectSeparator | boolean | true  구분자를 자동으로 감지하려면, false  그렇지 않으면. |

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


한 시트를 한 페이지로 렌더링하기 위해 SpreadsheetOptions 클래스를 새 인스턴스로 생성합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.
### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


시트를 여러 페이지로 렌더링하기 위해 SpreadsheetOptions 클래스를 새 인스턴스로 생성합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| countRowsPerPage | int | 각 페이지에 포함할 행 수. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.
### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


시트를 페이지로 렌더링하기 위해 SpreadsheetOptions 클래스의 새 인스턴스를 초기화합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| countRowsPerPage | int | 각 페이지에 포함할 행 수. |
| countColumnsPerPage | int | 각 페이지에 포함할 열 수. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.
### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


인쇄 영역만 렌더링하기 위해 SpreadsheetOptions 클래스의 새 인스턴스를 초기화합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.
### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


한 시트를 한 페이지로 렌더링할지 여부를 나타냅니다.

**Returns:**
boolean -  true  한 시트를 한 페이지에 렌더링하면 true; 그렇지 않으면 false.
### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


워크시트를 페이지로 분할할 때 각 페이지에 포함할 행 수를 가져옵니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Returns:**
int - 각 페이지에 포함할 행 수.
### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


워크시트를 페이지로 분할할 때 각 페이지에 포함할 열 수를 가져옵니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Returns:**
int - 각 페이지에 포함할 열 수.
### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


워크시트를 페이지로 분할할 때 각 페이지에 포함할 열 수를 설정합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| countColumnsPerPage | int | 각 페이지에 포함할 열 수. |

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


인쇄 영역만 렌더링되는지 여부를 나타냅니다.

**Returns:**
boolean -  true  인쇄 영역만 렌더링하면 true, 그렇지 않으면 false.
### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


이 옵션을 활성화하면 워크시트가 인쇄 영역 내의 페이지 구분에 따라 렌더링됩니다.

**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


인쇄 영역 내의 페이지 구분에 따라 워크시트를 렌더링할지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| renderingPrintAreaAndPageBreaks | boolean | true 로 설정하면 활성화되고, false 로 설정하면 비활성화됩니다. |

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


그리드 라인 렌더링을 활성화합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Returns:**
boolean -  true  그리드 라인이 활성화된 경우,  false  그 외.
### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


그리드 라인 렌더링을 활성화하거나 비활성화합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | true  그리드 라인 렌더링을 활성화하려면,  false  비활성화하려면. |

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


렌더링 중에 빈 행을 건너뛸지 여부를 나타냅니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  빈 행을 건너뛰어야 하는 경우,  false  그 외.
### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


렌더링 중에 빈 행을 건너뛸지 여부를 설정합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | true  빈 행을 건너뛰려면,  false  그 외. |

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


렌더링 중에 빈 열을 건너뛸지 여부를 나타냅니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  빈 열을 건너뛰는 경우,  false  그 외.
### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


렌더링 중에 빈 열을 건너뛸지 여부를 설정합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | true  빈 열을 건너뛰려면,  false  그 외. |

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


숨겨진 행을 렌더링할지 여부를 결정합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  숨겨진 행을 렌더링해야 하는 경우,  false  그 외.
### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


숨겨진 행을 렌더링할지 여부를 설정합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | true  숨겨진 행 렌더링을 활성화하려면,  false  비활성화하려면. |

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


헤딩 렌더링이 활성화되어 있는지 확인합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Returns:**
boolean -  true  머리글 렌더링이 활성화된 경우,  false  그 외.
### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


헤딩 렌더링을 활성화합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| renderHeadings | boolean | true  머리글 렌더링을 활성화하려면,  false  비활성화하려면. |

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


숨겨진 열 렌더링을 활성화합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  숨겨진 열 렌더링이 활성화된 경우,  false  그 외.
### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


숨겨진 열 렌더링을 활성화합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean | true  숨겨진 열 렌더링을 활성화하려면,  false  비활성화하려면. |

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


스프레드시트 문서를 HTML로 렌더링하기 위한 텍스트 오버플로 모드를 반환합니다.

자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.
### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


스프레드시트 문서를 HTML로 렌더링하기 위한 텍스트 오버플로 모드를 설정합니다. 자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | 설정할 텍스트 오버플로 모드입니다. |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


워크시트를 PDF로 변환할 때 왼쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다.

매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


워크시트를 PDF로 변환할 때 왼쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다.

매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


워크시트를 PDF로 변환할 때 오른쪽 여백을 설정합니다. 값이 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


워크시트를 PDF로 변환할 때 오른쪽 여백을 설정합니다. 값이 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


워크시트를 PDF로 변환할 때 위쪽 여백을 설정합니다. 값이 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


워크시트를 PDF로 변환할 때 위쪽 여백을 설정합니다. 값이 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


워크시트를 PDF로 변환할 때 아래쪽 여백을 설정합니다. 값이 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


워크시트를 PDF로 변환할 때 아래쪽 여백을 설정합니다. 값이 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bottomMargin | double |  |

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


인쇄 영역 및 페이지 나누기를 렌더링하기 위해  SpreadsheetOptions  의 새 인스턴스를 초기화합니다. 자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.
### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


인쇄 영역만 렌더링하기 위해  SpreadsheetOptions  클래스의 새 인스턴스를 초기화합니다. 자세한 내용은 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.
