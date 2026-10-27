---
title: "méthode for_jpg_view"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de ViewInfoOptions pour récupérer les informations de vue lors du rendu en JPG."
type: docs
url: /fr/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

Initialise une instance de [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) pour récupérer les informations de vue lors du rendu en JPG.

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### Exemple

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

Initialise une instance de ViewInfoOptions pour récupérer les informations de vue lors du rendu en JPG.

```python
def for_jpg_view(cls, extract_text):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| extract_text | `bool` | Active l'extraction de texte. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Voir aussi
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
