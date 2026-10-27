---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بتهيئة نسخة جديدة من LotusNotesViewInfo."
type: docs
url: /ar/python-net/groupdocs.viewer.results/lotusnotesviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

يُهيئ نسخة جديدة من [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

يُهيئ نسخة جديدة من الفئة [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/).

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_type | `FileType` | نوع الملف. |
| pages | `List[Page]` | قائمة الصفحات للعرض. |
| notes_count | `int` | عدد الملاحظات الموجود في ملف تخزين قاعدة بيانات Lotus. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يتم الرفع عندما تكون `notes_count` None. |

### انظر أيضًا
* class [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/)
