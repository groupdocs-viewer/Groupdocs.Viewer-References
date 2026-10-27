---
title: "طريقة from_rgb"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "ينشئ قيمة Argb32Color من القنوات الحمراء والخضراء والزرقاء المحددة، مع ضبط قناة الألفا لتكون غير شفافة بالكامل."
type: docs
url: /ar/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

ينشئ قيمة Argb32Color من القنوات الحمراء والخضراء والزرقاء المحددة، مع ضبط قناة الألفا لتكون غير شفافة بالكامل.

```python
def from_rgb(cls, red, green, blue):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| red | `int` | قيمة قناة الأحمر. |
| green | `int` | قيمة قناة الأخضر. |
| blue | `int` | قيمة قناة الأزرق. |

**Returns:** Argb32Color: New Argb32Color value.

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### انظر أيضًا
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
