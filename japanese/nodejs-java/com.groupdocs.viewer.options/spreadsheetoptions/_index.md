---
title: "SpreadsheetOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "スプレッドシートのレンダリングオプションを提供します。"
type: docs
weight: 31
url: /ja/nodejs-java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

スプレッドシートのレンダリングオプションを提供します。

SpreadsheetOptionsクラスは、GroupDocs.Viewerコンポーネントでスプレッドシートファイル（ExcelやCSVファイルなど）のレンダリングを制御するために使用できるさまざまな設定やパラメータをカプセル化します。詳細については、[Render spreadsheet files][]トピックの子項目をご覧ください。

使用例:

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
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isRenderByPageBreaks()](#isRenderByPageBreaks--) | ワークシートを改ページ単位でレンダリングするかどうかを決定します。 |
| [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | ワークシートを改ページでレンダリングするかどうかを設定します。 |
| [isDetectSeparator()](#isDetectSeparator--) | CSV/TSV ファイルの区切り文字を検出します。 |
| [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | CSV/TSV ファイルの区切り文字を検出するかどうかを設定します。 |
| [forOnePagePerSheet()](#forOnePagePerSheet--) | 1 つのシートを 1 ページにレンダリングするための  SpreadsheetOptions  クラスの新しいインスタンスを作成します。 |
| [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | シートを複数ページにレンダリングするための  SpreadsheetOptions  クラスの新しいインスタンスを作成します。 |
| [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | シートをページにレンダリングするための  SpreadsheetOptions  クラスの新しいインスタンスを初期化します。 |
| [forRenderingPrintArea()](#forRenderingPrintArea--) | 印刷領域のみをレンダリングするための  SpreadsheetOptions  クラスの新しいインスタンスを初期化します。 |
| [isOnePagePerSheet()](#isOnePagePerSheet--) | 1 つのシートが 1 ページにレンダリングされるかどうかを示します。 |
| [getCountRowsPerPage()](#getCountRowsPerPage--) | ワークシートをページに分割する際、各ページに含める行数を取得します。 |
| [getCountColumnsPerPage()](#getCountColumnsPerPage--) | ワークシートをページに分割する際、各ページに含める列数を取得します。 |
| [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | ワークシートをページに分割する際、各ページに含める列数を設定します。 |
| [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | 印刷領域のみがレンダリングされるかどうかを示します。 |
| [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | このオプションが有効な場合、ワークシートは印刷領域内の改ページでレンダリングされます。 |
| [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | 印刷領域内の改ページでワークシートをレンダリングするかどうかを設定します。 |
| [isRenderGridLines()](#isRenderGridLines--) | グリッド線のレンダリングを有効にします。 |
| [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | グリッド線のレンダリングを有効または無効にします。 |
| [isSkipEmptyRows()](#isSkipEmptyRows--) | レンダリング中に空の行をスキップするかどうかを示します。 |
| [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | レンダリング中に空の行をスキップするかどうかを設定します。 |
| [isSkipEmptyColumns()](#isSkipEmptyColumns--) | レンダリング中に空の列をスキップするかどうかを示します。 |
| [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | レンダリング中に空の列をスキップするかどうかを設定します。 |
| [isRenderHiddenRows()](#isRenderHiddenRows--) | 非表示行をレンダリングするかどうかを決定します。 |
| [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | 非表示行をレンダリングするかどうかを設定します。 |
| [isRenderHeadings()](#isRenderHeadings--) | 見出しのレンダリングが有効かどうかを確認します。 |
| [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | 見出しのレンダリングを有効にします。 |
| [isRenderHiddenColumns()](#isRenderHiddenColumns--) | 非表示列のレンダリングを有効にします。 |
| [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | 非表示列のレンダリングを有効にします。 |
| [getTextOverflowMode()](#getTextOverflowMode--) | スプレッドシート ドキュメントを HTML にレンダリングする際のテキスト オーバーフロー モードを返します。 |
| [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | スプレッドシート ドキュメントを HTML にレンダリングする際のテキスト オーバーフロー モードを設定します。 |
| [getLeftMargin()](#getLeftMargin--) | ワークシートを PDF に変換する際に左余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。 |
| [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | ワークシートを PDF に変換する際に左余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。 |
| [getRightMargin()](#getRightMargin--) | ワークシートを PDF に変換する際に右余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。パラメータが 0 未満の場合、デフォルト値が使用されます。 |
| [setRightMargin(double rightMargin)](#setRightMargin-double-) | ワークシートを PDF に変換する際に右余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。パラメータが 0 未満の場合、デフォルト値が使用されます。 |
| [getTopMargin()](#getTopMargin--) | ワークシートを PDF に変換する際に上余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。パラメータが 0 未満の場合、デフォルト値が使用されます。 |
| [setTopMargin(double topMargin)](#setTopMargin-double-) | ワークシートを PDF に変換する際に上余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。パラメータが 0 未満の場合、デフォルト値が使用されます。 |
| [getBottomMargin()](#getBottomMargin--) | ワークシートを PDF に変換する際に下余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。パラメータが 0 未満の場合、デフォルト値が使用されます。 |
| [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | ワークシートを PDF に変換する際に下余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。パラメータが 0 未満の場合、デフォルト値が使用されます。 |
| [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | 印刷領域と改ページをレンダリングするための SpreadsheetOptions の新しいインスタンスを初期化します。 |
| [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | 印刷領域のみをレンダリングするための  SpreadsheetOptions  クラスの新しいインスタンスを初期化します。 |
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


ワークシートを改ページ単位でレンダリングするかどうかを決定します。

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Returns:**
boolean -  true  true はワークシートが改ページでレンダリングされる場合、false はそれ以外の場合です。
### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


ワークシートを改ページでレンダリングするかどうかを設定します。

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| renderByPageBreaks | boolean | true  ワークシートが改ページでレンダリングされる場合、false  それ以外の場合です。 |

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


CSV/TSV ファイルの区切り文字を検出します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Returns:**
boolean -  true  区切り文字が自動的に検出される場合、false  それ以外の場合です。
### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


CSV/TSV ファイルの区切り文字を検出するかどうかを設定します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| detectSeparator | boolean | true  区切り文字を自動的に検出する場合、false  それ以外の場合です。 |

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


1 つのシートを 1 ページにレンダリングするための  SpreadsheetOptions  クラスの新しいインスタンスを作成します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.
### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


シートを複数ページにレンダリングするための  SpreadsheetOptions  クラスの新しいインスタンスを作成します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| countRowsPerPage | int | 各ページに含める行数です。 |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.
### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


シートをページにレンダリングするための  SpreadsheetOptions  クラスの新しいインスタンスを初期化します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| countRowsPerPage | int | 各ページに含める行数です。 |
| countColumnsPerPage | int | 各ページに含める列数です。 |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.
### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


印刷領域のみをレンダリングするための  SpreadsheetOptions  クラスの新しいインスタンスを初期化します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.
### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


1 つのシートが 1 ページにレンダリングされるかどうかを示します。

**Returns:**
boolean -  true  1 つのシートが 1 ページにレンダリングされる場合、false  それ以外の場合です。
### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


ワークシートをページに分割する際、各ページに含める行数を取得します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Returns:**
int - 各ページに含める行数です。
### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


ワークシートをページに分割する際、各ページに含める列数を取得します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Returns:**
int - 各ページに含める列数です。
### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


ワークシートをページに分割する際、各ページに含める列数を設定します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| countColumnsPerPage | int | 各ページに含める列数です。 |

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


印刷領域のみがレンダリングされるかどうかを示します。

**Returns:**
boolean -  true  印刷領域のみがレンダリングされる場合、false  それ以外の場合です。
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
| renderingPrintAreaAndPageBreaks | boolean | true に設定すると有効、false に設定すると無効です。 |

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


グリッド線のレンダリングを有効にします。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Returns:**
boolean -  true  がグリッドラインが有効な場合、  false  がそれ以外の場合です。
### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


グリッド線のレンダリングを有効または無効にします。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean | true  でグリッドラインの描画を有効にし、  false  で無効にします。 |

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


レンダリング中に空の行をスキップするかどうかを示します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  が空の行をスキップすべき場合、  false  がそれ以外の場合です。
### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


レンダリング中に空の行をスキップするかどうかを設定します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean | true  で空の行をスキップし、  false  でそれ以外です。 |

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


レンダリング中に空の列をスキップするかどうかを示します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  が空の列をスキップする場合、  false  がそれ以外の場合です。
### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


レンダリング中に空の列をスキップするかどうかを設定します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean | true  で空の列をスキップし、  false  でそれ以外です。 |

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


非表示行をレンダリングするかどうかを決定します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  が非表示行を描画すべき場合、  false  がそれ以外の場合です。
### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


非表示行をレンダリングするかどうかを設定します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean | true  で非表示行の描画を有効にし、  false  で無効にします。 |

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


見出しのレンダリングが有効かどうかを確認します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Returns:**
boolean -  true  が見出しの描画が有効な場合、  false  がそれ以外の場合です。
### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


見出しのレンダリングを有効にします。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| renderHeadings | boolean | true  で見出しの描画を有効にし、  false  で無効にします。 |

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


非表示列のレンダリングを有効にします。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  が非表示列の描画が有効な場合、  false  がそれ以外の場合です。
### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


非表示列のレンダリングを有効にします。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean | true  で非表示列の描画を有効にし、  false  で無効にします。 |

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


スプレッドシート ドキュメントを HTML にレンダリングする際のテキスト オーバーフロー モードを返します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.
### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


スプレッドシートドキュメントをHTMLにレンダリングするためのテキストオーバーフローモードを設定します。詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | 設定するテキストオーバーフローモードです。 |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


ワークシートを PDF に変換する際に左余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。

パラメーターが0未満の場合、デフォルト値が使用されます。詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


ワークシートを PDF に変換する際に左余白を設定します。0 未満の場合はデフォルトの変換値が使用されます。

パラメーターが0未満の場合、デフォルト値が使用されます。詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


PDFに変換する際のワークシートの右余白を設定します。0未満の場合はデフォルトの変換値が使用されます。パラメーターが0未満の場合もデフォルト値が使用されます。詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


PDFに変換する際のワークシートの右余白を設定します。0未満の場合はデフォルトの変換値が使用されます。パラメーターが0未満の場合もデフォルト値が使用されます。詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


PDFに変換する際のワークシートの上余白を設定します。0未満の場合はデフォルトの変換値が使用されます。パラメーターが0未満の場合もデフォルト値が使用されます。詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


PDFに変換する際のワークシートの上余白を設定します。0未満の場合はデフォルトの変換値が使用されます。パラメーターが0未満の場合もデフォルト値が使用されます。詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


PDFに変換する際のワークシートの下余白を設定します。0未満の場合はデフォルトの変換値が使用されます。パラメーターが0未満の場合もデフォルト値が使用されます。詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


PDFに変換する際のワークシートの下余白を設定します。0未満の場合はデフォルトの変換値が使用されます。パラメーターが0未満の場合もデフォルト値が使用されます。詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bottomMargin | double |  |

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


印刷領域と改ページをレンダリングするために SpreadsheetOptions の新しいインスタンスを初期化します。詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.
### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


印刷領域のみをレンダリングするために SpreadsheetOptions クラスの新しいインスタンスを初期化します。詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.
