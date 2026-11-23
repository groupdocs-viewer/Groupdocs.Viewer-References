---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بتهيئة مثال من الفئة FileName."
type: docs
url: /ar/python-net/groupdocs.viewer.options/filename/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

ينشئ مثيلاً من الفئة [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/).

```python
def __init__(self, file_name):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_name | `str` | اسم الملف. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `file_name` None. |

### مثال

```python
from groupdocs.viewer.options import FileName

# إنشاء مثال FileName باسم أرشيف مخصص
custom_name = FileName("Sample Files")
```

### انظر أيضًا
* class [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/)
