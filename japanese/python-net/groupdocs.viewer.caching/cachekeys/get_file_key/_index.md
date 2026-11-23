---
title: "get_file_key メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ファイルを表すキャッシュエントリの一意の識別子を返します。"
type: docs
url: /ja/python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

ファイルを表すキャッシュエントリの一意の識別子を返します。

```python
def get_file_key(cls, extension):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| extension | `str` | ファイル名のサフィックス（ピリオド「.」を含む）例: ".doc"。 |

**Returns:** str: Unique identifier for the cache entry that represents file.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | もし `extension` が None または空の場合。 |

### 参照
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
