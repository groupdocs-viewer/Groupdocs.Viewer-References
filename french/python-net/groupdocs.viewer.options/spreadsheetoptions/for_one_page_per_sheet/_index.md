---
title: "méthode for_one_page_per_sheet"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de SpreadsheetOptions pour rendre la feuille entière sur une page."
type: docs
url: /fr/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/
is_root: false
weight: 1010
---


## for_one_page_per_sheet

Initialise une instance [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) pour rendre la feuille entière sur une seule page.

Pour plus de détails, consultez la documentation.

```python
def for_one_page_per_sheet(cls):
    ...
```

**Returns:** `SpreadsheetOptions`: A new instance configured to render the whole sheet into one page.

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_one_page_per_sheet():
    # Charger la feuille de calcul
    with Viewer("products.xlsx") as viewer:
        view_options = PdfViewOptions("render_one_page_per_sheet/one_page_per_sheet.pdf")
        # Rendre chaque feuille de calcul sur une page.
        view_options.spreadsheet_options = SpreadsheetOptions.for_one_page_per_sheet()
        viewer.view(view_options)

if __name__ == "__main__":
    render_one_page_per_sheet()
```

### Voir aussi
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
