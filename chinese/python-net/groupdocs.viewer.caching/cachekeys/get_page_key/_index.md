---
title: "get_page_key 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "返回表示页面文件的缓存条目的唯一标识符。"
type: docs
url: /zh/python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

返回表示页面文件的缓存条目的唯一标识符。

```python
def get_page_key(cls, page_number, extension):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| page_number | `int` | 页面的编号。 |
| extension | `str` | 文件名后缀（包括句点 "."），例如 ".doc"。 |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `extension` 为 None 或为空时。 |

### 另见
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
