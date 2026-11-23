---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Layer クラスの新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

新しい [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) クラスのインスタンスを初期化します。

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.viewer.results import Layer

# 指定された名前でレイヤーを作成します。
layer = Layer("QUADRANT")
```

## __init__ {#name}

新しい Layer インスタンスを初期化します。

```python
def __init__(self, name):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| name | `str` | レイヤーの名前。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `name` が None または空の場合に発生します。 |

### 例

```python
from groupdocs.viewer.results import Layer

# 指定された名前でレイヤーを作成します
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

新しい Layer インスタンスを初期化します。

```python
def __init__(self, name, visible):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| name | `str` | レイヤーの名前。 |
| visible | `bool` | レイヤーの可視性インジケータ。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `name` が None または空の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### 参照
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
