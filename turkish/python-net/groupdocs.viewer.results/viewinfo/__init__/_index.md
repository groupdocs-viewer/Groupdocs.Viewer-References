---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "ViewInfo'ın yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.results/viewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) örneği başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages}

Yeni bir ViewInfo örneği başlatır.

```python
def __init__(self, file_type, pages):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_type | `FileType` | Dosyanın türü. |
| pages | `List[Page]` | Görüntülenecek sayfaların listesi. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `pages` None ise. |

### Ayrıca Bakınız
* class [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)
