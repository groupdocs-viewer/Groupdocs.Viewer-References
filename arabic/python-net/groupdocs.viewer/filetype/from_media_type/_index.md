---
title: "طريقة from_media_type"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بربط نوع وسائط الملف بـ FileType (مثال، 'application/pdf' يربط بـ FileType.pdf)."
type: docs
url: /ar/python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

يربط نوع وسائط الملف بـ [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (مثال: 'application/pdf' يربط بـ [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)).

```python
def from_media_type(cls, media_type):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| media_type | `str` | نوع وسائط الملف، مثال، ``application/pdf``. |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### انظر أيضًا
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
