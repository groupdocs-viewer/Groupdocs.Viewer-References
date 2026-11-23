---
title: "for_one_page_per_sheet Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine SpreadsheetOptions-Instanz zum Rendern des gesamten Blatts auf einer Seite."
type: docs
url: /de/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/
is_root: false
weight: 1010
---


## for_one_page_per_sheet

Initialisiert eine [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)‑Instanz zum Rendern des gesamten Blatts auf einer Seite.

Weitere Details finden Sie in der Dokumentation.

```python
def for_one_page_per_sheet(cls):
    ...
```

**Returns:** `SpreadsheetOptions`: A new instance configured to render the whole sheet into one page.

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_one_page_per_sheet():
    # Tabellenblatt laden
    with Viewer("products.xlsx") as viewer:
        view_options = PdfViewOptions("render_one_page_per_sheet/one_page_per_sheet.pdf")
        # Rendern Sie jedes Arbeitsblatt auf einer Seite.
        view_options.spreadsheet_options = SpreadsheetOptions.for_one_page_per_sheet()
        viewer.view(view_options)

if __name__ == "__main__":
    render_one_page_per_sheet()
```

### Siehe auch
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
