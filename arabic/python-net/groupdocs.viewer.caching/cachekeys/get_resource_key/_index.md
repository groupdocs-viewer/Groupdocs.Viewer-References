---
title: "طريقة get_resource_key"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "تُرجع معرفًا فريدًا لإدخال التخزين المؤقت الذي يمثل كائن Resource."
type: docs
url: /ar/python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

يرجع معرفًا فريدًا لمدخل الذاكرة المؤقتة الذي يمثل كائن [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/).

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| page_number | `int` | رقم الصفحة. |
| resource | `Resource` | المورد HTML. |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `page_number` أقل من أو يساوي الصفر، أو إذا كان `resource` None. |

### انظر أيضًا
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
