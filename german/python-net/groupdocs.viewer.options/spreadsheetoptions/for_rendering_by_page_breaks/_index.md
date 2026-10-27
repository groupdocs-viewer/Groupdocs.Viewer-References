---
title: "for_rendering_by_page_breaks Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine SpreadsheetOptions-Instanz, die so konfiguriert ist, Arbeitsblätter anhand von Seitenumbrüchen in Seiten zu teilen."
type: docs
url: /de/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/
is_root: false
weight: 1020
---


## for_rendering_by_page_breaks

Initialisiert eine [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)‑Instanz, die so konfiguriert ist, Arbeitsblätter anhand von Seitenumbrüchen in Seiten zu splitten.

Weitere Details finden Sie in der Dokumentation.

```python
def for_rendering_by_page_breaks(cls):
    ...
```

**Returns:** New `SpreadsheetOptions` instance for splitting to pages by page breaks. The behavior is similar to printing in Excel.

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_page_breaks():
    # Tabellenblatt laden
    with Viewer("products.xlsx") as viewer:
        # Konvertieren Sie das Tabellenblatt in PDF.
        view_options = PdfViewOptions("split_by_page_breaks/by_page_breaks.pdf")
        # Aufteilen mit Seitenumbrüchen.
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_by_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_page_breaks()
```

### Siehe auch
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
