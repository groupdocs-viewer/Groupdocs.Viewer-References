---
title: "get_resource_key yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Resource nesnesini temsil eden önbellek girdisi için benzersiz bir tanımlayıcı döndürür."
type: docs
url: /tr/python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

[`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) nesnesini temsil eden önbellek girdisi için benzersiz tanımlayıcı döndürür.

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page_number | `int` | Sayfanın numarası. |
| resource | `Resource` | HTML kaynağı. |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `page_number` sıfırdan küçük veya eşit ise veya `resource` None ise. |

### Ayrıca Bakınız
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
