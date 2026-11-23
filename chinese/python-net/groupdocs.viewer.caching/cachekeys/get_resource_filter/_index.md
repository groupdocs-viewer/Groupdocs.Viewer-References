---
title: "get_resource_filter 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "返回用于搜索表示 Resource 对象的缓存条目的过滤字符串。"
type: docs
url: /zh/python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

返回用于搜索表示 [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) 对象的缓存条目的过滤字符串。

```python
def get_resource_filter(cls, page_number):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| page_number | `int` | 页面的编号。 |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `page_number` 小于或等于零时。 |

### 另见
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
