---
title: "método for_rendering_print_area_and_page_breaks"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de la clase SpreadsheetOptions para renderizar áreas de impresión y saltos de página."
type: docs
url: /es/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/
is_root: false
weight: 1040
---


## for_rendering_print_area_and_page_breaks

Inicializa una instancia de la clase [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) para renderizar áreas de impresión y saltos de página.

Para obtener más detalles, consulte la documentación en https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area.

```python
def for_rendering_print_area_and_page_breaks(cls):
    ...
```

**Returns:** New instance of the `SpreadsheetOptions` class for rendering pages based on page breaks that are included into the print area. The behavior is similar to printing in Excel.

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_print_area_and_page_breaks():
    with Viewer("products.xlsx") as viewer:
        view_options = PdfViewOptions("print_area_and_page_breaks.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_print_area_and_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    render_print_area_and_page_breaks()
```

### Ver también
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
