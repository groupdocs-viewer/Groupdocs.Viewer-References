---
title: "método for_rendering_by_page_breaks"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de SpreadsheetOptions configurada para dividir hojas de trabajo en páginas mediante saltos de página."
type: docs
url: /es/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/
is_root: false
weight: 1020
---


## for_rendering_by_page_breaks

Inicializa una instancia de [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) configurada para dividir las hojas de cálculo en páginas mediante saltos de página.

Para obtener más detalles, consulte la documentación.

```python
def for_rendering_by_page_breaks(cls):
    ...
```

**Returns:** New `SpreadsheetOptions` instance for splitting to pages by page breaks. The behavior is similar to printing in Excel.

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_page_breaks():
    # Cargar hoja de cálculo
    with Viewer("products.xlsx") as viewer:
        # Convertir la hoja de cálculo a PDF.
        view_options = PdfViewOptions("split_by_page_breaks/by_page_breaks.pdf")
        # Dividir usando saltos de página.
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_by_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_page_breaks()
```

### Ver también
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
