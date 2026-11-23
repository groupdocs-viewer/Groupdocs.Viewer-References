---
title: "get_resource_key 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "返回表示 Resource 对象的缓存条目的唯一标识符。"
type: docs
url: /zh/python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

返回表示 [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) 对象的缓存条目的唯一标识符。

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| page_number | `int` | 页面的编号。 |
| resource | `Resource` | HTML 资源。 |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `page_number` 小于或等于零，或 `resource` 为 None。 |

### 另见
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
