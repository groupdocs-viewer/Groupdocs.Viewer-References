---
title: "metodo for_rendering_print_area"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza della classe SpreadsheetOptions per il rendering solo delle aree di stampa."
type: docs
url: /it/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/
is_root: false
weight: 1030
---


## for_rendering_print_area

Inizializza un'istanza della classe [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) per il rendering solo delle aree di stampa.

Per i dettagli, consultare la documentazione all'indirizzo https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#render-a-print-area.

```python
def for_rendering_print_area(cls):
    ...
```

**Returns:** SpreadsheetOptions: New instance of the `SpreadsheetOptions` class for rendering print areas only.

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_print_area():
    with Viewer("invoice.xlsx") as viewer:
        view_options = PdfViewOptions("render_print_area/print_area.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_print_area()
        viewer.view(view_options)
```

### Vedi anche
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
