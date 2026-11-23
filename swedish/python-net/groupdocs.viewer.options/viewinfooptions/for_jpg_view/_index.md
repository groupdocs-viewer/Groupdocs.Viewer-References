---
title: "for_jpg_view metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ViewInfoOptions‑instans för att hämta information om vyn när den renderas till JPG."
type: docs
url: /sv/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

Initierar en [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) instans för att hämta information om vyn när man renderar till JPG.

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### Exempel

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

Initierar en ViewInfoOptions-instans för att hämta visningsinformation när man renderar till JPG.

```python
def for_jpg_view(cls, extract_text):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| extract_text | `bool` | Aktiverar textutvinning. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Se även
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
