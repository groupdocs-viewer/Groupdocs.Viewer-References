---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "PdfViewInfo sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

PdfViewInfo sınıfının yeni bir örneğini başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-printing_allowed}

PdfViewInfo sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, file_type, pages, printing_allowed):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_type | `FileType` | Dosyanın türü. |
| pages | `List[Page]` | Görüntülenecek sayfaların listesi. |
| printing_allowed | `bool` | Yazdırma izni göstergesi. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `pages` None olduğunda. |

### Ayrıca Bakınız
* class [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/)
