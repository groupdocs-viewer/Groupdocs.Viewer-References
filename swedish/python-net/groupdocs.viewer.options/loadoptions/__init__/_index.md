---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en instans av klassen LoadOptions."
type: docs
url: /sv/python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en instans av klassen [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

Initierar en ny LoadOptions-instans.

För kodexempel, se dokumentationen.

```python
def __init__(self, file_type):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_type | `FileType` | Typen av filen som ska öppnas. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `file_type` är None. |

### Exempel

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Se även
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
