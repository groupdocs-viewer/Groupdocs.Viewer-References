---
title: "get_page_key メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ページファイルを表すキャッシュエントリの一意の識別子を返します。"
type: docs
url: /ja/python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

ページファイルを表すキャッシュエントリの一意の識別子を返します。

```python
def get_page_key(cls, page_number, extension):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| page_number | `int` | ページ番号。 |
| extension | `str` | ファイル名のサフィックス（ピリオド「.」を含む）例: ".doc"。 |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `extension` が None または空の場合。 |

### 参照
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
