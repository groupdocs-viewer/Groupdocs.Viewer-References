---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个新的 PdfViewInfo 实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

初始化一个新的 PdfViewInfo 实例。

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-printing_allowed}

初始化一个新的 PdfViewInfo 实例。

```python
def __init__(self, file_type, pages, printing_allowed):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_type | `FileType` | 文件的类型。 |
| pages | `List[Page]` | 要查看的页面列表。 |
| printing_allowed | `bool` | 打印权限指示器。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `pages` 为 None 时。 |

### 另见
* class [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/)
