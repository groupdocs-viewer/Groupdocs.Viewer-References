---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de la classe LoadOptions."
type: docs
url: /fr/python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une instance de la classe [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

Initialise une nouvelle instance de LoadOptions.

Pour un exemple de code, consultez la documentation.

```python
def __init__(self, file_type):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_type | `FileType` | Le type du fichier à ouvrir. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `file_type` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Voir aussi
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
