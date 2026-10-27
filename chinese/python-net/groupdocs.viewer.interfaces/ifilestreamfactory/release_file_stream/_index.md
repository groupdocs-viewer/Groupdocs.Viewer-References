---
title: "release_file_stream 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "释放由 IFileStreamFactory.createfilestream 方法创建的流。"
type: docs
url: /zh/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/release_file_stream/
is_root: false
weight: 1020
---


## release_file_stream {#file_stream}

释放由 [`IFileStreamFactory.create_file_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/create_file_stream/) 方法创建的流。

```python
def release_file_stream(self, file_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_stream | `io.RawIOBase` | 由 `IFileStreamFactory.create_file_stream` 方法创建的流。 |

**Returns:** None.

### 另见
* class [`IFileStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/)
