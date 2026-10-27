---
title: "فئة CadOptions"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "خيارات عرض رسومات CAD."
type: docs
url: /ar/python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

خيارات عرض رسومات CAD.

لمزيد من المعلومات وأمثلة الشيفرة، راجع وثائق Render CAD drawings and models as HTML, PDF, and image files و Specify rendering options for CAD files.

يعرض نوع CadOptions الأعضاء التالية:

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | ينشئ مثيلًا من CadOptions للعرض حسب الارتفاع. |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | ينشئ مثيلًا من CadOptions للعرض حسب عامل المقياس. |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | ينشئ مثيلًا من الفئة [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadapplications/) للعرض حسب العرض. |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | ينشئ مثيلًا من فئة CadOptions للعرض حسب العرض والارتفاع. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | لون خلفية الصورة. |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | العلم الذي يفعّل وضع تحويل موجه للأداء لجميع صيغ CAD، حيث يؤدي ضبطه إلى True إلى تسريع التحويل على حساب انخفاض جودة المخرجات؛ القيمة الافتراضية هي False للحصول على أقصى جودة. |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | ارتفاع نتيجة الإخراج (بالبكسل). |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | طبقات رسم CAD التي سيتم عرضها. |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | اسم التخطيط المحدد للعرض. اسم التخطيط حساس لحالة الأحرف. |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | ملف تكوين طابعة PC3. |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | العلم الذي يشير إلى ما إذا كان يجب عرض التخطيطات من مستند CAD. |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | عامل المقياس. القيمة التي تزيد عن 1 تكبر نتيجة الإخراج؛ القيمة بين 0 و 1 تصغر نتيجة الإخراج. |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | مناطق الرسم التي سيتم عرضها. |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | عرض نتيجة الإخراج (بالبكسل). |

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
        # التصيير حسب العرض وتمكين وضع الأداء
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### انظر أيضًا
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
