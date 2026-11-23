---
title: "get_file_key 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "返回表示文件的缓存条目的唯一标识符。"
type: docs
url: /zh/python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

返回表示文件的缓存条目的唯一标识符。

```python
def get_file_key(cls, extension):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| extension | `str` | 文件名后缀（包括句点 "."），例如 ".doc"。 |

**Returns:** str: Unique identifier for the cache entry that represents file.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `extension` 为 None 或为空。 |

### 另见
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
