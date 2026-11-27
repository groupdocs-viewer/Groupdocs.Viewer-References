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
import io
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

pages, resources = {}, {}

class PageStreams:
    def create_page_stream(self, page_number):
        pages[page_number] = io.BytesIO()
        return pages[page_number]

class ResourceStreams:
    def create_resource_stream(self, page_number, resource_name):
        # resource_name is the resource's file name, e.g. "s1.css"
        resources[(page_number, resource_name)] = io.BytesIO()
        return resources[(page_number, resource_name)]

    def create_resource_url(self, page_number, resource_name):
        return "res_{0}_{1}".format(page_number, resource_name)

with Viewer("sample.docx") as viewer:
    viewer.view(HtmlViewOptions.for_external_resources(PageStreams(), ResourceStreams()))
```

### Aliases

These names call `create_resource_stream` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `create_resource_stream_int32` | `create_resource_stream_int32(page_number, resource)` |

### See Also
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
