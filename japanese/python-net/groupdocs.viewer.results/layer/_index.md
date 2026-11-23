---
title: "Layer クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "CAD 図面に含まれるレイヤーを表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

CAD 図面に含まれるレイヤーを表します。

Layer 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | 新しい [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) クラスのインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | 新しい Layer インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | 新しい Layer インスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | 現在の Layer が指定された Layer オブジェクトと同じかどうかを判断します。 |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | 現在の [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) が指定されたオブジェクトと等しいかどうかをチェックします。 |
| [equals_layer](/viewer/python-net/groupdocs.viewer.results/layer/equals_layer/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.results/layer/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | 現在の Layer オブジェクトのハッシュコードを返します。 |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | 現在のオブジェクトを表す文字列を返します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | レイヤーの名前。 |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | レイヤーの可視性インジケータ。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("output.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### 参照
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
