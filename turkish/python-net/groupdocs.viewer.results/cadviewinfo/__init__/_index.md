---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "CadViewInfo sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.results/cadviewinfo/__init__/
is_root: false
weight: 10
---


## __init__ {#file_type-pages-layers-layouts}

CadViewInfo sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, file_type, pages, layers, layouts):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_type | `FileType` | Dosyanın türü. |
| pages | `List[Page]` | Görüntülenecek sayfaların listesi. |
| layers | `List[Layer]` | CAD çiziminde bulunan katmanların listesi. |
| layouts | `List[Layout]` | CAD çiziminde bulunan katmanların listesi. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `layouts` None olduğunda ortaya çıkar. |

### Ayrıca Bakınız
* class [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)
