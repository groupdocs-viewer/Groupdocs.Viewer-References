---
title: "get_resource_filter yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Resource nesnelerini temsil eden önbellek girdilerini aramak için bir filtre dizesi döndürür."
type: docs
url: /tr/python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

[`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) nesnelerini temsil eden önbellek girdilerini aramak için bir filtre dizesi döndürür.

```python
def get_resource_filter(cls, page_number):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page_number | `int` | Sayfa numarası. |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `page_number` sıfırdan küçük veya eşit olduğunda. |

### Ayrıca Bakınız
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
