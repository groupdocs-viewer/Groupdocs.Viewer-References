---
title: for_rendering_by_page_breaks method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of SpreadsheetOptions for splitting to pages by page breaks."
type: docs
url: /python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/
is_root: false
weight: 1020
---


## for_rendering_by_page_breaks

Initializes an instance of [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) for splitting to pages by page breaks.

For details, see the documentation: https://docs.groupdocs.com/viewer/python-net/split-worksheet-into-pages/.

```python
def for_rendering_by_page_breaks(cls):
    ...
```

**Returns:** New instance of `SpreadsheetOptions` configured for splitting to pages by page breaks. The behavior is similar to printing in Excel.

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_page_breaks():
    with Viewer("products.xlsx") as viewer:
        view_options = PdfViewOptions("split_by_page_breaks/by_page_breaks.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_by_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_page_breaks()
```

### See Also
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
