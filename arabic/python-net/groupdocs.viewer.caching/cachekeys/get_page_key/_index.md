---
title: "طريقة get_page_key"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يرجع معرفًا فريدًا لمدخل الذاكرة المؤقتة الذي يمثل ملف صفحة."
type: docs
url: /ar/python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

يرجع معرفًا فريدًا لمدخل الذاكرة المؤقتة الذي يمثل ملف صفحة.

```python
def get_page_key(cls, page_number, extension):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| page_number | `int` | رقم الصفحة. |
| extension | `str` | لاحقة اسم الملف (بما في ذلك النقطة \".\") مثال: \".doc\". |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما تكون `extension` None أو فارغة. |

### انظر أيضًا
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
