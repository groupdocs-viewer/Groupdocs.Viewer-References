---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بتهيئة نسخة جديدة من OutlookViewInfo."
type: docs
url: /ar/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

يُنشئ مثلاً جديدًا من [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

يُنشئ مثالًا جديدًا من OutlookViewInfo.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_type | `FileType` | نوع الملف. |
| pages | `List[Page]` | قائمة الصفحات للعرض. |
| folders | `List[str]` | قائمة المجلدات الموجودة في ملف بيانات Outlook. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يتم رمي الاستثناء عندما تكون `folders` None. |

### انظر أيضًا
* class [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/)
