---
title: "طريقة get_resource_filter"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "تُرجع سلسلة تصفية للبحث عن إدخالات التخزين المؤقت التي تمثل كائنات Resource."
type: docs
url: /ar/python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

يرجع سلسلة تصفية للبحث عن مدخلات الذاكرة المؤقتة التي تمثل كائنات [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/).

```python
def get_resource_filter(cls, page_number):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| page_number | `int` | رقم الصفحة. |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما يكون `page_number` أقل من أو يساوي الصفر. |

### انظر أيضًا
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
