---
title: "for_split_sheet_into_pages metodu"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bir sayfayı sayfalara render etmek için bir SpreadsheetOptions örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 1050
---


## for_split_sheet_into_pages {#count_rows_per_page}

Bir sayfayı sayfalara render etmek için bir SpreadsheetOptions örneği başlatır.

Ayrıntılar için, belgeleri şu adreste inceleyin: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| count_rows_per_page | `int` | Her sayfaya dahil edilecek satır sayısı. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering sheet into pages.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `count_rows_per_page` sıfıra eşit veya sıfırdan küçük olduğunda. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    # Spreadsheet'i yükle
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows()
```

## for_split_sheet_into_pages {#count_rows_per_page-count_columns_per_page}

Bir sayfayı sayfalara render etmek için bir SpreadsheetOptions örneği başlatır.

Ayrıntılar için, belgeleri şu adreste inceleyin: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page, count_columns_per_page):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| count_rows_per_page | `int` | Her sayfaya dahil edilecek satır sayısı. |
| count_columns_per_page | `int` | Her sayfaya dahil edilecek sütun sayısı. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering a sheet into pages.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `count_columns_per_page` sıfıra eşit veya sıfırdan küçük olduğunda. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows_and_columns():
    # Spreadsheet'i yükle
    with Viewer("four-pages.xlsx") as viewer:
        rows_per_page = 15
        columns_per_page = 7
        # Elektronik tabloyu PDF'ye dönüştür.
        view_options = PdfViewOptions("split_by_rows_and_columns/by_rows_and_columns.pdf")
        # Satır ve sütun sayısına göre böl.
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(
            rows_per_page, columns_per_page
        )
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows_and_columns()
```

### Ayrıca Bakınız
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
