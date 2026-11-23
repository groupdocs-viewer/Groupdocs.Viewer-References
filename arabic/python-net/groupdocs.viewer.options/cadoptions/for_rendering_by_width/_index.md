---
title: "طريقة for_rendering_by_width"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بتهيئة نسخة من فئة CadOptions للتصوير حسب العرض."
type: docs
url: /ar/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

ينشئ مثيلًا من الفئة [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadapplications/) للعرض حسب العرض.

```python
def for_rendering_by_width(cls, width):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | `int` | عرض نتيجة الإخراج (بالبكسل). |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `width` أقل من أو يساوي الصفر. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # تحميل ملف CAD
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

### انظر أيضًا
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
