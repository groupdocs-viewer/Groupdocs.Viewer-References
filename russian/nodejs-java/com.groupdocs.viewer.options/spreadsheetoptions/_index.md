---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Предоставляет параметры для рендеринга электронных таблиц."
type: docs
weight: 31
url: /ru/nodejs-java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Предоставляет параметры для рендеринга электронных таблиц.

Класс SpreadsheetOptions инкапсулирует различные настройки и параметры, которые могут использоваться для управления рендерингом файлов электронных таблиц (таких как Excel или CSV) в компоненте GroupDocs.Viewer. Подробности см. в дочерних темах [Render spreadsheet files][].

Пример использования:

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
## Методы

| Метод | Описание |
| --- | --- |
| [isRenderByPageBreaks()](#isRenderByPageBreaks--) | Определяет, следует ли рендерить лист по разрывам страниц. |
| [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | Устанавливает, следует ли отображать лист по разрывам страниц. |
| [isDetectSeparator()](#isDetectSeparator--) | Определяет разделитель для файлов CSV/TSV. |
| [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | Устанавливает, следует ли определять разделитель для файлов CSV/TSV. |
| [forOnePagePerSheet()](#forOnePagePerSheet--) | Создаёт новый экземпляр класса  SpreadsheetOptions  для отображения одного листа на одной странице. |
| [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Создаёт новый экземпляр класса  SpreadsheetOptions  для отображения листа на нескольких страницах. |
| [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Инициализирует новый экземпляр класса  SpreadsheetOptions  для отображения листа по страницам. |
| [forRenderingPrintArea()](#forRenderingPrintArea--) | Инициализирует новый экземпляр класса  SpreadsheetOptions  только для отображения областей печати. |
| [isOnePagePerSheet()](#isOnePagePerSheet--) | Указывает, отображается ли один лист на одной странице. |
| [getCountRowsPerPage()](#getCountRowsPerPage--) | Получает количество строк, включаемых в каждую страницу при разбивке листа на страницы. |
| [getCountColumnsPerPage()](#getCountColumnsPerPage--) | Получает количество столбцов, включаемых в каждую страницу при разбивке листа на страницы. |
| [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | Устанавливает количество столбцов, включаемых в каждую страницу при разбивке листа на страницы. |
| [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Указывает, отображаются ли только области печати. |
| [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | Когда эта опция включена, лист будет отображаться по разрывам страниц, находящимся внутри области печати. |
| [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | Устанавливает, следует ли отображать лист по разрывам страниц, находящимся внутри области печати. |
| [isRenderGridLines()](#isRenderGridLines--) | Включает отображение линий сетки. |
| [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Включает или отключает отображение линий сетки. |
| [isSkipEmptyRows()](#isSkipEmptyRows--) | Указывает, следует ли пропускать пустые строки при отображении. |
| [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Устанавливает, следует ли пропускать пустые строки при отображении. |
| [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Указывает, следует ли пропускать пустые столбцы при отображении. |
| [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Устанавливает, следует ли пропускать пустые столбцы при отображении. |
| [isRenderHiddenRows()](#isRenderHiddenRows--) | Определяет, следует ли отображать скрытые строки. |
| [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Устанавливает, следует ли отображать скрытые строки. |
| [isRenderHeadings()](#isRenderHeadings--) | Проверяет, включено ли отображение заголовков. |
| [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | Включает отображение заголовков. |
| [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Включает отображение скрытых столбцов. |
| [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Включает отображение скрытых столбцов. |
| [getTextOverflowMode()](#getTextOverflowMode--) | Возвращает режим переполнения текста при рендеринге электронных таблиц в HTML. |
| [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | Устанавливает режим переполнения текста при рендеринге электронных таблиц в HTML. |
| [getLeftMargin()](#getLeftMargin--) | Установить левый отступ листа при конвертации в PDF, если значение меньше 0, используется значение по умолчанию |
| [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | Установить левый отступ листа при конвертации в PDF, если значение меньше 0, используется значение по умолчанию |
| [getRightMargin()](#getRightMargin--) | Установить правый отступ листа при конвертации в PDF, если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. |
| [setRightMargin(double rightMargin)](#setRightMargin-double-) | Установить правый отступ листа при конвертации в PDF, если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. |
| [getTopMargin()](#getTopMargin--) | Установить верхний отступ листа при конвертации в PDF, если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. |
| [setTopMargin(double topMargin)](#setTopMargin-double-) | Установить верхний отступ листа при конвертации в PDF, если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. |
| [getBottomMargin()](#getBottomMargin--) | Установить нижний отступ листа при конвертации в PDF, если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. |
| [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | Установить нижний отступ листа при конвертации в PDF, если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. |
| [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | Инициализирует новый экземпляр  SpreadsheetOptions  для рендеринга областей печати и разрывов страниц. |
| [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Инициализирует новый экземпляр класса  SpreadsheetOptions  только для отображения областей печати. |
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


Определяет, следует ли рендерить лист по разрывам страниц.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Returns:**
boolean -  true  если лист должен рендериться по разрывам страниц,  false  в противном случае.
### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


Устанавливает, следует ли отображать лист по разрывам страниц.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderByPageBreaks | boolean | true  если лист должен рендериться по разрывам страниц,  false  в противном случае. |

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


Определяет разделитель для файлов CSV/TSV.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Returns:**
boolean -  true  если разделитель должен определяться автоматически,  false  в противном случае.
### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


Устанавливает, следует ли определять разделитель для файлов CSV/TSV.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| detectSeparator | boolean | true  для автоматического определения разделителя,  false  в противном случае. |

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Создаёт новый экземпляр класса  SpreadsheetOptions  для отображения одного листа на одной странице.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.
### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Создаёт новый экземпляр класса  SpreadsheetOptions  для отображения листа на нескольких страницах.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| countRowsPerPage | int | Количество строк, включаемых в каждую страницу. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.
### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Инициализирует новый экземпляр класса  SpreadsheetOptions  для отображения листа по страницам.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| countRowsPerPage | int | Количество строк, включаемых на каждую страницу. |
| countColumnsPerPage | int | Количество столбцов, включаемых на каждую страницу. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.
### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Инициализирует новый экземпляр класса  SpreadsheetOptions  только для отображения областей печати.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.
### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


Указывает, отображается ли один лист на одной странице.

**Returns:**
boolean -  true  если один лист рендерится в одну страницу;  false  в противном случае.
### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


Получает количество строк, включаемых в каждую страницу при разбивке листа на страницы.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Returns:**
int - количество строк, включаемых в каждую страницу.
### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


Получает количество столбцов, включаемых в каждую страницу при разбивке листа на страницы.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Returns:**
int - количество столбцов, включаемых в каждую страницу.
### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


Устанавливает количество столбцов, включаемых в каждую страницу при разбивке листа на страницы.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| countColumnsPerPage | int | Количество столбцов, включаемых в каждую страницу. |

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Указывает, отображаются ли только области печати.

**Returns:**
boolean -  true  если рендерятся только области печати,  false  в противном случае.
### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


Когда эта опция включена, лист будет отображаться по разрывам страниц, находящимся внутри области печати.

**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


Устанавливает, следует ли отображать лист по разрывам страниц, находящимся внутри области печати.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderingPrintAreaAndPageBreaks | boolean | Установите true для включения, false для отключения. |

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Включает отображение линий сетки.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Returns:**
boolean -  true  если линии сетки включены,  false  в противном случае.
### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Включает или отключает отображение линий сетки.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | true  чтобы включить отрисовку линий сетки,  false  чтобы отключить её. |

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Указывает, следует ли пропускать пустые строки при отображении.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  если пустые строки следует пропускать,  false  в противном случае.
### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Устанавливает, следует ли пропускать пустые строки при отображении.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | true  чтобы пропускать пустые строки,  false  в противном случае. |

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Указывает, следует ли пропускать пустые столбцы при отображении.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  если пустые столбцы пропускаются,  false  в противном случае.
### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Устанавливает, следует ли пропускать пустые столбцы при отображении.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | true  чтобы пропускать пустые столбцы,  false  в противном случае. |

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Определяет, следует ли отображать скрытые строки.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  если скрытые строки должны быть отрисованы,  false  в противном случае.
### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Устанавливает, следует ли отображать скрытые строки.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | true  чтобы включить отрисовку скрытых строк,  false  чтобы отключить её. |

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Проверяет, включено ли отображение заголовков.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Returns:**
boolean -  true  если отрисовка заголовков включена,  false  в противном случае.
### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


Включает отображение заголовков.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| renderHeadings | boolean | true  чтобы включить отрисовку заголовков,  false  чтобы отключить. |

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Включает отображение скрытых столбцов.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  если отрисовка скрытых столбцов включена,  false  в противном случае.
### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Включает отображение скрытых столбцов.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | true  чтобы включить отрисовку скрытых столбцов,  false  чтобы отключить. |

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


Возвращает режим переполнения текста при рендеринге электронных таблиц в HTML.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.
### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


Устанавливает режим переполнения текста при отрисовке электронных таблиц в HTML. Для подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | Режим переполнения текста, который необходимо установить. |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Установить левый отступ листа при конвертации в PDF, если значение меньше 0, используется значение по умолчанию

Если параметр меньше 0, используется значение по умолчанию. Для подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


Установить левый отступ листа при конвертации в PDF, если значение меньше 0, используется значение по умолчанию

Если параметр меньше 0, используется значение по умолчанию. Для подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Чтобы установить правый отступ листа при конвертации в pdf, если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. Для подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


Чтобы установить правый отступ листа при конвертации в pdf, если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. Для подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Чтобы установить верхний отступ листа при конвертации в pdf, если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. Для подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


Чтобы установить верхний отступ листа при конвертации в pdf, если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. Для подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Чтобы установить нижний отступ листа при конвертации в pdf, если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. Для подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


Чтобы установить нижний отступ листа при конвертации в pdf, если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. Для подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bottomMargin | double |  |

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


Инициализирует новый экземпляр  SpreadsheetOptions  для отрисовки областей печати и разрывов страниц. Для подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.
### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Инициализирует новый экземпляр класса  SpreadsheetOptions  только для отрисовки областей печати. Для подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.
