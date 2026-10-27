---
title: "طريقة for_rendering_by_scale_factor"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "ينشئ مثيلًا من CadOptions للعرض حسب عامل المقياس."
type: docs
url: /ar/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

ينشئ مثيلًا من CadOptions للعرض حسب عامل المقياس.

للحصول على مثال على الشيفرة، راجع الوثائق.

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| scale_factor | `float` | القيمة الأعلى من 1 تكبر نتيجة الإخراج؛ القيمة بين 0 و 1 تقلل نتيجة الإخراج. |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يتم رفع الاستثناء عندما يكون `scale_factor` أقل من أو يساوي الصفر. |

### مثال

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

### انظر أيضًا
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
