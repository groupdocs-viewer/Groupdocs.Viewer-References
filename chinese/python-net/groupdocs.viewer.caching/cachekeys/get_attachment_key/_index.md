---
title: "get_attachment_key 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "返回表示附件文件的缓存条目的唯一标识符。"
type: docs
url: /zh/python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

返回表示附件文件的缓存条目的唯一标识符。

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attachment_id | `str` | 在单文件上下文中唯一的附件标识符。 |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `attachment_id` 为 null 或为空时抛出。 |

### 另见
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
