---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "스프레드시트를 렌더링하기 위한 옵션을 제공합니다."
type: docs
weight: 31
url: /ko/java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

스프레드시트를 렌더링하기 위한 옵션을 제공합니다.


SpreadsheetOptions 클래스는 사용할 수 있는 다양한 설정 및 매개변수를 캡슐화합니다
GroupDocs.Viewer 구성 요소에서 스프레드시트 파일(예: Excel 또는 CSV 파일)의 렌더링을 제어합니다.
자세한 내용은 [Render spreadsheet files](../https://docs.groupdocs.com/viewer/java/render-spreadsheets/) 항목의 하위 항목을 참조하십시오.


사용 예시:

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


## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isRenderByPageBreaks()](#isRenderByPageBreaks--) | 워크시트가 페이지 구분으로 렌더링될지 여부를 결정합니다. |
|
|  | [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | 워크시트가 페이지 구분으로 렌더링될지 여부를 설정합니다. |
|
|  | [isDetectSeparator()](#isDetectSeparator--) | CSV/TSV 파일의 구분자를 감지합니다. |
|
|  | [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | CSV/TSV 파일의 구분자를 감지할지 여부를 설정합니다. |
|
|  | [forOnePagePerSheet()](#forOnePagePerSheet--) | 새 인스턴스를 생성합니다 |
SpreadsheetOptions
한 시트를 한 페이지에 렌더링하는 클래스입니다.
|
|  | [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | 새 인스턴스를 생성합니다 |
SpreadsheetOptions
시트를 여러 페이지에 렌더링하는 클래스입니다.
|
|  | [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | 새 인스턴스를 초기화합니다. |
SpreadsheetOptions
시트를 페이지에 렌더링하는 클래스입니다.
|
|  | [forRenderingPrintArea()](#forRenderingPrintArea--) | 새 인스턴스를 초기화합니다. |
SpreadsheetOptions
인쇄 영역만 렌더링하는 클래스입니다.
|
|  | [isOnePagePerSheet()](#isOnePagePerSheet--) | 한 시트가 한 페이지에 렌더링되는지 여부를 나타냅니다. |
|
|  | [getCountRowsPerPage()](#getCountRowsPerPage--) | 워크시트를 페이지로 분할할 때 각 페이지에 포함할 행 수를 가져옵니다. |
|
|  | [getCountColumnsPerPage()](#getCountColumnsPerPage--) | 워크시트를 페이지로 분할할 때 각 페이지에 포함할 열 수를 가져옵니다. |
|
|  | [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | 워크시트를 페이지로 분할할 때 각 페이지에 포함할 열 수를 설정합니다. |
|
|  | [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | 인쇄 영역만 렌더링되는지 여부를 나타냅니다. |
|
|  | [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | 이 옵션이 활성화되면 워크시트가 인쇄 영역 내에 있는 페이지 구분을 기준으로 렌더링됩니다. |
|
|  | [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | 인쇄 영역 내에 있는 페이지 구분을 기준으로 워크시트를 렌더링할지 여부를 설정합니다. |
|
|  | [isRenderGridLines()](#isRenderGridLines--) | 그리드 선 렌더링을 활성화합니다. |
|
|  | [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | 그리드 선 렌더링을 활성화하거나 비활성화합니다. |
|
|  | [isSkipEmptyRows()](#isSkipEmptyRows--) | 렌더링 중에 빈 행을 건너뛸지 여부를 나타냅니다. |
|
|  | [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | 렌더링 중에 빈 행을 건너뛸지 여부를 설정합니다. |
|
|  | [isSkipEmptyColumns()](#isSkipEmptyColumns--) | 렌더링 중에 빈 열을 건너뛸지 여부를 나타냅니다. |
|
|  | [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | 렌더링 중에 빈 열을 건너뛸지 여부를 설정합니다. |
|
|  | [isRenderHiddenRows()](#isRenderHiddenRows--) | 숨겨진 행을 렌더링할지 여부를 결정합니다. |
|
|  | [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | 숨겨진 행을 렌더링할지 여부를 설정합니다. |
|
|  | [isRenderHeadings()](#isRenderHeadings--) | 머리글 렌더링이 활성화되어 있는지 확인합니다. |
|
|  | [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | 머리글 렌더링을 활성화합니다. |
|
|  | [isRenderHiddenColumns()](#isRenderHiddenColumns--) | 숨겨진 열 렌더링을 활성화합니다. |
|
|  | [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | 숨겨진 열 렌더링을 활성화합니다. |
|
|  | [getTextOverflowMode()](#getTextOverflowMode--) | 스프레드시트 문서를 HTML로 렌더링하기 위한 텍스트 오버플로 모드를 반환합니다. |
|
|  | [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | 스프레드시트 문서를 HTML로 렌더링하기 위한 텍스트 오버플로 모드를 설정합니다. |
|
|  | [getLeftMargin()](#getLeftMargin--) | 워크시트를 PDF로 변환할 때 왼쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. |
|
|  | [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | 워크시트를 PDF로 변환할 때 왼쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. |
|
|  | [getRightMargin()](#getRightMargin--) | 워크시트를 PDF로 변환할 때 오른쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. |
|
|  | [setRightMargin(double rightMargin)](#setRightMargin-double-) | 워크시트를 PDF로 변환할 때 오른쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. |
|
|  | [getTopMargin()](#getTopMargin--) | 워크시트를 PDF로 변환할 때 위쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. |
|
|  | [setTopMargin(double topMargin)](#setTopMargin-double-) | 워크시트를 PDF로 변환할 때 위쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. |
|
|  | [getBottomMargin()](#getBottomMargin--) | 워크시트를 PDF로 변환할 때 아래쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. |
|
|  | [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | 워크시트를 PDF로 변환할 때 아래쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | 생성된 이미지의 수평 해상도를 인치당 도트(dpi) 단위로 가져오거나 설정합니다. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | 생성된 이미지의 수평 해상도를 인치당 도트(dpi) 단위로 설정합니다. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | 생성된 이미지의 수직 해상도를 인치당 도트(dpi) 단위로 가져오거나 설정합니다. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | 생성된 이미지의 수직 해상도를 인치당 도트(dpi) 단위로 설정합니다. |
|
|  | [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | 인쇄 영역 및 페이지 구분을 렌더링하기 위해  SpreadsheetOptions  의 새 인스턴스를 초기화합니다. |
|
|  | [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | 인쇄 영역만 렌더링하기 위해  SpreadsheetOptions  클래스의 새 인스턴스를 초기화합니다. |
|
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


워크시트가 페이지 구분으로 렌더링될지 여부를 결정합니다.


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Returns:**
boolean -  true  워크시트를 페이지 구분으로 렌더링해야 하는 경우,  false  그 외의 경우.

### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


워크시트가 페이지 구분으로 렌더링될지 여부를 설정합니다.


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | renderByPageBreaks | boolean | true  워크시트를 페이지 구분으로 렌더링해야 하는 경우,  false  그 외의 경우. |
|

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


CSV/TSV 파일의 구분자를 감지합니다.


자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator)를 참조하십시오.


**Returns:**
boolean -  true  구분자를 자동으로 감지해야 하는 경우,  false  그 외의 경우.

### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


CSV/TSV 파일의 구분자를 감지할지 여부를 설정합니다.


자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | detectSeparator | boolean | true  구분자를 자동으로 감지하도록,  false  그 외의 경우. |
|

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


새 인스턴스를 생성합니다
SpreadsheetOptions
한 시트를 한 페이지에 렌더링하는 클래스입니다.
자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page)를 참조하십시오.


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.

### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


새 인스턴스를 생성합니다
SpreadsheetOptions
시트를 여러 페이지에 렌더링하는 클래스입니다.
자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | countRowsPerPage | int | 각 페이지에 포함할 행 수. |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.

### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


새 인스턴스를 초기화합니다.
SpreadsheetOptions
시트를 페이지에 렌더링하는 클래스입니다.
자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | countRowsPerPage | int | 각 페이지에 포함할 행 수. |
|
|  | countColumnsPerPage | int | 각 페이지에 포함할 열 수. |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.

### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


새 인스턴스를 초기화합니다.
SpreadsheetOptions
인쇄 영역만 렌더링하는 클래스입니다.
자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area)를 참조하십시오.


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.

### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


한 시트가 한 페이지에 렌더링되는지 여부를 나타냅니다.


**Returns:**
boolean -  true  하나의 시트를 하나의 페이지로 렌더링하는 경우;  false  그 외의 경우.

### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


워크시트를 페이지로 분할할 때 각 페이지에 포함할 행 수를 가져옵니다.


자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows)를 참조하십시오.


**Returns:**
int - 각 페이지에 포함할 행 수.

### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


워크시트를 페이지로 분할할 때 각 페이지에 포함할 열 수를 가져옵니다.


자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns)를 참조하십시오.


**Returns:**
int - 각 페이지에 포함할 열 수.

### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


워크시트를 페이지로 분할할 때 각 페이지에 포함할 열 수를 설정합니다.


자세한 내용은 [문서](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns)를 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | countColumnsPerPage | int | 각 페이지에 포함할 열 수. |
|

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


인쇄 영역만 렌더링되는지 여부를 나타냅니다.


**Returns:**
boolean -  true  인쇄 영역만 렌더링하는 경우,  false  그 외의 경우.

### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


이 옵션이 활성화되면 워크시트가 인쇄 영역 내에 있는 페이지 구분을 기준으로 렌더링됩니다.


**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


인쇄 영역 내에 있는 페이지 구분을 기준으로 워크시트를 렌더링할지 여부를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | renderingPrintAreaAndPageBreaks | boolean | 활성화하려면 true 로 설정하고, 비활성화하려면 false 로 설정합니다. |
|

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


그리드 선 렌더링을 활성화합니다.


자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines)을(를) 참조하십시오.


**Returns:**
boolean - true이면 그리드 라인이 활성화되고, false이면 그렇지 않습니다.

### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


그리드 선 렌더링을 활성화하거나 비활성화합니다.


자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines)을(를) 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | true이면 그리드 라인 렌더링을 활성화하고, false이면 비활성화합니다. |
|

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


렌더링 중에 빈 행을 건너뛸지 여부를 나타냅니다.


자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns)을(를) 참조하십시오.


**Returns:**
boolean - true이면 빈 행을 건너뛰고, false이면 그렇지 않습니다.

### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


렌더링 중에 빈 행을 건너뛸지 여부를 설정합니다.


자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns)을(를) 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | true이면 빈 행을 건너뛰고, false이면 그렇지 않습니다. |
|

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


렌더링 중에 빈 열을 건너뛸지 여부를 나타냅니다.


자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns)을(를) 참조하십시오.


**Returns:**
boolean - true이면 빈 열을 건너뛰고, false이면 그렇지 않습니다.

### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


렌더링 중에 빈 열을 건너뛸지 여부를 설정합니다.


자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns)을(를) 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | true이면 빈 열을 건너뛰고, false이면 그렇지 않습니다. |
|

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


숨겨진 행을 렌더링할지 여부를 결정합니다.


자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns)을(를) 참조하십시오.


**Returns:**
boolean - true이면 숨겨진 행을 렌더링하고, false이면 그렇지 않습니다.

### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


숨겨진 행을 렌더링할지 여부를 설정합니다.


자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns)을(를) 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | true이면 숨겨진 행의 렌더링을 활성화하고, false이면 비활성화합니다. |
|

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


머리글 렌더링이 활성화되어 있는지 확인합니다.


자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings)을(를) 참조하십시오.


**Returns:**
boolean - true이면 머리글 렌더링이 활성화되고, false이면 그렇지 않습니다.

### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


머리글 렌더링을 활성화합니다.


자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings)을(를) 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | renderHeadings | boolean | true이면 머리글 렌더링을 활성화하고, false이면 비활성화합니다. |
|

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


숨겨진 열 렌더링을 활성화합니다.


자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns)을(를) 참조하십시오.


**Returns:**
boolean - true이면 숨겨진 열 렌더링이 활성화되고, false이면 그렇지 않습니다.

### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


숨겨진 열 렌더링을 활성화합니다.


자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns)을(를) 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | true이면 숨겨진 열 렌더링을 활성화하고, false이면 비활성화합니다. |
|

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


스프레드시트 문서를 HTML로 렌더링하기 위한 텍스트 오버플로 모드를 반환합니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow)을(를) 참조하십시오.


**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.

### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


스프레드시트 문서를 HTML로 렌더링하기 위한 텍스트 오버플로 모드를 설정합니다. 자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow)을(를) 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | 설정할 텍스트 오버플로 모드입니다. |
|

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


워크시트를 PDF로 변환할 때 왼쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다.


매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages)을(를) 참조하십시오.


**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


워크시트를 PDF로 변환할 때 왼쪽 여백을 설정합니다. 0보다 작으면 기본 변환 값이 사용됩니다.


매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages)을(를) 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


워크시트를 PDF로 변환할 때 오른쪽 여백을 설정합니다. 값이 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages)을(를) 참조하십시오.


**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


워크시트를 PDF로 변환할 때 오른쪽 여백을 설정합니다. 값이 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages)을(를) 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


워크시트를 PDF로 변환할 때 상단 여백을 설정합니다. 값이 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages)을(를) 참조하십시오.


**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


워크시트를 PDF로 변환할 때 상단 여백을 설정합니다. 값이 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages)을(를) 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


워크시트를 PDF로 변환할 때 하단 여백을 설정하려면 값이 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages)을 참조하십시오.


**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


워크시트를 PDF로 변환할 때 하단 여백을 설정하려면 값이 0보다 작으면 기본 변환 값이 사용됩니다. 매개변수가 0보다 작으면 기본값이 사용됩니다. 자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages)을 참조하십시오.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bottomMargin | double |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


생성된 이미지의 수평 해상도를 인치당 도트(DPI) 단위로 가져오거나 설정합니다. 이 옵션은 스프레드시트를 PNG 또는 JPEG 형식으로 렌더링할 때만 사용됩니다.


기본값은 96 DPI입니다. 최소 가능한 값은 72 DPI, 최대 가능한 값은 600 DPI입니다.
사용자가 지정한 값이 이러한 한계를 벗어나면 최소값 또는 최대값이 적용됩니다.


**Returns:**
int - 인치당 도트(DPI) 단위의 수평 해상도.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


생성된 이미지의 수평 해상도를 인치당 도트(DPI) 단위로 설정합니다. 이 옵션은 스프레드시트를 PNG 또는 JPEG 형식으로 렌더링할 때만 사용됩니다.


기본값은 96 DPI입니다. 최소 가능한 값은 72 DPI, 최대 가능한 값은 600 DPI입니다.
사용자가 지정한 값이 이러한 한계를 벗어나면 최소값 또는 최대값이 적용됩니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | horizontalResolution | int | 인치당 도트(DPI) 단위의 수평 해상도. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


생성된 이미지의 수직 해상도를 인치당 도트(DPI) 단위로 가져오거나 설정합니다. 이 옵션은 스프레드시트를 PNG 또는 JPEG 형식으로 렌더링할 때만 사용됩니다.


기본값은 96 DPI입니다. 최소 가능한 값은 72 DPI, 최대 가능한 값은 600 DPI입니다.
사용자가 지정한 값이 이러한 한계를 벗어나면 최소값 또는 최대값이 적용됩니다.


**Returns:**
int - 인치당 도트(DPI) 단위의 수직 해상도.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


생성된 이미지의 수직 해상도를 인치당 도트(DPI) 단위로 설정합니다. 이 옵션은 스프레드시트를 PNG 또는 JPEG 형식으로 렌더링할 때만 사용됩니다.


기본값은 96 DPI입니다. 최소 가능한 값은 72 DPI, 최대 가능한 값은 600 DPI입니다.
사용자가 지정한 값이 이러한 한계를 벗어나면 최소값 또는 최대값이 적용됩니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | verticalResolution | int | 인치당 도트(DPI) 단위의 수직 해상도. |
|

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


인쇄 영역 및 페이지 나누기를 렌더링하기 위해 SpreadsheetOptions의 새 인스턴스를 초기화합니다. 자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area)을 참조하십시오.


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.

### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


인쇄 영역만 렌더링하기 위해 SpreadsheetOptions 클래스의 새 인스턴스를 초기화합니다. 자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/)을 참조하십시오.


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.

