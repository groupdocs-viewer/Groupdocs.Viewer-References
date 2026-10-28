---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "OutlookViewInfo sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/) örneği başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Yeni bir OutlookViewInfo örneği başlatır.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_type | `FileType` | Dosyanın türü. |
| pages | `List[Page]` | Görüntülenecek sayfaların listesi. |
| folders | `List[str]` | Outlook Veri dosyasında bulunan klasörlerin listesi. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `folders` None olduğunda fırlatılır. |

### Ayrıca Bakınız
* class [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/)
