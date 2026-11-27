---
title: release_resource_stream method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Releases the stream created by IResourceStreamFactory.create_resource_stream method."
type: docs
url: /python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1030
---


## release_resource_stream {#page_number-resource-resource_stream}

Releases the stream created by [`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/) method.

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| page_number | `int` | The number of a page. |
| resource | `Resource` | The HTML resource such as font, style, image or graphics. |
| resource_stream | `io.RawIOBase` | Stream created by `IResourceStreamFactory.create_resource_stream` method. |

**Returns:** None.

### Aliases

These names call `release_resource_stream` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `release_resource_stream_int32` | `release_resource_stream_int32(page_number, resource, resource_stream)` |
| `release_resource_stream_stream` | `release_resource_stream_stream(page_number, resource, resource_stream)` |
| `release_resource_stream_streams` | `release_resource_stream_streams(page_number, resource, resource_stream)` |

### See Also
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
