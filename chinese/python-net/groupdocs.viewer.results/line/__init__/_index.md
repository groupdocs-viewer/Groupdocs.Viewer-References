---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 Line 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

初始化一个新的 [`Line`](/viewer/python-net/groupdocs.viewer.results/line/) 实例。

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

初始化一个新的 [`Line`](/viewer/python-net/groupdocs.viewer.results/line/) 类实例。

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| line | `str` | 该行。 |
| x | `float` | 包含行的矩形在页面布局中左上角的 X 坐标。 |
| y | `float` | 包含行的矩形在页面布局中左上角的 Y 坐标。 |
| width | `float` | 包含行的矩形的宽度（以像素为单位）。 |
| height | `float` | 包含该线的矩形的高度（以像素为单位）。 |
| words | `List[Word]` | 该行包含的单词。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `line` 为 null 或为空，或 `words` 为 null 时抛出。 |

### 另见
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
