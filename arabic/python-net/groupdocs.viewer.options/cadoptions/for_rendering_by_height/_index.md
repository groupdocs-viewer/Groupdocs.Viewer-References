---
title: "طريقة for_rendering_by_height"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "ينشئ مثيلًا من CadOptions للعرض حسب الارتفاع."
type: docs
url: /ar/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

ينشئ مثيلًا من CadOptions للعرض حسب الارتفاع.

للحصول على مثال على الشيفرة، راجع الوثائق.

```python
def for_rendering_by_height(cls, height):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| height | `int` | ارتفاع نتيجة الإخراج (بالبكسل). |

**Returns:** CadOptions: New instance configured for rendering by height.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما يكون `height` أقل من أو يساوي الصفر. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### انظر أيضًا
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
