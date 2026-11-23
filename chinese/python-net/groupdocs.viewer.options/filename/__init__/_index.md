---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 FileName 类的实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/filename/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

初始化 [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) 类的实例。

```python
def __init__(self, file_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_name | `str` | 文件的名称。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `file_name` 为 None。 |

### 示例

```python
from groupdocs.viewer.options import FileName

# 使用自定义存档名称创建 FileName 实例
custom_name = FileName("Sample Files")
```

### 另见
* class [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/)
