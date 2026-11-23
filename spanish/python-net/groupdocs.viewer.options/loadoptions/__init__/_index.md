---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de la clase LoadOptions."
type: docs
url: /es/python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una instancia de la clase [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

Inicializa una nueva instancia de LoadOptions.

Para un ejemplo de código, consulte la documentación.

```python
def __init__(self, file_type):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_type | `FileType` | El tipo del archivo a abrir. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `file_type` es None. |

### Ejemplo

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Ver también
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
