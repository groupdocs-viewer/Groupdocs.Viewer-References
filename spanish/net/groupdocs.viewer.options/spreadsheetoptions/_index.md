---
title: "SpreadsheetOptions"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Contiene opciones para renderizar hojas de cálculo. Para más detalles, consulte los elementos hijos de los archivos Render spreadsheet en https//docs.groupdocs.com/viewer/net/renderspreadsheets/ tema."
type: docs
weight: 530
url: /es/net/groupdocs.viewer.options/spreadsheetoptions/
---

## SpreadsheetOptions class

Contiene opciones para renderizar hojas de cálculo. Para más detalles, consulte los subtemas del tema [Render spreadsheet files](https://docs.groupdocs.com/viewer/net/render-spreadsheets/).

```csharp
public class SpreadsheetOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/spreadsheetoptions/bottommargin) { get; set; } | Establece el margen inferior de una página al convertir a PDF. |
| [CountColumnsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countcolumnsperpage) { get; } | El número de columnas a incluir en cada página al dividir la hoja de cálculo en páginas. |
| [CountRowsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countrowsperpage) { get; } | El número de filas a incluir en cada página al dividir la hoja de cálculo en páginas. |
| [DetectSeparator](../../groupdocs.viewer.options/spreadsheetoptions/detectseparator) { get; set; } | Detecta un separador (para archivos CSV/TSV). |
| [HorizontalResolution](../../groupdocs.viewer.options/spreadsheetoptions/horizontalresolution) { get; set; } | Obtiene o establece la resolución horizontal para las imágenes generadas en puntos por pulgada. Esta opción se utiliza solo al renderizar hojas de cálculo a formatos PNG o JPEG. |
| [LeftMargin](../../groupdocs.viewer.options/spreadsheetoptions/leftmargin) { get; set; } | Establece el margen izquierdo de una página al convertir a PDF. |
| [RenderGridLines](../../groupdocs.viewer.options/spreadsheetoptions/rendergridlines) { get; set; } | Permite renderizar líneas de cuadrícula. |
| [RenderHeadings](../../groupdocs.viewer.options/spreadsheetoptions/renderheadings) { get; set; } | Permite renderizar encabezados. |
| [RenderHiddenColumns](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddencolumns) { get; set; } | Permite renderizar columnas ocultas. |
| [RenderHiddenRows](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddenrows) { get; set; } | Permite renderizar filas ocultas. |
| [RightMargin](../../groupdocs.viewer.options/spreadsheetoptions/rightmargin) { get; set; } | Establece el margen derecho de una página al convertir a PDF. |
| [SkipEmptyColumns](../../groupdocs.viewer.options/spreadsheetoptions/skipemptycolumns) { get; set; } | Desactiva la representación de columnas vacías. |
| [SkipEmptyRows](../../groupdocs.viewer.options/spreadsheetoptions/skipemptyrows) { get; set; } | Desactiva la representación de filas vacías. |
| [TextOverflowMode](../../groupdocs.viewer.options/spreadsheetoptions/textoverflowmode) { get; set; } | Establece el modo de desbordamiento de texto para renderizar documentos de hoja de cálculo en HTML. Por defecto es , lo que imita el comportamiento predeterminado de MS Excel. |
| [TopMargin](../../groupdocs.viewer.options/spreadsheetoptions/topmargin) { get; set; } | Establece el margen superior de una página al convertir a PDF. |
| [VerticalResolution](../../groupdocs.viewer.options/spreadsheetoptions/verticalresolution) { get; set; } | Obtiene o establece la resolución vertical para las imágenes generadas en puntos por pulgada. Esta opción se usa solo al renderizar hojas de cálculo a formatos PNG o JPEG. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ForOnePagePerSheet](../../groupdocs.viewer.options/spreadsheetoptions/foronepagepersheet)() | Inicializa una instancia de la clase [`SpreadsheetOptions`](../spreadsheetoptions) para renderizar toda la hoja en una sola página. |
| static [ForRenderingByPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingbypagebreaks)() | Inicializa una instancia de la clase [`SpreadsheetOptions`](../spreadsheetoptions) para dividir en páginas por saltos de página. |
| static [ForRenderingPrintArea](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintarea)() | Inicializa una instancia de la clase [`SpreadsheetOptions`](../spreadsheetoptions) para renderizar solo las áreas de impresión. |
| static [ForRenderingPrintAreaAndPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintareaandpagebreaks)() | Inicializa una instancia de la clase [`SpreadsheetOptions`](../spreadsheetoptions) para renderizar áreas de impresión y saltos de página. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages)(int) | Inicializa una instancia de la clase [`SpreadsheetOptions`](../spreadsheetoptions) para renderizar la hoja en páginas. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages_1)(int, int) | Inicializa una instancia de la clase [`SpreadsheetOptions`](../spreadsheetoptions) para renderizar la hoja en páginas. |

### Ver también

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
