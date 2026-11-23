---
title: "método for_jpg_view"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de ViewInfoOptions para obtener información sobre la vista al renderizar en JPG."
type: docs
url: /es/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

Inicializa una instancia de [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) para obtener información de vista al renderizar en JPG.

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

def get_jpg_view_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_jpg_view())
        print("Document type:", info.file_type)
        print("Pages count:", len(info.pages))

if __name__ == "__main__":
    get_jpg_view_info()
```

## for_jpg_view {#extract_text}

Inicializa una instancia de ViewInfoOptions para obtener información de vista al renderizar a JPG.

```python
def for_jpg_view(cls, extract_text):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| extract_text | `bool` | Habilita la extracción de texto. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Ver también
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
