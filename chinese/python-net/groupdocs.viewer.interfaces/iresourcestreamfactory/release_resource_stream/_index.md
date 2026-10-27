---
title: "release_resource_stream 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "释放由 IResourceStreamFactory.createresourcestream 方法创建的流。"
type: docs
url: /zh/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1050
---


## release_resource_stream {#page_number-resource-resource_stream}

释放由 [`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/) 方法创建的流。

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| page_number | `int` | 页面的编号。 |
| resource | `Resource` | HTML 资源，例如字体、样式、图像或图形。 |
| resource_stream | `io.RawIOBase` | 由 `IResourceStreamFactory.create_resource_stream` 方法创建的流。 |

**Returns:** None.

### 另见
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
