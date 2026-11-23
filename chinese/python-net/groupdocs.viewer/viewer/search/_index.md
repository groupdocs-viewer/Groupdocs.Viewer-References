---
title: "search 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "执行文本搜索，并根据提供的选项在已加载的文档中高亮显示找到的文本。"
type: docs
url: /zh/python-net/groupdocs.viewer/viewer/search/
is_root: false
weight: 1110
---


## search {#options}

执行文本搜索，并根据提供的选项在已加载的文档中高亮显示找到的文本。

```python
def search(self, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | `SearchHighlightOptions` | 搜索和高亮选项，包括要搜索的文本短语。不能为空。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `options` 为 None。 |

### 另见
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
