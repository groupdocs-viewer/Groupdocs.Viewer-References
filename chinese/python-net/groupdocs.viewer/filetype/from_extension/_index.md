---
title: "from_extension 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "将文件扩展名映射到文件类型。"
type: docs
url: /zh/python-net/groupdocs.viewer/filetype/from_extension/
is_root: false
weight: 1090
---


## from_extension {#extension}

将文件扩展名映射到文件类型。

```python
def from_extension(cls, extension):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| extension | `str` | 文件扩展名可带或不带句点 '.'。 |

**Returns:** FileType: The corresponding file type if supported; otherwise `FileType.unknown`.

### 另见
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
