---
title: "for_rendering_by_height メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "高さでレンダリングするための CadOptions インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

高さでレンダリングするための CadOptions インスタンスを初期化します。

コード例については、ドキュメントをご覧ください。

```python
def for_rendering_by_height(cls, height):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| height | `int` | 出力結果の高さ（ピクセル単位）です。 |

**Returns:** CadOptions: New instance configured for rendering by height.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `height` がゼロ以下の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### 参照
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
