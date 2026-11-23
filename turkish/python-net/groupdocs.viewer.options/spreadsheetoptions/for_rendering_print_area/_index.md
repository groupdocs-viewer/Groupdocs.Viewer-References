---
title: "for_rendering_print_area yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Yalnızca yazdırma alanlarını işlemek için SpreadsheetOptions sınıfının bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/
is_root: false
weight: 1030
---


## for_rendering_print_area

Yalnızca yazdırma alanlarını render etmek için [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) sınıfının bir örneğini başlatır.

Ayrıntılar için https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#render-a-print-area adresindeki belgelere bakın.

```python
def for_rendering_print_area(cls):
    ...
```

**Returns:** SpreadsheetOptions: New instance of the `SpreadsheetOptions` class for rendering print areas only.

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_print_area():
    with Viewer("invoice.xlsx") as viewer:
        view_options = PdfViewOptions("render_print_area/print_area.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_print_area()
        viewer.view(view_options)
```

### Ayrıca Bakınız
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
