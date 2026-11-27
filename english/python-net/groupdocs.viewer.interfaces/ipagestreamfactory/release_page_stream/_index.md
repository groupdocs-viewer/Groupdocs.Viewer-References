---
title: release_page_stream method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Releases the stream created by IPageStreamFactory.create_page_stream method."
type: docs
url: /python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 1020
---


## release_page_stream {#page_number-page_stream}

Releases the stream created by [`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/) method.

```python
def release_page_stream(self, page_number, page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| page_number | `int` | The number of a page. |
| page_stream | `io.RawIOBase` | Stream created by `IPageStreamFactory.create_page_stream` method. |

### Aliases

These names call `release_page_stream` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `release_page_stream_int32` | `release_page_stream_int32(page_number, page_stream)` |
| `release_page_stream_stream` | `release_page_stream_stream(page_number, page_stream)` |
| `release_page_stream_streams` | `release_page_stream_streams(page_number, page_stream)` |

### See Also
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
