---
title: "فئة VisioRenderingOptions"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل خيارات لتصيير مستندات Visio."
type: docs
url: /ar/python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

يمثل خيارات لتصيير مستندات Visio.

للتفاصيل، راجع الوثائق.

النوع VisioRenderingOptions يعرض الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | ينشئ مثلاً من الفئة [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | عرض الشكل؛ الارتفاع يُحسب تلقائيًا. القيمة الافتراضية هي 100. |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | الخاصية تعرض فقط أشكال Visio، وليس مخططًا. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # تحميل مستند Visio
    with Viewer("map.vsdx") as viewer:
        # تحويل ملف Visio إلى PDF.
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # عرض فقط الأشكال الرئيسية.
        view_options.visio_rendering_options.render_figures_only = True
        # حدد عرض الشكل بالبكسل.
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### انظر أيضًا
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
