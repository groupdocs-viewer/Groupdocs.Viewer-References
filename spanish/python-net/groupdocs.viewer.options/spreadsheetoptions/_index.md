---
title: "Clase SpreadsheetOptions"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Las opciones para renderizar hojas de cálculo."
type: docs
url: /es/python-net/groupdocs.viewer.options/spreadsheetoptions/
is_root: false
weight: 280
---


## SpreadsheetOptions class

Las opciones para renderizar hojas de cálculo.

Para obtener más detalles, consulte los subtemas del tema Render spreadsheet files.

El tipo SpreadsheetOptions expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [for_one_page_per_sheet](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/) | Inicializa una instancia de [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) para renderizar toda la hoja en una sola página. |
| [for_rendering_by_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/) | Inicializa una instancia de [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) configurada para dividir las hojas de cálculo en páginas mediante saltos de página. |
| [for_rendering_print_area](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/) | Inicializa una instancia de la clase [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) para renderizar solo las áreas de impresión. |
| [for_rendering_print_area_and_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/) | Inicializa una instancia de la clase [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) para renderizar áreas de impresión y saltos de página. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page) | Inicializa una instancia de SpreadsheetOptions para renderizar una hoja en páginas. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page-count_columns_per_page) | Inicializa una instancia de SpreadsheetOptions para renderizar una hoja en páginas. |
| [for_split_sheet_into_pages_int32](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages_int32/) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/bottom_margin/) | El margen inferior de una página al convertir a PDF. |
| [count_columns_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_columns_per_page/) | El número de columnas a incluir en cada página al dividir la hoja de cálculo en páginas. |
| [count_rows_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_rows_per_page/) | El número de filas a incluir en cada página al dividir la hoja de cálculo en páginas. |
| [detect_separator](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/detect_separator/) | La propiedad habilita la detección de un separador para archivos CSV/TSV. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/) | La resolución horizontal para imágenes generadas en puntos por pulgada. Esta opción se usa solo al renderizar hojas de cálculo a formatos PNG o JPEG. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/left_margin/) | El margen izquierdo de una página al convertir a PDF. |
| [render_grid_lines](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_grid_lines/) | La propiedad habilita el renderizado de líneas de cuadrícula. |
| [render_headings](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_headings/) | La propiedad habilita el renderizado de encabezados. |
| [render_hidden_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_columns/) | La propiedad habilita el renderizado de columnas ocultas. |
| [render_hidden_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_rows/) | La propiedad permite la representación de filas ocultas. |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/right_margin/) | El margen derecho de una página al convertir a PDF. |
| [skip_empty_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_columns/) | La propiedad desactiva la representación de columnas vacías. |
| [skip_empty_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_rows/) | La propiedad desactiva la representación de filas vacías. |
| [text_overflow_mode](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/text_overflow_mode/) | El modo de desbordamiento de texto para representar documentos de hoja de cálculo en HTML. El valor predeterminado es `TextOverflowMode.OverlayIfNextIsEmpty`, que imita el comportamiento predeterminado de MS Excel. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/top_margin/) | El margen superior de una página al convertir a PDF. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/) | La resolución vertical para imágenes generadas en puntos por pulgada. Esta opción se utiliza solo al representar hojas de cálculo en formatos PNG o JPEG. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Habilitar la representación de líneas de cuadrícula en la hoja de cálculo.
    view_options.spreadsheet_options.render_grid_lines = True
    viewer.view(view_options)
```

### Ver también
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
