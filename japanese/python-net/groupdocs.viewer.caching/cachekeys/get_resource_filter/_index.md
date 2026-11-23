---
title: "get_resource_filter メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Resource オブジェクトを表すキャッシュエントリを検索するためのフィルタ文字列を返します。"
type: docs
url: /ja/python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

[`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) オブジェクトを表すキャッシュエントリを検索するためのフィルタ文字列を返します。

```python
def get_resource_filter(cls, page_number):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| page_number | `int` | ページ数。 |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `page_number` が 0 以下の場合。 |

### 参照
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
