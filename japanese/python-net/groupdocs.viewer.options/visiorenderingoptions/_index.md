---
title: "VisioRenderingOptions クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Visio ドキュメントのレンダリングオプションを表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

Visio ドキュメントのレンダリングオプションを表します。

詳細については、ドキュメントをご覧ください。

VisioRenderingOptions 型は以下のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/) クラスのインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | 図の幅；高さは自動的に計算されます。デフォルト値は 100 です。 |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | このプロパティは、図ではなく Visio 図形のみをレンダリングします。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # Visio ドキュメントを読み込む
    with Viewer("map.vsdx") as viewer:
        # Visio ファイルを PDF に変換します。
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # マスターシェイプのみをレンダリングします。
        view_options.visio_rendering_options.render_figures_only = True
        # シェイプの幅をピクセル単位で指定します。
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
