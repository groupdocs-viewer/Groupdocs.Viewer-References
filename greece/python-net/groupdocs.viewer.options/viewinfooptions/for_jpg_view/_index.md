---
title: "μέθοδος for_jpg_view"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια παρουσία της ViewInfoOptions για να ανακτήσει πληροφορίες σχετικά με την προβολή κατά την απόδοση σε JPG."
type: docs
url: /el/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

Αρχικοποιεί ένα στιγμιότυπο [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) για την ανάκτηση πληροφοριών προβολής κατά την απόδοση σε JPG.

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### Παράδειγμα

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

Αρχικοποιεί ένα στιγμιότυπο ViewInfoOptions για την ανάκτηση πληροφοριών προβολής κατά την απόδοση σε JPG.

```python
def for_jpg_view(cls, extract_text):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| extract_text | `bool` | Ενεργοποιεί την εξαγωγή κειμένου. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Δείτε επίσης
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
