---
title: "parse_from_filename_with_extension 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "返回一个 Image2DFormat 值，该值对应于从指定文件名提取的文件扩展名。"
type: docs
url: /zh/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_filename_with_extension/
is_root: false
weight: 1050
---


## parse_from_filename_with_extension {#filename}

返回一个 Image2DFormat 值，该值对应于从指定文件名提取的文件扩展名。

```python
def parse_from_filename_with_extension(cls, filename):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| filename | `str` | 任意文件名，可以是相对路径或完整路径。 |

**Returns:** Image2DFormat: Image2DFormat value. Returns `Image2DFormat.undefined` if the extension cannot be recognized.

### 另见
* class [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/)
