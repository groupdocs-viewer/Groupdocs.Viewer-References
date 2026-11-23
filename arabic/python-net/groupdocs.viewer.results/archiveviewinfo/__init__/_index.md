---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "ينشئ مثيلًا جديدًا من ArchiveViewInfo."
type: docs
url: /ar/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلاً جديدًا من [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

ينشئ مثيلاً جديدًا من ArchiveViewInfo.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_type | `FileType` | نوع الملف. |
| pages | `List[Page]` | قائمة الصفحات للعرض. |
| folders | `List[str]` | قائمة المجلدات الموجودة في ملف الأرشيف. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `folders` يساوي None. |

### انظر أيضًا
* class [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)
