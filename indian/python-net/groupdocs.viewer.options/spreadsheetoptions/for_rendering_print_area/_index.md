---
title: "for_rendering_print_area मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "केवल प्रिंट क्षेत्रों को रेंडर करने के लिए SpreadsheetOptions क्लास की एक इंस्टेंस को इनिशियलाइज़ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/
is_root: false
weight: 1030
---


## for_rendering_print_area

केवल प्रिंट क्षेत्रों को रेंडर करने के लिए [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है।

विवरण के लिए, https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#render-a-print-area पर दस्तावेज़ देखें।

```python
def for_rendering_print_area(cls):
    ...
```

**Returns:** SpreadsheetOptions: New instance of the `SpreadsheetOptions` class for rendering print areas only.

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_print_area():
    with Viewer("invoice.xlsx") as viewer:
        view_options = PdfViewOptions("render_print_area/print_area.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_print_area()
        viewer.view(view_options)
```

### साथ में देखें
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
