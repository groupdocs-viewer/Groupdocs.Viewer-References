---
title: "méthode for_rendering_print_area_and_page_breaks"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de la classe SpreadsheetOptions pour le rendu des zones d'impression et des sauts de page."
type: docs
url: /fr/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/
is_root: false
weight: 1040
---


## for_rendering_print_area_and_page_breaks

Initialise une instance de la classe [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) pour rendre les zones d’impression et les sauts de page.

Pour plus de détails, consultez la documentation à l'adresse https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area.

```python
def for_rendering_print_area_and_page_breaks(cls):
    ...
```

**Returns:** New instance of the `SpreadsheetOptions` class for rendering pages based on page breaks that are included into the print area. The behavior is similar to printing in Excel.

### Exemple

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

### Voir aussi
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
