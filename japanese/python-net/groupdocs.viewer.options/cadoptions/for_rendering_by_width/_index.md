---
title: "for_rendering_by_width メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "幅でレンダリングするための CadOptions クラスのインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

幅でレンダリングするための [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) クラスのインスタンスを初期化します。

```python
def for_rendering_by_width(cls, width):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| width | `int` | 出力結果の幅（ピクセル単位）。 |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `width` が 0 以下の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # CAD ファイルを読み込む
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True
        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### 参照
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
