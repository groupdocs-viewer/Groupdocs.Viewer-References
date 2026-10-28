---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "MboxViewInfo yeni bir örnek başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.results/mboxviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

`[`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/)` sınıfının yeni bir örneğini başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

Yeni bir `[`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/)` örneğini başlatır.

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_type | `FileType` | Dosyanın türü. |
| pages | `List[Page]` | Görüntülenecek sayfaların listesi. |
| notes_count | `int` | Lotus veritabanı depolama dosyasında bulunan not sayısı. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `notes_count` None ise. |

### Ayrıca Bakınız
* class [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/)
