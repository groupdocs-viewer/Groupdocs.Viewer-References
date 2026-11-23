---
title: "SpreadsheetOptions"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Предоставляет параметры для визуализации электронных таблиц."
type: docs
weight: 31
url: /ru/java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Предоставляет параметры для визуализации электронных таблиц.


Класс SpreadsheetOptions инкапсулирует различные настройки и параметры, которые могут быть использованы
для управления рендерингом файлов электронных таблиц (например, Excel или CSV) в компоненте GroupDocs.Viewer.
Для получения подробностей см. дочерние элементы темы [Render spreadsheet files](../https://docs.groupdocs.com/viewer/java/render-spreadsheets/).


Пример использования:

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


## Методы

| Метод | Описание |
| --- | --- |
|  | [isRenderByPageBreaks()](#isRenderByPageBreaks--) | Определяет, следует ли рендерить лист по разрывам страниц. |
|
|  | [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | Устанавливает, следует ли рендерить лист по разрывам страниц. |
|
|  | [isDetectSeparator()](#isDetectSeparator--) | Определяет разделитель для файлов CSV/TSV. |
|
|  | [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | Устанавливает, следует ли определять разделитель для файлов CSV/TSV. |
|
|  | [forOnePagePerSheet()](#forOnePagePerSheet--) | Создаёт новый экземпляр |
SpreadsheetOptions
класс для рендеринга одного листа на одну страницу.
|
|  | [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Создаёт новый экземпляр |
SpreadsheetOptions
класс для рендеринга листа на несколько страниц.
|
|  | [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Инициализирует новый экземпляр |
SpreadsheetOptions
класс для рендеринга листа на страницы.
|
|  | [forRenderingPrintArea()](#forRenderingPrintArea--) | Инициализирует новый экземпляр |
SpreadsheetOptions
класс для рендеринга только областей печати.
|
|  | [isOnePagePerSheet()](#isOnePagePerSheet--) | Указывает, рендерится ли один лист на одну страницу. |
|
|  | [getCountRowsPerPage()](#getCountRowsPerPage--) | Получает количество строк, включаемых в каждую страницу при разбиении листа на страницы. |
|
|  | [getCountColumnsPerPage()](#getCountColumnsPerPage--) | Получает количество столбцов, включаемых в каждую страницу при разбиении листа на страницы. |
|
|  | [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | Устанавливает количество столбцов, включаемых в каждую страницу при разбиении листа на страницы. |
|
|  | [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Указывает, рендерятся ли только области печати. |
|
|  | [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | Когда эта опция включена, лист будет рендериться по разрывам страниц, находящимся внутри области печати. |
|
|  | [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | Устанавливает, рендерить ли лист по разрывам страниц, находящимся внутри области печати. |
|
|  | [isRenderGridLines()](#isRenderGridLines--) | Включает рендеринг линий сетки. |
|
|  | [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Включает или отключает рендеринг линий сетки. |
|
|  | [isSkipEmptyRows()](#isSkipEmptyRows--) | Указывает, следует ли пропускать пустые строки при рендеринге. |
|
|  | [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Устанавливает, следует ли пропускать пустые строки при рендеринге. |
|
|  | [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Указывает, следует ли пропускать пустые столбцы при рендеринге. |
|
|  | [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Устанавливает, следует ли пропускать пустые столбцы при рендеринге. |
|
|  | [isRenderHiddenRows()](#isRenderHiddenRows--) | Определяет, должны ли скрытые строки рендериться. |
|
|  | [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Устанавливает, должны ли скрытые строки рендериться. |
|
|  | [isRenderHeadings()](#isRenderHeadings--) | Проверяет, включён ли рендеринг заголовков. |
|
|  | [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | Включает рендеринг заголовков. |
|
|  | [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Включает рендеринг скрытых столбцов. |
|
|  | [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Включает рендеринг скрытых столбцов. |
|
|  | [getTextOverflowMode()](#getTextOverflowMode--) | Возвращает режим переполнения текста при рендеринге электронных таблиц в HTML. |
|
|  | [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | Устанавливает режим переполнения текста при рендеринге электронных таблиц в HTML. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Установить левый отступ листа при конвертации в PDF; если значение меньше 0, используется значение по умолчанию. |
|
|  | [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | Установить левый отступ листа при конвертации в PDF; если значение меньше 0, используется значение по умолчанию. |
|
|  | [getRightMargin()](#getRightMargin--) | Установить правый отступ листа при конвертации в PDF; если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. |
|
|  | [setRightMargin(double rightMargin)](#setRightMargin-double-) | Установить правый отступ листа при конвертации в PDF; если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. |
|
|  | [getTopMargin()](#getTopMargin--) | Установить верхний отступ листа при конвертации в PDF; если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. |
|
|  | [setTopMargin(double topMargin)](#setTopMargin-double-) | Установить верхний отступ листа при конвертации в PDF; если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Установить нижний отступ листа при конвертации в PDF; если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. |
|
|  | [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | Установить нижний отступ листа при конвертации в PDF; если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Получает или задает горизонтальное разрешение генерируемых изображений в точках на дюйм. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | Устанавливает горизонтальное разрешение генерируемых изображений в точках на дюйм. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Получает или задает вертикальное разрешение генерируемых изображений в точках на дюйм. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | Устанавливает вертикальное разрешение генерируемых изображений в точках на дюйм. |
|
|  | [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | Инициализирует новый экземпляр  SpreadsheetOptions  для отображения областей печати и разрывов страниц. |
|
|  | [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Инициализирует новый экземпляр класса  SpreadsheetOptions  только для отображения областей печати. |
|
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


Определяет, следует ли рендерить лист по разрывам страниц.


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Returns:**
boolean -  true  если лист должен отображаться по разрывам страниц,  false  в противном случае.

### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


Устанавливает, следует ли рендерить лист по разрывам страниц.


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | renderByPageBreaks | boolean | true  если лист должен отображаться по разрывам страниц,  false  в противном случае. |
|

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


Определяет разделитель для файлов CSV/TSV.


Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator).


**Returns:**
boolean -  true  если разделитель должен быть определён автоматически,  false  в противном случае.

### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


Устанавливает, следует ли определять разделитель для файлов CSV/TSV.


Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | detectSeparator | boolean | true  для автоматического определения разделителя,  false  в противном случае. |
|

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Создаёт новый экземпляр
SpreadsheetOptions
класс для рендеринга одного листа на одну страницу.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.

### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Создаёт новый экземпляр
SpreadsheetOptions
класс для рендеринга листа на несколько страниц.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | countRowsPerPage | int | Количество строк, включаемых в каждую страницу. |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.

### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Инициализирует новый экземпляр
SpreadsheetOptions
класс для рендеринга листа на страницы.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | countRowsPerPage | int | Количество строк, включаемых на каждую страницу. |
|
|  | countColumnsPerPage | int | Количество столбцов, включаемых на каждую страницу. |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.

### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Инициализирует новый экземпляр
SpreadsheetOptions
класс для рендеринга только областей печати.
Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.

### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


Указывает, рендерится ли один лист на одну страницу.


**Returns:**
boolean -  true  если один лист отображается на одной странице;  false  в противном случае.

### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


Получает количество строк, включаемых в каждую страницу при разбиении листа на страницы.


Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Returns:**
int - количество строк, включаемых в каждую страницу.

### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


Получает количество столбцов, включаемых в каждую страницу при разбиении листа на страницы.


Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).


**Returns:**
int - количество столбцов, включаемых в каждую страницу.

### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


Устанавливает количество столбцов, включаемых в каждую страницу при разбиении листа на страницы.


Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | countColumnsPerPage | int | Количество столбцов, включаемых в каждую страницу. |
|

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Указывает, рендерятся ли только области печати.


**Returns:**
boolean -  true  если отображаются только области печати,  false  в противном случае.

### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


Когда эта опция включена, лист будет рендериться по разрывам страниц, находящимся внутри области печати.


**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


Устанавливает, рендерить ли лист по разрывам страниц, находящимся внутри области печати.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | renderingPrintAreaAndPageBreaks | boolean | Установите true для включения, false для отключения. |
|

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Включает рендеринг линий сетки.


Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines).


**Returns:**
boolean -  true  если линии сетки включены,  false  в противном случае.

### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Включает или отключает рендеринг линий сетки.


Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  для включения отрисовки линий сетки,  false  для её отключения. |
|

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Указывает, следует ли пропускать пустые строки при рендеринге.


Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Returns:**
boolean -  true  если пустые строки следует пропускать,  false  в противном случае.

### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Устанавливает, следует ли пропускать пустые строки при рендеринге.


Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  для пропуска пустых строк,  false  в противном случае. |
|

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Указывает, следует ли пропускать пустые столбцы при рендеринге.


Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Returns:**
boolean -  true  если пустые столбцы пропускаются,  false  в противном случае.

### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Устанавливает, следует ли пропускать пустые столбцы при рендеринге.


Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  для пропуска пустых столбцов,  false  в противном случае. |
|

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Определяет, должны ли скрытые строки рендериться.


Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Returns:**
boolean -  true  если скрытые строки должны отрисовываться,  false  в противном случае.

### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Устанавливает, должны ли скрытые строки рендериться.


Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  для включения отрисовки скрытых строк,  false  для её отключения. |
|

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Проверяет, включён ли рендеринг заголовков.


Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings).


**Returns:**
boolean -  true  если отрисовка заголовков включена,  false  в противном случае.

### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


Включает рендеринг заголовков.


Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | renderHeadings | boolean | true  для включения отрисовки заголовков,  false  для её отключения. |
|

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Включает рендеринг скрытых столбцов.


Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Returns:**
boolean -  true  если отрисовка скрытых столбцов включена,  false  в противном случае.

### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Включает рендеринг скрытых столбцов.


Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  для включения отрисовки скрытых столбцов,  false  для её отключения. |
|

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


Возвращает режим переполнения текста при рендеринге электронных таблиц в HTML.
Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.

### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


Устанавливает режим переполнения текста при отрисовке электронных таблиц в HTML. Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | Режим переполнения текста, который необходимо установить. |
|

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Установить левый отступ листа при конвертации в PDF; если значение меньше 0, используется значение по умолчанию.


Если параметр меньше 0, используется значение по умолчанию. Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


Установить левый отступ листа при конвертации в PDF; если значение меньше 0, используется значение по умолчанию.


Если параметр меньше 0, используется значение по умолчанию. Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Для установки правого поля листа при конвертации в PDF: если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


Для установки правого поля листа при конвертации в PDF: если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Для установки верхнего поля листа при конвертации в PDF: если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


Для установки верхнего поля листа при конвертации в PDF: если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. Для получения подробной информации см. [документацию](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Чтобы установить нижний отступ листа при конвертации в pdf, если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. Для подробностей см. [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


Чтобы установить нижний отступ листа при конвертации в pdf, если значение меньше 0, используется значение по умолчанию. Если параметр меньше 0, используется значение по умолчанию. Для подробностей см. [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bottomMargin | double |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


Получает или задает горизонтальное разрешение генерируемых изображений в точках на дюйм. Этот параметр используется только при рендеринге электронных таблиц в форматы PNG или JPEG.


Значение по умолчанию — 96 DPI. Минимально возможное значение — 72 DPI, максимально возможное значение — 600 DPI.
Если указанное пользователем значение выходит за эти пределы, будет применено минимальное или максимальное возможное значение.


**Returns:**
int — горизонтальное разрешение в DPI.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


Устанавливает горизонтальное разрешение генерируемых изображений в точках на дюйм. Этот параметр используется только при рендеринге электронных таблиц в форматы PNG или JPEG.


Значение по умолчанию — 96 DPI. Минимально возможное значение — 72 DPI, максимально возможное значение — 600 DPI.
Если указанное пользователем значение выходит за эти пределы, будет применено минимальное или максимальное возможное значение.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | horizontalResolution | int | горизонтальное разрешение в DPI. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Получает или задает вертикальное разрешение генерируемых изображений в точках на дюйм. Этот параметр используется только при рендеринге электронных таблиц в форматы PNG или JPEG.


Значение по умолчанию — 96 DPI. Минимально возможное значение — 72 DPI, максимально возможное значение — 600 DPI.
Если указанное пользователем значение выходит за эти пределы, будет применено минимальное или максимальное возможное значение.


**Returns:**
int — вертикальное разрешение в DPI.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


Устанавливает вертикальное разрешение генерируемых изображений в точках на дюйм. Этот параметр используется только при рендеринге электронных таблиц в форматы PNG или JPEG.


Значение по умолчанию — 96 DPI. Минимально возможное значение — 72 DPI, максимально возможное значение — 600 DPI.
Если указанное пользователем значение выходит за эти пределы, будет применено минимальное или максимальное возможное значение.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | verticalResolution | int | вертикальное разрешение в DPI. |
|

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


Инициализирует новый экземпляр  SpreadsheetOptions  для рендеринга областей печати и разрывов страниц. Для подробностей см. [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.

### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Инициализирует новый экземпляр класса  SpreadsheetOptions  только для рендеринга областей печати. Для подробностей см. [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.

