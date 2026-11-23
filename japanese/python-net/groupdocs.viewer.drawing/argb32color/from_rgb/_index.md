---
title: "from_rgb メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "指定された Red、Green、Blue チャンネルから Argb32Color 値を作成し、Alpha チャンネルは完全に不透明に設定されます。"
type: docs
url: /ja/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

指定された Red、Green、Blue チャンネルから Argb32Color 値を作成し、Alpha チャンネルは完全に不透明に設定されます。

```python
def from_rgb(cls, red, green, blue):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| red | `int` | 赤チャンネルの値。 |
| green | `int` | 緑チャンネルの値。 |
| blue | `int` | 青チャンネルの値。 |

**Returns:** Argb32Color: New Argb32Color value.

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### 参照
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
