---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ViewInfo の新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/viewinfo/__init__/
is_root: false
weight: 10
---


## __init__

新しいインスタンスを初期化します [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)。

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages}

新しい ViewInfo インスタンスを初期化します。

```python
def __init__(self, file_type, pages):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_type | `FileType` | ファイルの種類です。 |
| pages | `List[Page]` | 表示するページのリストです。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | もし `pages` が None の場合。 |

### 参照
* class [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)
