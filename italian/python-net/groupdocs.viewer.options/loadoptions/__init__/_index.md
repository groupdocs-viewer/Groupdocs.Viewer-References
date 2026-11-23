---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza della classe LoadOptions."
type: docs
url: /it/python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza un'istanza della classe [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

Inizializza una nuova istanza di LoadOptions.

Per un esempio di codice, vedere la documentazione.

```python
def __init__(self, file_type):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_type | `FileType` | Il tipo del file da aprire. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `file_type` è None. |

### Esempio

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Vedi anche
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
