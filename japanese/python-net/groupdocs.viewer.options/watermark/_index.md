---
title: "Watermark クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "テキストの透かしを表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

テキストの透かしを表します。

詳細についてはオンラインドキュメントをご覧ください。

Watermark 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/) クラスのインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | 透かしの色。デフォルト値は `Rgb24Color.known_colors.css_level1.red` です。 |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | 透かしに使用されるフォント名。 |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | 透かしの位置。デフォルト値は `Position.diagonal` です。 |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | 透かしのサイズ。デフォルト値は [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/) です。 |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | 透かしのテキスト。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # ドキュメントを読み込む
    with Viewer("sample.docx") as viewer:
        # HTML ファイルを作成します。
        viewOptions = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark.html"
        )
        # 透かしを追加します。
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```

### Guides
`Watermark` を使用するタスク ガイド：

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
