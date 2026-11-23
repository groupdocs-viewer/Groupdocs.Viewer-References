---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "新しい Resource インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/resource/__init__/
is_root: false
weight: 10
---


## __init__

新しい Resource インスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#file_name-nested}

新しい Resource インスタンスを初期化します。

```python
def __init__(self, file_name, nested):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_name | `str` | リソースファイル名。 |
| nested | `bool` | リソースが別のリソース内に存在するかどうかを示します。例: CSS や SVG リソース内にあるフォントリソース。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `file_name` が None または空の場合に発生します。 |

### 参照
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)
