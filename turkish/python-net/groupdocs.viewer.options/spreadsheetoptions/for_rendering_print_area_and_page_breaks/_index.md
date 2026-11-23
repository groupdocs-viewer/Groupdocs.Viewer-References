---
title: "for_rendering_print_area_and_page_breaks yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Yazdırma alanları ve sayfa sonlarını işlemek için SpreadsheetOptions sınıfının bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/
is_root: false
weight: 1040
---


## for_rendering_print_area_and_page_breaks

Yazdırma alanlarını ve sayfa sonlarını render etmek için [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) sınıfının bir örneğini başlatır.

Ayrıntılar için https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area adresindeki belgeleri inceleyin.

```python
def for_rendering_print_area_and_page_breaks(cls):
    ...
```

**Returns:** New instance of the `SpreadsheetOptions` class for rendering pages based on page breaks that are included into the print area. The behavior is similar to printing in Excel.

### Örnek

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

### Ayrıca Bakınız
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
