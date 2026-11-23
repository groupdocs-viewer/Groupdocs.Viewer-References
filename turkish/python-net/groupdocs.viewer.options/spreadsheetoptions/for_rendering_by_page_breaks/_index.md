---
title: "for_rendering_by_page_breaks metodu"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Sayfa sonlarına göre çalışma sayfalarını sayfalara bölmek için yapılandırılmış bir SpreadsheetOptions örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/
is_root: false
weight: 1020
---


## for_rendering_by_page_breaks

Sayfa sonlarına göre çalışma sayfalarını sayfalara bölmek için yapılandırılmış bir [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) örneği başlatır.

Ayrıntılar için belgelere bakın.

```python
def for_rendering_by_page_breaks(cls):
    ...
```

**Returns:** New `SpreadsheetOptions` instance for splitting to pages by page breaks. The behavior is similar to printing in Excel.

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_page_breaks():
    # Spreadsheet'i yükle
    with Viewer("products.xlsx") as viewer:
        # Elektronik tabloyu PDF'ye dönüştür.
        view_options = PdfViewOptions("split_by_page_breaks/by_page_breaks.pdf")
        # Sayfa sonlarını kullanarak böl.
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_by_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_page_breaks()
```

### Ayrıca Bakınız
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
