---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes options for rendering word processing documents."
type: docs
url: /python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes options for rendering word processing documents.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Enable rendering of tracked changes.
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### See Also
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
