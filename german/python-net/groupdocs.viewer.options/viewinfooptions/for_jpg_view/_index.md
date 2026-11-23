---
title: "for_jpg_view Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine ViewInfoOptions-Instanz, um Informationen über die Ansicht beim Rendern in JPG abzurufen."
type: docs
url: /de/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

Initialisiert eine [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) Instanz, um Informationen zur Ansicht beim Rendern in JPG abzurufen.

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### Beispiel

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

Initialisiert eine ViewInfoOptions-Instanz zum Abrufen von Ansichtsinformationen beim Rendern zu JPG.

```python
def for_jpg_view(cls, extract_text):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| extract_text | `bool` | Aktiviert die Textextraktion. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Siehe auch
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
