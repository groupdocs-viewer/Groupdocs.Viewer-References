---
title: "فئة ViewInfo"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل معلومات العرض لمستند عام."
type: docs
url: /ar/python-net/groupdocs.viewer.results/viewinfo/
is_root: false
weight: 180
---


## ViewInfo class

يمثل معلومات العرض لمستند عام.

يعرض نوع ViewInfo الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/) | يُهيئ مثيلًا جديدًا من [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/#file_type-pages) | يُهيئ مثيلًا جديدًا من ViewInfo. |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | يعيد سلسلة تمثل الكائن الحالي. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | نوع الملف. |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | قائمة الصفحات للعرض. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("sample.docx") as viewer:
    options = ViewInfoOptions.for_html_view()
    view_info = viewer.get_view_info(options)
    for page in view_info.pages:
        print(f"Page {page.number}: {page.name}")
```

### انظر أيضًا
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
