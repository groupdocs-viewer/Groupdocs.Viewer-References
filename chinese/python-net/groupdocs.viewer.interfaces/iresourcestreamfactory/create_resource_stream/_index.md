---
title: "create_resource_stream 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "创建用于写入输出 HTML 资源数据的流。"
type: docs
url: /zh/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/
is_root: false
weight: 1010
---


## create_resource_stream {#page_number-resource}

创建用于写入输出 HTML 资源数据的流。

```python
def create_resource_stream(self, page_number, resource):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| page_number | `int` | 页面的编号。 |
| resource | `Resource` | HTML 资源，例如字体、样式、图像或图形。 |

**Returns:** io.RawIOBase: Stream used to write output resource data.

### 示例

```python
from groupdocs.viewer import Viewer

viewer = Viewer()
factory = viewer.resource_stream_factory

# 在第 1 页为 CSS 资源创建流。
stream = factory.create_resource_stream(pageNumber=1, resource="style.css")
with stream:
    stream.write(b"body { font-family: Arial; }")
```

### 另见
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
