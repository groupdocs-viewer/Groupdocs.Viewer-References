---
title: "search yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Metin araması gerçekleştirir ve bulunan metni, sağlanan seçeneklere göre yüklü belgede vurgular."
type: docs
url: /tr/python-net/groupdocs.viewer/viewer/search/
is_root: false
weight: 1110
---


## search {#options}

Metin araması gerçekleştirir ve bulunan metni, sağlanan seçeneklere göre yüklü belgede vurgular.

```python
def search(self, options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | `SearchHighlightOptions` | Arama ve vurgulama seçenekleri, arama yapılacak metin ifadesi dahil. None olmamalıdır. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `options` None ise. |

### Ayrıca Bakınız
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
