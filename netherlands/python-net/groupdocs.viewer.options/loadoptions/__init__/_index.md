---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een instantie van de LoadOptions-klasse."
type: docs
url: /nl/python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een instantie van de [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) klasse.

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

Initialiseert een nieuwe LoadOptions‑instantie.

Voor een codevoorbeeld, zie de documentatie.

```python
def __init__(self, file_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_type | `FileType` | Het type van het te openen bestand. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `file_type` None is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Zie ook
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
