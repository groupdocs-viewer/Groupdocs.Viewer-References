---
title: "for_rendering_by_page_breaks मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "वर्कशीट को पेज ब्रेक के आधार पर पृष्ठों में विभाजित करने के लिए कॉन्फ़िगर किए गए एक SpreadsheetOptions इंस्टेंस को प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/
is_root: false
weight: 1020
---


## for_rendering_by_page_breaks

पेज ब्रेक के आधार पर वर्कशीट को पृष्ठों में विभाजित करने के लिए कॉन्फ़िगर किए गए एक [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) इंस्टेंस को इनिशियलाइज़ करता है।

विवरण के लिए, दस्तावेज़ देखें।

```python
def for_rendering_by_page_breaks(cls):
    ...
```

**Returns:** New `SpreadsheetOptions` instance for splitting to pages by page breaks. The behavior is similar to printing in Excel.

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_page_breaks():
    # स्प्रेडशीट लोड करें
    with Viewer("products.xlsx") as viewer:
        # स्प्रेडशीट को PDF में परिवर्तित करें।
        view_options = PdfViewOptions("split_by_page_breaks/by_page_breaks.pdf")
        # पेज ब्रेक का उपयोग करके विभाजित करें।
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_by_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_page_breaks()
```

### साथ में देखें
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
