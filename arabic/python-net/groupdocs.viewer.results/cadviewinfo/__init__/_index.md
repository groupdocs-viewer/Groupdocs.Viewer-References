---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُهيئ نسخة جديدة من CadViewInfo."
type: docs
url: /ar/python-net/groupdocs.viewer.results/cadviewinfo/__init__/
is_root: false
weight: 10
---


## __init__ {#file_type-pages-layers-layouts}

يُهيئ نسخة جديدة من CadViewInfo.

```python
def __init__(self, file_type, pages, layers, layouts):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_type | `FileType` | نوع الملف. |
| pages | `List[Page]` | قائمة الصفحات للعرض. |
| layers | `List[Layer]` | قائمة الطبقات الموجودة في رسم CAD. |
| layouts | `List[Layout]` | قائمة الطبقات الموجودة في رسم CAD. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يتم رفع الاستثناء عندما تكون `layouts` فارغة أو None. |

### انظر أيضًا
* class [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)
