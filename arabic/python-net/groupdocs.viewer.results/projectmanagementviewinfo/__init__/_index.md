---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُهيئ نسخة جديدة من ProjectManagementViewInfo."
type: docs
url: /ar/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

يُنشئ مثالًا جديدًا من [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-start_date-end_date}

يُهيئ نسخة جديدة من ProjectManagementViewInfo.

```python
def __init__(self, file_type, pages, start_date, end_date):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_type | `FileType` | نوع الملف. |
| pages | `List[Page]` | قائمة الصفحات للعرض. |
| start_date | `datetime` | تاريخ ووقت بدء المشروع. |
| end_date | `datetime` | تاريخ ووقت إكمال المشروع. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `pages` هو None. |

### انظر أيضًا
* class [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/)
