---
title: "release_page_stream 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "释放由 IPageStreamFactory.createpagestream 方法创建的流。"
type: docs
url: /zh/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 1030
---


## release_page_stream {#page_number-page_stream}

释放由 [`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/) 方法创建的流。

```python
def release_page_stream(self, page_number, page_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| page_number | `int` | 页面的编号。 |
| page_stream | `io.RawIOBase` | 由 `IPageStreamFactory.create_page_stream` 方法创建的流。 |

### 另见
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
