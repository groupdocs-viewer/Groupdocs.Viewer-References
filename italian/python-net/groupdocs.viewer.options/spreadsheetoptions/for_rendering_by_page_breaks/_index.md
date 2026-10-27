---
title: "metodo for_rendering_by_page_breaks"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza di SpreadsheetOptions configurata per dividere i fogli di lavoro in pagine mediante interruzioni di pagina."
type: docs
url: /it/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/
is_root: false
weight: 1020
---


## for_rendering_by_page_breaks

Inizializza un'istanza di [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) configurata per suddividere i fogli di lavoro in pagine tramite interruzioni di pagina.

Per i dettagli, vedere la documentazione.

```python
def for_rendering_by_page_breaks(cls):
    ...
```

**Returns:** New `SpreadsheetOptions` instance for splitting to pages by page breaks. The behavior is similar to printing in Excel.

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_page_breaks():
    # Carica il foglio di calcolo
    with Viewer("products.xlsx") as viewer:
        # Converti il foglio di calcolo in PDF.
        view_options = PdfViewOptions("split_by_page_breaks/by_page_breaks.pdf")
        # Dividi usando le interruzioni di pagina.
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_by_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_page_breaks()
```

### Vedi anche
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
