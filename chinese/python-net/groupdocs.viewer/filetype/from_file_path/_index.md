---
title: "from_file_path 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "提取文件扩展名并将其映射到文件类型。"
type: docs
url: /zh/python-net/groupdocs.viewer/filetype/from_file_path/
is_root: false
weight: 1100
---


## from_file_path {#file_path}

提取文件扩展名并将其映射到文件类型。

```python
def from_file_path(cls, file_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | `str` | 文件名或文件路径。 |

**Returns:** FileType: The detected file type if supported; otherwise returns `FileType.unknown`.

### 另见
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
