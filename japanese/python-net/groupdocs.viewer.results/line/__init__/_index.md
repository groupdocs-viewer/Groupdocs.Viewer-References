---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Line の新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

新しい [`Line`](/viewer/python-net/groupdocs.viewer.results/line/) のインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

新しい [`Line`](/viewer/python-net/groupdocs.viewer.results/line/) クラスのインスタンスを初期化します。

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| line | `str` | 行です。 |
| x | `float` | 行を含む矩形が始まるページレイアウト上の最上部左側点の X 座標です。 |
| y | `float` | 行を含む矩形が始まるページレイアウト上の最上部左側点の Y 座標です。 |
| width | `float` | 行を含む矩形の幅（ピクセル単位）です。 |
| height | `float` | ラインを含む矩形の高さ（ピクセル単位）。 |
| words | `List[Word]` | 行に含まれる単語。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `line` が null または空、または `words` が null のときに発生します。 |

### 参照
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
