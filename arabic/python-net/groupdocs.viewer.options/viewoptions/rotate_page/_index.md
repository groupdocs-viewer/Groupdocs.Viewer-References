---
title: "طريقة rotate_page"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يطبق دورانًا باتجاه عقارب الساعة على الصفحة."
type: docs
url: /ar/python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

يطبق دورانًا باتجاه عقارب الساعة على الصفحة.

للتفاصيل، راجع الوثائق على https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/.

```python
def rotate_page(self, page_number, rotation):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| page_number | `int` | يجب أن يكون رقم الصفحة أكبر من 0 بشكل صارم. |
| rotation | `Rotation` | قيمة الدوران. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان الدوران للصفحة ذات الرقم `page_number` قد أُضيف بالفعل. |

### انظر أيضًا
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
