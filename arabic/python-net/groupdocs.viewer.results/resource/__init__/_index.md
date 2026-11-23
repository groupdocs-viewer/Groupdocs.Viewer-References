---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُنشئ مثالًا جديدًا من Resource."
type: docs
url: /ar/python-net/groupdocs.viewer.results/resource/__init__/
is_root: false
weight: 10
---


## __init__

يُنشئ مثالًا جديدًا من Resource.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-nested}

يُنشئ مثالًا جديدًا من Resource.

```python
def __init__(self, file_name, nested):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_name | `str` | اسم ملف المورد. |
| nested | `bool` | يشير إلى ما إذا كان المورد موجودًا داخل مورد آخر، على سبيل المثال مورد الخط الموجود في مورد CSS أو SVG. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يتم رفع الاستثناء عندما تكون `file_name` فارغة أو None. |

### انظر أيضًا
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)
