---
title: "méthode for_rendering_print_area"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de la classe SpreadsheetOptions pour le rendu des zones d'impression uniquement."
type: docs
url: /fr/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/
is_root: false
weight: 1030
---


## for_rendering_print_area

Initialise une instance de la classe [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) pour rendre uniquement les zones d’impression.

Pour plus de détails, consultez la documentation à l'adresse https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#render-a-print-area.

```python
def for_rendering_print_area(cls):
    ...
```

**Returns:** SpreadsheetOptions: New instance of the `SpreadsheetOptions` class for rendering print areas only.

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_print_area():
    with Viewer("invoice.xlsx") as viewer:
        view_options = PdfViewOptions("render_print_area/print_area.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_print_area()
        viewer.view(view_options)
```

### Voir aussi
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
