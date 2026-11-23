---
title: "get_resource_key メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Resource オブジェクトを表すキャッシュエントリの一意の識別子を返します。"
type: docs
url: /ja/python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

[`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) オブジェクトを表すキャッシュエントリの一意の識別子を返します。

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| page_number | `int` | ページ番号。 |
| resource | `Resource` | HTML リソース。 |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `page_number` が 0 以下、または `resource` が None の場合。 |

### 参照
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
