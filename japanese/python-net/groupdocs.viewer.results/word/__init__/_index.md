---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Word の新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

新しい [`Word`](/viewer/python-net/groupdocs.viewer.results/word/) のインスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

新しい [`Word`](/viewer/python-net/groupdocs.viewer.results/word/) のインスタンスを初期化します。

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| word | `str` | 単語です。 |
| x | `float` | 単語を含む矩形が始まるページレイアウト上の最上部左側点の X 座標です。 |
| y | `float` | 単語を含む矩形が始まるページレイアウト上の最上部左側点の Y 座標です。 |
| width | `float` | 単語を含む矩形の幅です。 |
| height | `float` | 単語を含む矩形の高さです。 |
| characters | `List[Character]` | 単語に含まれる文字。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `characters` が null の場合。 |

### 参照
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
