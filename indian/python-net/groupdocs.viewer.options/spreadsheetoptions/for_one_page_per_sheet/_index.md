---
title: "for_one_page_per_sheet मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "पूरे शीट को एक पृष्ठ में रेंडर करने के लिए एक SpreadsheetOptions इंस्टेंस को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/
is_root: false
weight: 1010
---


## for_one_page_per_sheet

पूरे शीट को एक पृष्ठ में रेंडर करने के लिए एक [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) इंस्टेंस को इनिशियलाइज़ करता है।

विवरण के लिए, दस्तावेज़ देखें।

```python
def for_one_page_per_sheet(cls):
    ...
```

**Returns:** `SpreadsheetOptions`: A new instance configured to render the whole sheet into one page.

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_one_page_per_sheet():
    # स्प्रेडशीट लोड करें
    with Viewer("products.xlsx") as viewer:
        view_options = PdfViewOptions("render_one_page_per_sheet/one_page_per_sheet.pdf")
        # प्रत्येक वर्कशीट को एक पृष्ठ पर रेंडर करें।
        view_options.spreadsheet_options = SpreadsheetOptions.for_one_page_per_sheet()
        viewer.view(view_options)

if __name__ == "__main__":
    render_one_page_per_sheet()
```

### साथ में देखें
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
