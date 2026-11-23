---
title: "get_attachment_key yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Ek dosyasını temsil eden önbellek girdisi için benzersiz tanımlayıcı döndürür."
type: docs
url: /tr/python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

Ek dosyasını temsil eden önbellek girdisi için benzersiz tanımlayıcı döndürür.

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attachment_id | `str` | Tek dosya bağlamında benzersiz ek tanımlayıcısı. |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `attachment_id` null veya boş olduğunda fırlatılır. |

### Ayrıca Bakınız
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
