---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "新しい FileCache インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

新しい FileCache インスタンスを初期化します。

```python
def __init__(self, cache_path):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| cache_path | `str` | ドキュメントキャッシュが保存される相対パスまたは絶対パスです。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `cache_path` が None の場合。 |

## __init__ {#cache_path-cache_sub_folder}

FileCache クラスの新しいインスタンスを初期化します。

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| cache_path | `str` | ドキュメントキャッシュが保存される相対パスまたは絶対パスです。 |
| cache_sub_folder | `str` | `cache_path` に追加するサブフォルダーです。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `cache_sub_folder` が None の場合。 |

### 参照
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
