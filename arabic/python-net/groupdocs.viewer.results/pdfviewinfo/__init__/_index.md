---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُهيئ نسخة جديدة من PdfViewInfo."
type: docs
url: /ar/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

يُهيئ نسخة جديدة من PdfViewInfo.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-printing_allowed}

يُهيئ نسخة جديدة من PdfViewInfo.

```python
def __init__(self, file_type, pages, printing_allowed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_type | `FileType` | نوع الملف. |
| pages | `List[Page]` | قائمة الصفحات للعرض. |
| printing_allowed | `bool` | مؤشر إذن الطباعة. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عند كون `pages` None. |

### انظر أيضًا
* class [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/)
