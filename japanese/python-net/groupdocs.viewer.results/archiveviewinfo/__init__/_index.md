---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ArchiveViewInfo の新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

新しい [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/) インスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

新しい ArchiveViewInfo インスタンスを初期化します。

```python
def __init__(self, file_type, pages, folders):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_type | `FileType` | ファイルの種類です。 |
| pages | `List[Page]` | 表示するページのリストです。 |
| folders | `List[str]` | アーカイブファイルに含まれるフォルダーの一覧。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `folders` が None の場合。 |

### 参照
* class [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)
