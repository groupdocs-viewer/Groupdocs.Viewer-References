---
title: "méthode for_rendering_by_page_breaks"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de SpreadsheetOptions configurée pour diviser les feuilles de calcul en pages par sauts de page."
type: docs
url: /fr/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/
is_root: false
weight: 1020
---


## for_rendering_by_page_breaks

Initialise une instance [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) configurée pour diviser les feuilles de calcul en pages selon les sauts de page.

Pour plus de détails, consultez la documentation.

```python
def for_rendering_by_page_breaks(cls):
    ...
```

**Returns:** New `SpreadsheetOptions` instance for splitting to pages by page breaks. The behavior is similar to printing in Excel.

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_page_breaks():
    # Charger la feuille de calcul
    with Viewer("products.xlsx") as viewer:
        # Convertir la feuille de calcul en PDF.
        view_options = PdfViewOptions("split_by_page_breaks/by_page_breaks.pdf")
        # Diviser en utilisant les sauts de page.
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_by_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_page_breaks()
```

### Voir aussi
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
