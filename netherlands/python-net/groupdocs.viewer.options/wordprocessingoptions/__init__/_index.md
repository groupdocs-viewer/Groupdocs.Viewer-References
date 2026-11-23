---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert opties voor het renderen van tekstverwerkingsdocumenten."
type: docs
url: /nl/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert opties voor het renderen van tekstverwerkingsdocumenten.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Schakel het renderen van bijgehouden wijzigingen in.
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Zie ook
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
