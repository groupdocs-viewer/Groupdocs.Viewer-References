---
title: "for_split_sheet_into_pages metode"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance SpreadsheetOptions untuk merender lembar menjadi halaman."
type: docs
url: /id/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 1050
---


## for_split_sheet_into_pages {#count_rows_per_page}

Menginisialisasi sebuah instance SpreadsheetOptions untuk merender lembar menjadi halaman.

Untuk detail, lihat dokumentasi di https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| count_rows_per_page | `int` | Jumlah baris yang akan dimasukkan ke setiap halaman. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering sheet into pages.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `count_rows_per_page` sama dengan atau kurang dari nol. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    # Muat spreadsheet
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows()
```

## for_split_sheet_into_pages {#count_rows_per_page-count_columns_per_page}

Menginisialisasi sebuah instance SpreadsheetOptions untuk merender lembar menjadi halaman.

Untuk detail, lihat dokumentasi di https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page, count_columns_per_page):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| count_rows_per_page | `int` | Jumlah baris yang akan dimasukkan ke setiap halaman. |
| count_columns_per_page | `int` | Jumlah kolom yang akan dimasukkan ke setiap halaman. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering a sheet into pages.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `count_columns_per_page` sama dengan atau kurang dari nol. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows_and_columns():
    # Muat spreadsheet
    with Viewer("four-pages.xlsx") as viewer:
        rows_per_page = 15
        columns_per_page = 7
        # Konversi spreadsheet ke PDF.
        view_options = PdfViewOptions("split_by_rows_and_columns/by_rows_and_columns.pdf")
        # Pisahkan berdasarkan jumlah baris dan kolom.
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(
            rows_per_page, columns_per_page
        )
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows_and_columns()
```

### Lihat Juga
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
