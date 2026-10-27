---
title: "طريقة get_file_key"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يرجع معرفًا فريدًا لمدخل الذاكرة المؤقتة الذي يمثل ملفًا."
type: docs
url: /ar/python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

يرجع معرفًا فريدًا لمدخل الذاكرة المؤقتة الذي يمثل ملفًا.

```python
def get_file_key(cls, extension):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| extension | `str` | لاحقة اسم الملف (بما في ذلك النقطة \".\") مثال: \".doc\". |

**Returns:** str: Unique identifier for the cache entry that represents file.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `extension` None أو فارغًا. |

### انظر أيضًا
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
