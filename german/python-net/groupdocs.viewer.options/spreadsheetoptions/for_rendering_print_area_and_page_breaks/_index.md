---
title: "for_rendering_print_area_and_page_breaks Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine Instanz der Klasse SpreadsheetOptions zum Rendern von Druckbereichen und Seitenumbrüchen."
type: docs
url: /de/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/
is_root: false
weight: 1040
---


## for_rendering_print_area_and_page_breaks

Initialisiert eine Instanz der [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)‑Klasse, um Druckbereiche und Seitenumbrüche zu rendern.

Für Details siehe die Dokumentation unter https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area.

```python
def for_rendering_print_area_and_page_breaks(cls):
    ...
```

**Returns:** New instance of the `SpreadsheetOptions` class for rendering pages based on page breaks that are included into the print area. The behavior is similar to printing in Excel.

### Beispiel

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

### Siehe auch
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
