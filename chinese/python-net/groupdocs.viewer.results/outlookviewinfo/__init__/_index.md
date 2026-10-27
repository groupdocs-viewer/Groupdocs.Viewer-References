---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 OutlookViewInfo 的新实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

初始化一个新的 [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/) 实例。

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

初始化一个新的 OutlookViewInfo 实例。

```python
def __init__(self, file_type, pages, folders):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_type | `FileType` | 文件的类型。 |
| pages | `List[Page]` | 要查看的页面列表。 |
| folders | `List[str]` | Outlook 数据文件中包含的文件夹列表。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `folders` 为 None 时抛出。 |

### 另见
* class [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/)
