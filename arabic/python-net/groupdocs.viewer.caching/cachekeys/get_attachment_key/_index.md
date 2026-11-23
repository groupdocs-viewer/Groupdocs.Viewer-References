---
title: "طريقة get_attachment_key"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يرجع معرفًا فريدًا لمدخل الذاكرة المؤقتة الذي يمثل ملف المرفق."
type: docs
url: /ar/python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

يرجع معرفًا فريدًا لمدخل الذاكرة المؤقتة الذي يمثل ملف المرفق.

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| attachment_id | `str` | معرف فريد (في سياق ملف واحد) للمرفق. |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يُرمى عندما يكون `attachment_id` null أو فارغ. |

### انظر أيضًا
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
