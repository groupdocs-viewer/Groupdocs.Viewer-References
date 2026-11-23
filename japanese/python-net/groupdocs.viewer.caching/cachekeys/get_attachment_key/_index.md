---
title: "get_attachment_key メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "添付ファイルを表すキャッシュエントリの一意の識別子を返します。"
type: docs
url: /ja/python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

添付ファイルを表すキャッシュエントリの一意の識別子を返します。

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| attachment_id | `str` | 添付ファイルの（単一ファイルのコンテキストにおける）一意の識別子。 |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `attachment_id` が null または空の場合にスローされます。 |

### 参照
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
