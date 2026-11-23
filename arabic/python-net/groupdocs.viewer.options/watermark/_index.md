---
title: "فئة Watermark"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل علامة مائية نصية."
type: docs
url: /ar/python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

يمثل علامة مائية نصية.

انظر الوثائق عبر الإنترنت لمزيد من المعلومات.

نوع Watermark يُظهر الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | يُنشئ مثيلاً من الفئة [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | لون العلامة المائية. القيمة الافتراضية هي `Rgb24Color.known_colors.css_level1.red`. |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | اسم الخط المستخدم للعلامة المائية. |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | موضع العلامة المائية. القيمة الافتراضية هي `Position.diagonal`. |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | حجم العلامة المائية. القيمة الافتراضية هي [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/). |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | نص العلامة المائية. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # تحميل المستند
    with Viewer("sample.docx") as viewer:
        # إنشاء ملف HTML.
        viewOptions = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark.html"
        )
        # إضافة علامة مائية.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```

### Guides
أدلة المهام التي تستخدم `Watermark`:

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### انظر أيضًا
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
