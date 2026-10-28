---
title: "get_file_key yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Dosyayı temsil eden önbellek girdisi için benzersiz tanımlayıcı döndürür."
type: docs
url: /tr/python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

Dosyayı temsil eden önbellek girdisi için benzersiz tanımlayıcı döndürür.

```python
def get_file_key(cls, extension):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| extension | `str` | Dosya adı son eki (nokta "." dahil) ör. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents file.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | Eğer `extension` None veya boş ise. |

### Ayrıca Bakınız
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
