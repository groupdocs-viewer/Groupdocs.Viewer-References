---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "スプレッドシートのレンダリングオプションを提供します。"
type: docs
weight: 31
url: /ja/java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

スプレッドシートのレンダリングオプションを提供します。


SpreadsheetOptions クラスは、使用できるさまざまな設定とパラメータをカプセル化します
GroupDocs.Viewer コンポーネントでスプレッドシート ファイル（Excel や CSV ファイルなど）のレンダリングを制御するためです。
詳細については、[Render spreadsheet files](../https://docs.groupdocs.com/viewer/java/render-spreadsheets/) トピックの子項目をご覧ください。


使用例:

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


## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isRenderByPageBreaks()](#isRenderByPageBreaks--) | ワークシートを改ページでレンダリングするかどうかを決定します。 |
|
|  | [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | ワークシートを改ページでレンダリングするかどうかを設定します。 |
|
|  | [isDetectSeparator()](#isDetectSeparator--) | CSV/TSV ファイルの区切り文字を検出します。 |
|
|  | [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | CSV/TSV ファイルの区切り文字を検出するかどうかを設定します。 |
|
|  | [forOnePagePerSheet()](#forOnePagePerSheet--) | 新しいインスタンスを作成します |
SpreadsheetOptions
1 つのシートを 1 ページにレンダリングするクラスです。
|
|  | [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | 新しいインスタンスを作成します |
SpreadsheetOptions
シートを複数ページにレンダリングするクラスです。
|
|  | [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | 新しいインスタンスを初期化します |
SpreadsheetOptions
シートをページにレンダリングするクラスです。
|
|  | [forRenderingPrintArea()](#forRenderingPrintArea--) | 新しいインスタンスを初期化します |
SpreadsheetOptions
印刷領域のみをレンダリングするクラスです。
|
|  | [isOnePagePerSheet()](#isOnePagePerSheet--) | 1 つのシートが 1 ページにレンダリングされるかどうかを示します。 |
|
|  | [getCountRowsPerPage()](#getCountRowsPerPage--) | ワークシートをページに分割する際、各ページに含める行数を取得します。 |
|
|  | [getCountColumnsPerPage()](#getCountColumnsPerPage--) | ワークシートをページに分割する際、各ページに含める列数を取得します。 |
|
|  | [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | ワークシートをページに分割する際、各ページに含める列数を設定します。 |
|
|  | [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | 印刷領域のみがレンダリングされるかどうかを示します。 |
|
|  | [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | このオプションが有効な場合、ワークシートは印刷領域内の改ページでレンダリングされます。 |
|
|  | [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | 印刷領域内の改ページでワークシートをレンダリングするかどうかを設定します。 |
|
|  | [isRenderGridLines()](#isRenderGridLines--) | グリッド線のレンダリングを有効にします。 |
|
|  | [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | グリッド線のレンダリングを有効化または無効化します。 |
|
|  | [isSkipEmptyRows()](#isSkipEmptyRows--) | レンダリング中に空の行をスキップするかどうかを示します。 |
|
|  | [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | レンダリング中に空の行をスキップするかどうかを設定します。 |
|
|  | [isSkipEmptyColumns()](#isSkipEmptyColumns--) | レンダリング中に空の列をスキップするかどうかを示します。 |
|
|  | [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | レンダリング中に空の列をスキップするかどうかを設定します。 |
|
|  | [isRenderHiddenRows()](#isRenderHiddenRows--) | 非表示の行をレンダリングするかどうかを決定します。 |
|
|  | [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | 非表示の行をレンダリングするかどうかを設定します。 |
|
|  | [isRenderHeadings()](#isRenderHeadings--) | 見出しのレンダリングが有効かどうかを確認します。 |
|
|  | [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | 見出しのレンダリングを有効にします。 |
|
|  | [isRenderHiddenColumns()](#isRenderHiddenColumns--) | 非表示列のレンダリングを有効にします。 |
|
|  | [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | 非表示列のレンダリングを有効にします。 |
|
|  | [getTextOverflowMode()](#getTextOverflowMode--) | スプレッドシートドキュメントを HTML にレンダリングする際のテキストオーバーフローモードを返します。 |
|
|  | [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | スプレッドシートドキュメントを HTML にレンダリングする際のテキストオーバーフローモードを設定します。 |
|
|  | [getLeftMargin()](#getLeftMargin--) | ワークシートを PDF に変換する際の左余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。 |
|
|  | [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | ワークシートを PDF に変換する際の左余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。 |
|
|  | [getRightMargin()](#getRightMargin--) | ワークシートを PDF に変換する際の右余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。パラメーターが 0 未満の場合、デフォルト値が使用されます。 |
|
|  | [setRightMargin(double rightMargin)](#setRightMargin-double-) | ワークシートを PDF に変換する際の右余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。パラメーターが 0 未満の場合、デフォルト値が使用されます。 |
|
|  | [getTopMargin()](#getTopMargin--) | ワークシートを PDF に変換する際の上余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。パラメーターが 0 未満の場合、デフォルト値が使用されます。 |
|
|  | [setTopMargin(double topMargin)](#setTopMargin-double-) | ワークシートを PDF に変換する際の上余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。パラメーターが 0 未満の場合、デフォルト値が使用されます。 |
|
|  | [getBottomMargin()](#getBottomMargin--) | ワークシートを PDF に変換する際の下余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。パラメーターが 0 未満の場合、デフォルト値が使用されます。 |
|
|  | [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | ワークシートを PDF に変換する際の下余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。パラメーターが 0 未満の場合、デフォルト値が使用されます。 |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | 生成された画像の水平解像度（dpi）を取得または設定します。 |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | 生成された画像の水平解像度（dpi）を設定します。 |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | 生成された画像の垂直解像度（dpi）を取得または設定します。 |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | 生成された画像の垂直解像度（dpi）を設定します。 |
|
|  | [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | 印刷エリアとページ区切りのレンダリング用に SpreadsheetOptions の新しいインスタンスを初期化します。 |
|
|  | [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | 印刷エリアのみのレンダリング用に SpreadsheetOptions クラスの新しいインスタンスを初期化します。 |
|
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


ワークシートを改ページでレンダリングするかどうかを決定します。


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Returns:**
boolean - ページ区切りでワークシートをレンダリングする場合は true、そうでない場合は false。

### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


ワークシートを改ページでレンダリングするかどうかを設定します。


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | renderByPageBreaks | boolean | true  - ページ区切りでワークシートをレンダリングする場合、false  - それ以外の場合。 |
|

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


CSV/TSV ファイルの区切り文字を検出します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator) を参照してください。


**Returns:**
boolean - 区切り文字を自動的に検出する場合は true、そうでない場合は false。

### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


CSV/TSV ファイルの区切り文字を検出するかどうかを設定します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | detectSeparator | boolean | true は自動的に区切り文字を検出し、false はそれ以外です。 |
|

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


新しいインスタンスを作成します
SpreadsheetOptions
1 つのシートを 1 ページにレンダリングするクラスです。
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page) を参照してください。


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.

### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


新しいインスタンスを作成します
SpreadsheetOptions
シートを複数ページにレンダリングするクラスです。
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | countRowsPerPage | int | 各ページに含める行数。 |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.

### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


新しいインスタンスを初期化します
SpreadsheetOptions
シートをページにレンダリングするクラスです。
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | countRowsPerPage | int | 各ページに含める行数。 |
|
|  | countColumnsPerPage | int | 各ページに含める列の数。 |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.

### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


新しいインスタンスを初期化します
SpreadsheetOptions
印刷領域のみをレンダリングするクラスです。
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area) を参照してください。


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.

### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


1 つのシートが 1 ページにレンダリングされるかどうかを示します。


**Returns:**
boolean - true は1枚のシートが1ページにレンダリングされる場合、false はそれ以外の場合です。

### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


ワークシートをページに分割する際、各ページに含める行数を取得します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows) を参照してください。


**Returns:**
int - 各ページに含める行数。

### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


ワークシートをページに分割する際、各ページに含める列数を取得します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns) を参照してください。


**Returns:**
int - 各ページに含める列数。

### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


ワークシートをページに分割する際、各ページに含める列数を設定します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | countColumnsPerPage | int | 各ページに含める列の数。 |
|

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


印刷領域のみがレンダリングされるかどうかを示します。


**Returns:**
boolean - true は印刷領域のみがレンダリングされる場合、false はそれ以外の場合です。

### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


このオプションが有効な場合、ワークシートは印刷領域内の改ページでレンダリングされます。


**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


印刷領域内の改ページでワークシートをレンダリングするかどうかを設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | renderingPrintAreaAndPageBreaks | boolean | 有効にするには true、無効にするには false を設定します。 |
|

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


グリッド線のレンダリングを有効にします。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines) を参照してください。


**Returns:**
boolean - true はグリッドラインが有効な場合、false はそれ以外の場合です。

### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


グリッド線のレンダリングを有効化または無効化します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | true はグリッドラインの描画を有効にし、false は無効にします。 |
|

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


レンダリング中に空の行をスキップするかどうかを示します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns) を参照してください。


**Returns:**
boolean - true は空の行をスキップすべき場合、false はそれ以外の場合です。

### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


レンダリング中に空の行をスキップするかどうかを設定します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | true は空の行をスキップし、false はそれ以外です。 |
|

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


レンダリング中に空の列をスキップするかどうかを示します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns) を参照してください。


**Returns:**
boolean - true は空の列がスキップされる場合、false はそれ以外の場合です。

### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


レンダリング中に空の列をスキップするかどうかを設定します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | true は空の列をスキップし、false はそれ以外です。 |
|

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


非表示の行をレンダリングするかどうかを決定します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns) を参照してください。


**Returns:**
boolean - 隠し行をレンダリングする場合は true、そうでない場合は false。

### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


非表示の行をレンダリングするかどうかを設定します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | true は隠し行のレンダリングを有効にし、false は無効にします。 |
|

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


見出しのレンダリングが有効かどうかを確認します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings) を参照してください。


**Returns:**
boolean - 見出しのレンダリングが有効な場合は true、そうでない場合は false。

### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


見出しのレンダリングを有効にします。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | renderHeadings | boolean | true は見出しのレンダリングを有効にし、false は無効にします。 |
|

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


非表示列のレンダリングを有効にします。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns) を参照してください。


**Returns:**
boolean - 隠し列のレンダリングが有効な場合は true、そうでない場合は false。

### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


非表示列のレンダリングを有効にします。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | true は隠し列のレンダリングを有効にし、false は無効にします。 |
|

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


スプレッドシートドキュメントを HTML にレンダリングする際のテキストオーバーフローモードを返します。
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow) を参照してください。


**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.

### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


スプレッドシートドキュメントを HTML にレンダリングする際のテキストオーバーフローモードを設定します。詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | 設定するテキストオーバーフローモードです。 |
|

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


ワークシートを PDF に変換する際の左余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。


パラメーターが 0 未満の場合、既定値が使用されます。詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) を参照してください。


**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


ワークシートを PDF に変換する際の左余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。


パラメーターが 0 未満の場合、既定値が使用されます。詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


PDF に変換する際のワークシートの右余白を設定します。0 未満の場合は既定の変換値が使用されます。パラメーターが 0 未満の場合も既定値が使用されます。詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) を参照してください。


**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


PDF に変換する際のワークシートの右余白を設定します。0 未満の場合は既定の変換値が使用されます。パラメーターが 0 未満の場合も既定値が使用されます。詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


PDF に変換する際のワークシートの上余白を設定します。0 未満の場合は既定の変換値が使用されます。パラメーターが 0 未満の場合も既定値が使用されます。詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) を参照してください。


**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


PDF に変換する際のワークシートの上余白を設定します。0 未満の場合は既定の変換値が使用されます。パラメーターが 0 未満の場合も既定値が使用されます。詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


PDF に変換する際のワークシートの下余白を設定します。0 未満の場合は既定の変換値が使用されます。パラメーターが 0 未満の場合も既定値が使用されます。詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) を参照してください。


**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


PDF に変換する際のワークシートの下余白を設定します。0 未満の場合は既定の変換値が使用されます。パラメーターが 0 未満の場合も既定値が使用されます。詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bottomMargin | double |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


生成された画像の水平解像度（dpi）を取得または設定します。このオプションは、スプレッドシートを PNG または JPEG 形式にレンダリングする場合にのみ使用されます。


既定値は 96 DPI です。最小可能値は 72 DPI、最大可能値は 600 DPI です。
ユーザーが指定した値がこれらの範囲外の場合、最小または最大の可能な値が適用されます。


**Returns:**
int - 水平解像度（DPI）です。

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


生成された画像の水平解像度を DPI（ドット毎インチ）で設定します。このオプションはスプレッドシートを PNG または JPEG 形式でレンダリングする場合にのみ使用されます。


既定値は 96 DPI です。最小可能値は 72 DPI、最大可能値は 600 DPI です。
ユーザーが指定した値がこれらの範囲外の場合、最小または最大の可能な値が適用されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | horizontalResolution | int | 水平解像度（DPI）です。 |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


生成された画像の垂直解像度を DPI（ドット毎インチ）で取得または設定します。このオプションはスプレッドシートを PNG または JPEG 形式でレンダリングする場合にのみ使用されます。


既定値は 96 DPI です。最小可能値は 72 DPI、最大可能値は 600 DPI です。
ユーザーが指定した値がこれらの範囲外の場合、最小または最大の可能な値が適用されます。


**Returns:**
int - 垂直解像度（DPI）です。

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


生成された画像の垂直解像度を DPI（ドット毎インチ）で設定します。このオプションはスプレッドシートを PNG または JPEG 形式でレンダリングする場合にのみ使用されます。


既定値は 96 DPI です。最小可能値は 72 DPI、最大可能値は 600 DPI です。
ユーザーが指定した値がこれらの範囲外の場合、最小または最大の可能な値が適用されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | verticalResolution | int | 垂直解像度（DPI）です。 |
|

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


印刷領域とページブレークのレンダリング用に SpreadsheetOptions の新しいインスタンスを初期化します。詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area) を参照してください。


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.

### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


印刷領域のみのレンダリング用に SpreadsheetOptions クラスの新しいインスタンスを初期化します。詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/) を参照してください。


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.

