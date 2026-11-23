---
title: "for_rendering_by_scale_factor メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "スケール係数でレンダリングするための CadOptions インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

スケール係数でレンダリングするための CadOptions インスタンスを初期化します。

コード例については、ドキュメントをご覧ください。

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| scale_factor | `float` | 1 より大きい値は出力結果を拡大し、0 から 1 の間の値は出力結果を縮小します。 |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `scale_factor` が 0 以下のときに発生します。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def set_image_size():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("set_image_size/image_with_size_limits.pdf")
        png_options.cad_options = CadOptions.for_rendering_by_scale_factor(0.5)
        viewer.view(png_options)

if __name__ == "__main__":
    set_image_size()
```

### 参照
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
