---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个新的 CadViewInfo 实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/cadviewinfo/__init__/
is_root: false
weight: 10
---


## __init__ {#file_type-pages-layers-layouts}

初始化一个新的 CadViewInfo 实例。

```python
def __init__(self, file_type, pages, layers, layouts):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_type | `FileType` | 文件的类型。 |
| pages | `List[Page]` | 要查看的页面列表。 |
| layers | `List[Layer]` | 该 CAD 绘图包含的图层列表。 |
| layouts | `List[Layout]` | 该 CAD 绘图包含的图层列表。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `layouts` 为 None 时抛出。 |

### 另见
* class [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)
