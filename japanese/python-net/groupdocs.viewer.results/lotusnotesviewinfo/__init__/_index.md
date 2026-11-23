---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "LotusNotesViewInfo の新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/lotusnotesviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

新しい [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/) のインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

新しい [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/) クラスのインスタンスを初期化します。

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_type | `FileType` | ファイルの種類です。 |
| pages | `List[Page]` | 表示するページのリストです。 |
| notes_count | `int` | Lotus データベースストレージファイルに含まれるノート数。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `notes_count` が None の場合に発生します。 |

### 参照
* class [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/)
