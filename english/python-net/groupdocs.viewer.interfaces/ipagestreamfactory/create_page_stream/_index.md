---
title: create_page_stream method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Creates the stream used to write output page data."
type: docs
url: /python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/
is_root: false
weight: 1010
---


## create_page_stream {#page_number}

Creates the stream used to write output page data.

```python
def create_page_stream(self, page_number):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| page_number | `int` | The number of a page. |

**Returns:** io.RawIOBase: Stream used to write output page data.

### Example

```python
    import io
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import PngViewOptions

    page_buffers = {}

    def create_page_stream(page_number):
        buf = io.BytesIO()
        page_buffers[page_number] = buf
        return buf

    with Viewer("input.docx") as viewer:
        viewer.view(PngViewOptions(create_page_stream))
    ```

### See Also
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
