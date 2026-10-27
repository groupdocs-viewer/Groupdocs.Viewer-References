---
title: "for_split_sheet_into_pages मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक शीट को पृष्ठों में रेंडर करने के लिए SpreadsheetOptions इंस्टेंस को इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 1050
---


## for_split_sheet_into_pages {#count_rows_per_page}

एक शीट को पृष्ठों में रेंडर करने के लिए SpreadsheetOptions इंस्टेंस को इनिशियलाइज़ करता है।

विवरण के लिए, https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows पर दस्तावेज़ देखें।

```python
def for_split_sheet_into_pages(cls, count_rows_per_page):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| count_rows_per_page | `int` | प्रत्येक पृष्ठ में शामिल करने के लिए पंक्तियों की संख्या। |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering sheet into pages.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `count_rows_per_page` शून्य के बराबर या उससे कम हो। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    # स्प्रेडशीट लोड करें
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows()
```

## for_split_sheet_into_pages {#count_rows_per_page-count_columns_per_page}

एक शीट को पृष्ठों में रेंडर करने के लिए SpreadsheetOptions इंस्टेंस को इनिशियलाइज़ करता है।

विवरण के लिए, https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns पर दस्तावेज़ देखें।

```python
def for_split_sheet_into_pages(cls, count_rows_per_page, count_columns_per_page):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| count_rows_per_page | `int` | प्रत्येक पृष्ठ में शामिल करने के लिए पंक्तियों की संख्या। |
| count_columns_per_page | `int` | प्रत्येक पृष्ठ में शामिल करने के लिए स्तंभों की संख्या। |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering a sheet into pages.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `count_columns_per_page` शून्य के बराबर या उससे कम हो। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows_and_columns():
    # स्प्रेडशीट लोड करें
    with Viewer("four-pages.xlsx") as viewer:
        rows_per_page = 15
        columns_per_page = 7
        # स्प्रेडशीट को PDF में परिवर्तित करें।
        view_options = PdfViewOptions("split_by_rows_and_columns/by_rows_and_columns.pdf")
        # पंक्तियों और स्तंभों की संख्या के अनुसार विभाजित करें।
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(
            rows_per_page, columns_per_page
        )
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows_and_columns()
```

### साथ में देखें
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
