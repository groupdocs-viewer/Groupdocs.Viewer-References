---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بتهيئة نسخة من الفئة LoadOptions."
type: docs
url: /ar/python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

يُهيء مثيلاً من الفئة [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

يُهيء مثيلاً جديداً من LoadOptions.

للحصول على مثال على الشيفرة، راجع الوثائق.

```python
def __init__(self, file_type):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_type | `FileType` | نوع الملف المراد فتحه. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `file_type` يساوي None. |

### مثال

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### انظر أيضًا
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
