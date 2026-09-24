---
title: for_html_view method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a ViewInfoOptions instance for retrieving view information when rendering to HTML."
type: docs
url: /python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

Initializes a ViewInfoOptions instance for retrieving view information when rendering to HTML.

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### Example

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # Create view info options for HTML format (single page)
    options = ViewInfoOptions.for_html_view(True)

    # Load a document and retrieve view information
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

Initializes a ViewInfoOptions instance for retrieving view information when rendering to HTML.

```python
def for_html_view(cls, render_single_page):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| render_single_page | `bool` | Enables HTML content rendering to a single page. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Retrieve view info for HTML with a single page
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### See Also
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
