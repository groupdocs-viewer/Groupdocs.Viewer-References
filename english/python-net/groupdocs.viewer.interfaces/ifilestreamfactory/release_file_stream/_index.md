---
title: release_file_stream method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Releases the stream created by IFileStreamFactory.createfilestream method."
type: docs
url: /python-net/groupdocs.viewer.interfaces/ifilestreamfactory/release_file_stream/
is_root: false
weight: 1020
---


## release_file_stream {#file_stream}

Releases the stream created by [`IFileStreamFactory.create_file_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/create_file_stream/) method.

```python
def release_file_stream(self, file_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_stream | `io.RawIOBase` | Stream created by `IFileStreamFactory.create_file_stream` method. |

**Returns:** None.

### See Also
* class [`IFileStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/)
