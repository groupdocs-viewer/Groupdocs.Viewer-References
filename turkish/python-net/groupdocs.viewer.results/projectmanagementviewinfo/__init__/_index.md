---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "ProjectManagementViewInfo sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/) örneği başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-start_date-end_date}

ProjectManagementViewInfo sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, file_type, pages, start_date, end_date):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_type | `FileType` | Dosyanın türü. |
| pages | `List[Page]` | Görüntülenecek sayfaların listesi. |
| start_date | `datetime` | Projenin başlatıldığı tarih ve saat. |
| end_date | `datetime` | Projenin tamamlanması gereken tarih ve saat. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `pages` None ise. |

### Ayrıca Bakınız
* class [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/)
