---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine Instanz der Klasse LoadOptions."
type: docs
url: /de/python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine Instanz der [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) Klasse.

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

Initialisiert eine neue LoadOptions-Instanz.

Für ein Code‑Beispiel siehe die Dokumentation.

```python
def __init__(self, file_type):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_type | `FileType` | Der Typ der zu öffnenden Datei. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `file_type` None ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Siehe auch
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
