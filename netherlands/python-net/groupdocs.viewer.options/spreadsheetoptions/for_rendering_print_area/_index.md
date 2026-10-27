---
title: "for_rendering_print_area methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een instantie van de SpreadsheetOptions‑klasse voor het alleen renderen van de afdrukgebieden."
type: docs
url: /nl/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/
is_root: false
weight: 1030
---


## for_rendering_print_area

Initialiseert een instantie van de [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) klasse voor het alleen renderen van de afdrukgebieden.

Voor details, zie de documentatie op https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#render-a-print-area.

```python
def for_rendering_print_area(cls):
    ...
```

**Returns:** SpreadsheetOptions: New instance of the `SpreadsheetOptions` class for rendering print areas only.

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_print_area():
    with Viewer("invoice.xlsx") as viewer:
        view_options = PdfViewOptions("render_print_area/print_area.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_print_area()
        viewer.view(view_options)
```

### Zie ook
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
