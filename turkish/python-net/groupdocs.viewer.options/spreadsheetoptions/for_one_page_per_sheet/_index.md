---
title: "for_one_page_per_sheet metodu"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Tüm sayfayı tek bir sayfada renderlemek için bir SpreadsheetOptions örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/
is_root: false
weight: 1010
---


## for_one_page_per_sheet

Tam bir sayfada tüm sayfayı render etmek için bir [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) örneği başlatır.

Ayrıntılar için belgelere bakın.

```python
def for_one_page_per_sheet(cls):
    ...
```

**Returns:** `SpreadsheetOptions`: A new instance configured to render the whole sheet into one page.

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_one_page_per_sheet():
    # Spreadsheet'i yükle
    with Viewer("products.xlsx") as viewer:
        view_options = PdfViewOptions("render_one_page_per_sheet/one_page_per_sheet.pdf")
        # Her çalışma sayfasını tek bir sayfaya renderla.
        view_options.spreadsheet_options = SpreadsheetOptions.for_one_page_per_sheet()
        viewer.view(view_options)

if __name__ == "__main__":
    render_one_page_per_sheet()
```

### Ayrıca Bakınız
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
