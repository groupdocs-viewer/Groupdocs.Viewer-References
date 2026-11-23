---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 LotusNotesViewInfo 的新实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/lotusnotesviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

初始化一个新的 [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/) 实例。

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

初始化一个新的 [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/) 类实例。

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_type | `FileType` | 文件的类型。 |
| pages | `List[Page]` | 要查看的页面列表。 |
| notes_count | `int` | Lotus 数据库存储文件中包含的笔记计数。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `notes_count` 为 None 时抛出。 |

### 另见
* class [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/)
