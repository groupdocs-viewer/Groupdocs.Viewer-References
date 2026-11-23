---
title: "for_rendering_by_page_breaks metode"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi instance SpreadsheetOptions yang dikonfigurasi untuk membagi worksheet menjadi halaman berdasarkan pemisah halaman."
type: docs
url: /id/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/
is_root: false
weight: 1020
---


## for_rendering_by_page_breaks

Menginisialisasi sebuah instance [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) yang dikonfigurasi untuk membagi lembar kerja menjadi halaman berdasarkan pemisah halaman.

Untuk detail, lihat dokumentasi.

```python
def for_rendering_by_page_breaks(cls):
    ...
```

**Returns:** New `SpreadsheetOptions` instance for splitting to pages by page breaks. The behavior is similar to printing in Excel.

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_page_breaks():
    # Muat spreadsheet
    with Viewer("products.xlsx") as viewer:
        # Konversi spreadsheet ke PDF.
        view_options = PdfViewOptions("split_by_page_breaks/by_page_breaks.pdf")
        # Pisahkan menggunakan pemisah halaman.
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_by_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_page_breaks()
```

### Lihat Juga
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
