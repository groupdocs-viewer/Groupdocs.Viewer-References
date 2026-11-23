---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个新的 ProjectManagementViewInfo 实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

初始化一个新的 [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/) 实例。

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-start_date-end_date}

初始化一个新的 ProjectManagementViewInfo 实例。

```python
def __init__(self, file_type, pages, start_date, end_date):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_type | `FileType` | 文件的类型。 |
| pages | `List[Page]` | 要查看的页面列表。 |
| start_date | `datetime` | 该项目开始的日期时间。 |
| end_date | `datetime` | 该项目完成的日期时间。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `pages` 为 None。 |

### 另见
* class [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/)
