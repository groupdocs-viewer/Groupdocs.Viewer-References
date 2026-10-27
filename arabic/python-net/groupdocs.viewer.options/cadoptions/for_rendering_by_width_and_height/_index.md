---
title: "طريقة for_rendering_by_width_and_height"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "ينشئ مثيلًا من فئة CadOptions للعرض حسب العرض والارتفاع."
type: docs
url: /ar/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/
is_root: false
weight: 1040
---


## for_rendering_by_width_and_height {#width-height}

ينشئ مثيلًا من فئة CadOptions للعرض حسب العرض والارتفاع.

للحصول على مثال على الشيفرة، راجع الوثائق.

```python
def for_rendering_by_width_and_height(cls, width, height):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | `int` | عرض نتيجة الإخراج (بالبكسل). |
| height | `int` | ارتفاع نتيجة الإخراج (بالبكسل). |

**Returns:** CadOptions: New instance of CadOptions class for rendering by width and height.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `height` أقل من أو يساوي الصفر. |

### انظر أيضًا
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
