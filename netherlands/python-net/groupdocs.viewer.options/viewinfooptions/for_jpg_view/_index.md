---
title: "for_jpg_view methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een ViewInfoOptions‑instantie om informatie over de weergave op te halen bij het renderen naar JPG."
type: docs
url: /nl/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

Initialiseert een [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) instantie om informatie over de weergave op te halen bij het renderen naar JPG.

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### Voorbeeld

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

Initialiseert een ViewInfoOptions‑instantie om weergave‑informatie op te halen bij het renderen naar JPG.

```python
def for_jpg_view(cls, extract_text):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| extract_text | `bool` | Schakelt tekstextractie in. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Zie ook
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
