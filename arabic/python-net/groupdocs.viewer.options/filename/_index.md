---
title: "الفئة FileName"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "اسم الملف."
type: docs
url: /ar/python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

اسم الملف.

نوع FileName يعرض الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | ينشئ مثيلاً من الفئة [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/). |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | يعيد سلسلة تمثل الكائن الحالي. |

### الحقول
| حقل | الوصف |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | اسم الملف الفارغ. |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | اسم الملف المصدر. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, FileName

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "output/archive_{0}.html"
    )
    view_options.archive_options.file_name = FileName("Sample Files")
    viewer.view(view_options)
```

### انظر أيضًا
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
