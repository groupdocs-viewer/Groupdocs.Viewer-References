---
title: "for_rendering_print_area Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine Instanz der Klasse SpreadsheetOptions zum Rendern nur der Druckbereiche."
type: docs
url: /de/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/
is_root: false
weight: 1030
---


## for_rendering_print_area

Initialisiert eine Instanz der [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)‑Klasse, um ausschließlich die Druckbereiche zu rendern.

Weitere Details finden Sie in der Dokumentation unter https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#render-a-print-area.

```python
def for_rendering_print_area(cls):
    ...
```

**Returns:** SpreadsheetOptions: New instance of the `SpreadsheetOptions` class for rendering print areas only.

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_print_area():
    with Viewer("invoice.xlsx") as viewer:
        view_options = PdfViewOptions("render_print_area/print_area.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_print_area()
        viewer.view(view_options)
```

### Siehe auch
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
