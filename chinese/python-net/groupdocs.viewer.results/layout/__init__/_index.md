---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个新的 Layout 实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/layout/__init__/
is_root: false
weight: 10
---


## __init__

初始化一个新的 Layout 实例。

```python
def __init__(self):
    ...
```

## __init__ {#name-width-height}

初始化一个新的 [`Layout`](/viewer/python-net/groupdocs.viewer.results/layout/) 实例。

```python
def __init__(self, name, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | `str` | 布局的名称。 |
| width | `float` | 布局的宽度（像素）。 |
| height | `float` | 布局的高度（像素）。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `name` 为 None 或为空时。 |

### 另见
* class [`Layout`](/viewer/python-net/groupdocs.viewer.results/layout/)
