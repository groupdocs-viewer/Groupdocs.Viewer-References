---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Watermark クラスのインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/watermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

[`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/) クラスのインスタンスを初期化します。

```python
def __init__(self, text):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| text | `str` | 透かしテキスト。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `text` が None または空の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

with Viewer("sample.docx") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "add_text_watermark/output-watermark.html"
    )
    view_options.watermark = Watermark("This is a watermark")
    viewer.view(view_options)
```

### 参照
* class [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/)
