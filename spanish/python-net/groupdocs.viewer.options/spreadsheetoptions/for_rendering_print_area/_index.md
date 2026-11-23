---
title: "método for_rendering_print_area"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de la clase SpreadsheetOptions para renderizar solo las áreas de impresión."
type: docs
url: /es/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/
is_root: false
weight: 1030
---


## for_rendering_print_area

Inicializa una instancia de la clase [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) para renderizar solo las áreas de impresión.

Para obtener detalles, consulte la documentación en https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#render-a-print-area.

```python
def for_rendering_print_area(cls):
    ...
```

**Returns:** SpreadsheetOptions: New instance of the `SpreadsheetOptions` class for rendering print areas only.

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_print_area():
    with Viewer("invoice.xlsx") as viewer:
        view_options = PdfViewOptions("render_print_area/print_area.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_print_area()
        viewer.view(view_options)
```

### Ver también
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
