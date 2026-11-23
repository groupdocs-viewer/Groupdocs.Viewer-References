---
title: "metodo for_jpg_view"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza di ViewInfoOptions per recuperare informazioni sulla visualizzazione durante il rendering in JPG."
type: docs
url: /it/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

Inizializza un'istanza di [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) per recuperare le informazioni della vista durante il rendering in JPG.

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### Esempio

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

Inizializza un'istanza di ViewInfoOptions per recuperare le informazioni della vista durante il rendering in JPG.

```python
def for_jpg_view(cls, extract_text):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| extract_text | `bool` | Abilita l'estrazione del testo. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Vedi anche
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
