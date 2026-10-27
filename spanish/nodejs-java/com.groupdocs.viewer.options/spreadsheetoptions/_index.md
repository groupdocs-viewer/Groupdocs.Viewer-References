---
title: "SpreadsheetOptions"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Proporciona opciones para renderizar hojas de cálculo."
type: docs
weight: 31
url: /es/nodejs-java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Proporciona opciones para renderizar hojas de cálculo.

La clase SpreadsheetOptions encapsula varios ajustes y parámetros que pueden usarse para controlar la renderización de archivos de hoja de cálculo (como archivos Excel o CSV) en el componente GroupDocs.Viewer. Para obtener más detalles, consulte los elementos hijos del tema [Render spreadsheet files][].

Ejemplo de uso:

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
## Métodos

| Método | Descripción |
| --- | --- |
| [isRenderByPageBreaks()](#isRenderByPageBreaks--) | Determina si la hoja de cálculo debe renderizarse por saltos de página. |
| [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | Establece si la hoja de cálculo debe renderizarse por saltos de página. |
| [isDetectSeparator()](#isDetectSeparator--) | Detecta el separador para archivos CSV/TSV. |
| [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | Establece si se debe detectar el separador para archivos CSV/TSV. |
| [forOnePagePerSheet()](#forOnePagePerSheet--) | Crea una nueva instancia de la clase  SpreadsheetOptions  para renderizar una hoja en una página. |
| [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Crea una nueva instancia de la clase  SpreadsheetOptions  para renderizar una hoja en varias páginas. |
| [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Inicializa una nueva instancia de la clase  SpreadsheetOptions  para renderizar una hoja en páginas. |
| [forRenderingPrintArea()](#forRenderingPrintArea--) | Inicializa una nueva instancia de la clase  SpreadsheetOptions  para renderizar solo áreas de impresión. |
| [isOnePagePerSheet()](#isOnePagePerSheet--) | Indica si una hoja se renderiza en una página. |
| [getCountRowsPerPage()](#getCountRowsPerPage--) | Obtiene la cantidad de filas que se incluirán en cada página al dividir la hoja de cálculo en páginas. |
| [getCountColumnsPerPage()](#getCountColumnsPerPage--) | Obtiene la cantidad de columnas que se incluirán en cada página al dividir la hoja de cálculo en páginas. |
| [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | Establece la cantidad de columnas que se incluirán en cada página al dividir la hoja de cálculo en páginas. |
| [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Indica si solo se renderizan las áreas de impresión. |
| [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | Cuando esta opción está habilitada, una hoja de cálculo se renderizará por saltos de página que estén dentro del área de impresión. |
| [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | Establece si se debe renderizar una hoja de cálculo por saltos de página que estén dentro del área de impresión. |
| [isRenderGridLines()](#isRenderGridLines--) | Habilita el renderizado de líneas de cuadrícula. |
| [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Habilita o deshabilita el renderizado de líneas de cuadrícula. |
| [isSkipEmptyRows()](#isSkipEmptyRows--) | Indica si se deben omitir filas vacías durante el renderizado. |
| [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Establece si se deben omitir filas vacías durante el renderizado. |
| [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Indica si se deben omitir columnas vacías durante el renderizado. |
| [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Establece si se deben omitir columnas vacías durante el renderizado. |
| [isRenderHiddenRows()](#isRenderHiddenRows--) | Determina si se deben renderizar filas ocultas. |
| [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Establece si se deben renderizar filas ocultas. |
| [isRenderHeadings()](#isRenderHeadings--) | Comprueba si el renderizado de encabezados está habilitado. |
| [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | Habilita el renderizado de encabezados. |
| [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Habilita el renderizado de columnas ocultas. |
| [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Habilita el renderizado de columnas ocultas. |
| [getTextOverflowMode()](#getTextOverflowMode--) | Devuelve el modo de desbordamiento de texto para renderizar documentos de hoja de cálculo en HTML. |
| [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | Establece el modo de desbordamiento de texto para renderizar documentos de hoja de cálculo en HTML. |
| [getLeftMargin()](#getLeftMargin--) | Para establecer el margen izquierdo de la hoja de cálculo al convertir a PDF, si es menor que 0 se utiliza el valor de conversión predeterminado. |
| [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | Para establecer el margen izquierdo de la hoja de cálculo al convertir a PDF, si es menor que 0 se utiliza el valor de conversión predeterminado. |
| [getRightMargin()](#getRightMargin--) | Para establecer el margen derecho de la hoja de cálculo al convertir a PDF, si es menor que 0 se utiliza el valor de conversión predeterminado. Si el parámetro es menor que 0, se utiliza el valor predeterminado. |
| [setRightMargin(double rightMargin)](#setRightMargin-double-) | Para establecer el margen derecho de la hoja de cálculo al convertir a PDF, si es menor que 0 se utiliza el valor de conversión predeterminado. Si el parámetro es menor que 0, se utiliza el valor predeterminado. |
| [getTopMargin()](#getTopMargin--) | Para establecer el margen superior de la hoja de cálculo al convertir a PDF, si es menor que 0 se utiliza el valor de conversión predeterminado. Si el parámetro es menor que 0, se utiliza el valor predeterminado. |
| [setTopMargin(double topMargin)](#setTopMargin-double-) | Para establecer el margen superior de la hoja de cálculo al convertir a PDF, si es menor que 0 se utiliza el valor de conversión predeterminado. Si el parámetro es menor que 0, se utiliza el valor predeterminado. |
| [getBottomMargin()](#getBottomMargin--) | Para establecer el margen inferior de la hoja de cálculo al convertir a PDF, si es menor que 0 se utiliza el valor de conversión predeterminado. Si el parámetro es menor que 0, se utiliza el valor predeterminado. |
| [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | Para establecer el margen inferior de la hoja de cálculo al convertir a PDF, si es menor que 0 se utiliza el valor de conversión predeterminado. Si el parámetro es menor que 0, se utiliza el valor predeterminado. |
| [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | Inicializa una nueva instancia de SpreadsheetOptions para renderizar áreas de impresión y saltos de página. |
| [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Inicializa una nueva instancia de la clase  SpreadsheetOptions  para renderizar solo áreas de impresión. |
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


Determina si la hoja de cálculo debe renderizarse por saltos de página.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Returns:**
boolean -  true  si la hoja de cálculo debe renderizarse por saltos de página,  false  de lo contrario.
### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


Establece si la hoja de cálculo debe renderizarse por saltos de página.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderByPageBreaks | boolean | true  si la hoja de cálculo debe renderizarse por saltos de página,  false  de lo contrario. |

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


Detecta el separador para archivos CSV/TSV.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Returns:**
boolean -  true  si el separador debe detectarse automáticamente,  false  de lo contrario.
### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


Establece si se debe detectar el separador para archivos CSV/TSV.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| detectSeparator | boolean | true  para detectar automáticamente el separador,  false  de lo contrario. |

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Crea una nueva instancia de la clase  SpreadsheetOptions  para renderizar una hoja en una página.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.
### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Crea una nueva instancia de la clase  SpreadsheetOptions  para renderizar una hoja en varias páginas.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| countRowsPerPage | int | El número de filas a incluir en cada página. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.
### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Inicializa una nueva instancia de la clase  SpreadsheetOptions  para renderizar una hoja en páginas.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| countRowsPerPage | int | El número de filas a incluir en cada página. |
| countColumnsPerPage | int | El número de columnas a incluir en cada página. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.
### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Inicializa una nueva instancia de la clase  SpreadsheetOptions  para renderizar solo áreas de impresión.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.
### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


Indica si una hoja se renderiza en una página.

**Returns:**
boolean -  true  si una hoja se renderiza en una página;  false  de lo contrario.
### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


Obtiene la cantidad de filas que se incluirán en cada página al dividir la hoja de cálculo en páginas.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Returns:**
int - el recuento de filas a incluir en cada página.
### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


Obtiene la cantidad de columnas que se incluirán en cada página al dividir la hoja de cálculo en páginas.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Returns:**
int - el recuento de columnas a incluir en cada página.
### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


Establece la cantidad de columnas que se incluirán en cada página al dividir la hoja de cálculo en páginas.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| countColumnsPerPage | int | El recuento de columnas a incluir en cada página. |

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Indica si solo se renderizan las áreas de impresión.

**Returns:**
boolean -  true  si solo se renderizan las áreas de impresión,  false  de lo contrario.
### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


Cuando esta opción está habilitada, una hoja de cálculo se renderizará por saltos de página que estén dentro del área de impresión.

**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


Establece si se debe renderizar una hoja de cálculo por saltos de página que estén dentro del área de impresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderingPrintAreaAndPageBreaks | boolean | Establecer en true para habilitar, false para deshabilitar. |

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Habilita el renderizado de líneas de cuadrícula.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Returns:**
boolean -  true  si las líneas de cuadrícula están habilitadas,  false  de lo contrario.
### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Habilita o deshabilita el renderizado de líneas de cuadrícula.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | true  para habilitar el renderizado de líneas de cuadrícula,  false  para desactivarlo. |

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Indica si se deben omitir filas vacías durante el renderizado.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  si se deben omitir filas vacías,  false  de lo contrario.
### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Establece si se deben omitir filas vacías durante el renderizado.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | true  para omitir filas vacías,  false  de lo contrario. |

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Indica si se deben omitir columnas vacías durante el renderizado.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  si se omiten columnas vacías,  false  de lo contrario.
### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Establece si se deben omitir columnas vacías durante el renderizado.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | true  para omitir columnas vacías,  false  de lo contrario. |

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Determina si se deben renderizar filas ocultas.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  si se deben renderizar filas ocultas,  false  de lo contrario.
### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Establece si se deben renderizar filas ocultas.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | true  para habilitar el renderizado de filas ocultas,  false  para desactivarlo. |

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Comprueba si el renderizado de encabezados está habilitado.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Returns:**
boolean -  true  si el renderizado de encabezados está habilitado,  false  de lo contrario.
### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


Habilita el renderizado de encabezados.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderHeadings | boolean | true  para habilitar el renderizado de encabezados,  false  para desactivarlo. |

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Habilita el renderizado de columnas ocultas.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  si el renderizado de columnas ocultas está habilitado,  false  de lo contrario.
### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Habilita el renderizado de columnas ocultas.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | true  para habilitar el renderizado de columnas ocultas,  false  para desactivarlo. |

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


Devuelve el modo de desbordamiento de texto para renderizar documentos de hoja de cálculo en HTML.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.
### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


Establece el modo de desbordamiento de texto para renderizar documentos de hoja de cálculo en HTML. Para más detalles, consulte la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | El modo de desbordamiento de texto a establecer. |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Para establecer el margen izquierdo de la hoja de cálculo al convertir a PDF, si es menor que 0 se utiliza el valor de conversión predeterminado.

Si el parámetro es menor que 0, se utiliza el valor predeterminado. Para más detalles, consulte la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


Para establecer el margen izquierdo de la hoja de cálculo al convertir a PDF, si es menor que 0 se utiliza el valor de conversión predeterminado.

Si el parámetro es menor que 0, se utiliza el valor predeterminado. Para más detalles, consulte la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Para establecer el margen derecho de la hoja de cálculo al convertir a PDF, si es menor que 0 se usa el valor de conversión predeterminado. Si el parámetro es menor que 0, se utiliza el valor predeterminado. Para más detalles, consulte la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


Para establecer el margen derecho de la hoja de cálculo al convertir a PDF, si es menor que 0 se usa el valor de conversión predeterminado. Si el parámetro es menor que 0, se utiliza el valor predeterminado. Para más detalles, consulte la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Para establecer el margen superior de la hoja de cálculo al convertir a PDF, si es menor que 0 se usa el valor de conversión predeterminado. Si el parámetro es menor que 0, se utiliza el valor predeterminado. Para más detalles, consulte la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


Para establecer el margen superior de la hoja de cálculo al convertir a PDF, si es menor que 0 se usa el valor de conversión predeterminado. Si el parámetro es menor que 0, se utiliza el valor predeterminado. Para más detalles, consulte la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Para establecer el margen inferior de la hoja de cálculo al convertir a PDF, si es menor que 0 se usa el valor de conversión predeterminado. Si el parámetro es menor que 0, se utiliza el valor predeterminado. Para más detalles, consulte la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


Para establecer el margen inferior de la hoja de cálculo al convertir a PDF, si es menor que 0 se usa el valor de conversión predeterminado. Si el parámetro es menor que 0, se utiliza el valor predeterminado. Para más detalles, consulte la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bottomMargin | double |  |

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


Inicializa una nueva instancia de  SpreadsheetOptions  para renderizar áreas de impresión y saltos de página. Para más detalles, consulte la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.
### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Inicializa una nueva instancia de la clase  SpreadsheetOptions  solo para renderizar áreas de impresión. Para más detalles, consulte la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.
