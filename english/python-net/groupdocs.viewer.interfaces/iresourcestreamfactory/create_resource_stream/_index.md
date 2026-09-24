---
title: create_resource_stream method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Creates the stream used to write output HTML resource data."
type: docs
url: /python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/
is_root: false
weight: 1010
---


## create_resource_stream {#page_number-resource}

Creates the stream used to write output HTML resource data.

```python
def create_resource_stream(self, page_number, resource):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| page_number | `int` | The number of a page. |
| resource | `Resource` | The HTML resource such as font, style, image or graphics. |

**Returns:** io.RawIOBase: Stream used to write output resource data.

### Example

```python
from groupdocs.viewer import Viewer

viewer = Viewer()
factory = viewer.resource_stream_factory

# Create a stream for a CSS resource on page 1
stream = factory.create_resource_stream(pageNumber=1, resource="style.css")
with stream:
    stream.write(b"body { font-family: Arial; }")
```

### See Also
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
