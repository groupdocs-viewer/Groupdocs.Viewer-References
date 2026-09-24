---
title: for_jpg_view method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a ViewInfoOptions instance to retrieve information about view when rendering into JPG."
type: docs
url: /python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

Initializes a [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) instance to retrieve information about view when rendering into JPG.

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### Example

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

Initializes a ViewInfoOptions instance for retrieving view information when rendering to JPG.

```python
def for_jpg_view(cls, extract_text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| extract_text | `bool` | Enables text extraction. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### See Also
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
