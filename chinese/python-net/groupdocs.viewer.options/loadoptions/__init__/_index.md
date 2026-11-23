---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 LoadOptions 类的实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

初始化 [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) 类的实例。

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

初始化一个新的 LoadOptions 实例。

代码示例请参见文档。

```python
def __init__(self, file_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_type | `FileType` | 要打开的文件类型。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `file_type` 为 None。 |

### 示例

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### 另见
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
