---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "新しい Layout のインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/layout/__init__/
is_root: false
weight: 10
---


## __init__

新しい Layout のインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#name-width-height}

新しい [`Layout`](/viewer/python-net/groupdocs.viewer.results/layout/) のインスタンスを初期化します。

```python
def __init__(self, name, width, height):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| name | `str` | レイアウトの名前です。 |
| width | `float` | レイアウトの幅（ピクセル単位）。 |
| height | `float` | レイアウトの高さ（ピクセル単位）。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `name` が None または空の場合。 |

### 参照
* class [`Layout`](/viewer/python-net/groupdocs.viewer.results/layout/)
