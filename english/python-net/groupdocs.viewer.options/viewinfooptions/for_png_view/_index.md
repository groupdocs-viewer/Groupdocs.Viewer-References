---
title: for_png_view method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of the ViewInfoOptions class to retrieve information about view when rendering into PNG."
type: docs
url: /python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

Initializes an instance of the [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) class to retrieve information about view when rendering into PNG.

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Create view info options for PNG format
view_info_options_png = ViewInfoOptions.for_png_view()

# Load a document and get view information for PNG
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

Initializes an instance of the ViewInfoOptions class to retrieve information about view when rendering into PNG.

```python
def for_png_view(cls, extract_text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| extract_text | `bool` | Enables text extraction. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Example

```python
from groupdocs.viewer.options import ViewInfoOptions

# Create view info options for PNG format with text extraction enabled
options = ViewInfoOptions.for_png_view(extractText=True)
```

### See Also
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
