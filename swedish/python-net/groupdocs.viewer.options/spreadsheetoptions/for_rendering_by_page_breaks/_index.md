---
title: "for_rendering_by_page_breaks metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en SpreadsheetOptions-instans konfigurerad för att dela kalkylblad i sidor med sidbrytningar."
type: docs
url: /sv/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/
is_root: false
weight: 1020
---


## for_rendering_by_page_breaks

Initierar en [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)‑instans konfigurerad för att dela upp kalkylblad i sidor vid sidbrytningar.

För detaljer, se dokumentationen.

```python
def for_rendering_by_page_breaks(cls):
    ...
```

**Returns:** New `SpreadsheetOptions` instance for splitting to pages by page breaks. The behavior is similar to printing in Excel.

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_page_breaks():
    # Läs in kalkylblad
    with Viewer("products.xlsx") as viewer:
        # Konvertera kalkylbladet till PDF.
        view_options = PdfViewOptions("split_by_page_breaks/by_page_breaks.pdf")
        # Dela med hjälp av sidbrytningar.
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_by_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_page_breaks()
```

### Se även
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
