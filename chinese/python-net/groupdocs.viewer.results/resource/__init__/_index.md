---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个新的 Resource 实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/resource/__init__/
is_root: false
weight: 10
---


## __init__

初始化一个新的 Resource 实例。

```python
def __init__(self):
    ...
```

## __init__ {#file_name-nested}

初始化一个新的 Resource 实例。

```python
def __init__(self, file_name, nested):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_name | `str` | 资源文件名。 |
| nested | `bool` | 指示资源是否位于另一个资源内部，例如位于 CSS 或 SVG 资源中的字体资源。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `file_name` 为 None 或为空时抛出。 |

### 另见
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)
