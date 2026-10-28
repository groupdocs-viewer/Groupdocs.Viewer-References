---
title: "get_page_key yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Sayfa dosyasını temsil eden önbellek girdisi için benzersiz tanımlayıcı döndürür."
type: docs
url: /tr/python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

Sayfa dosyasını temsil eden önbellek girdisi için benzersiz tanımlayıcı döndürür.

```python
def get_page_key(cls, page_number, extension):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| page_number | `int` | Sayfanın numarası. |
| extension | `str` | Dosya adı son eki (nokta "." dahil) ör. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `extension` None veya boş olduğunda. |

### Ayrıca Bakınız
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
