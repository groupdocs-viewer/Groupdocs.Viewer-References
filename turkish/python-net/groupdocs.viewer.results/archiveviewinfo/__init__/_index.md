---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "ArchiveViewInfo sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/) örneği başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Yeni bir ArchiveViewInfo örneği başlatır.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_type | `FileType` | Dosyanın türü. |
| pages | `List[Page]` | Görüntülenecek sayfaların listesi. |
| folders | `List[str]` | Arşiv dosyası içinde bulunan klasörlerin listesi. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `folders` None ise. |

### Ayrıca Bakınız
* class [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)
