---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "LoadOptions sınıfının bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

[`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) sınıfının bir örneğini başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

Yeni bir LoadOptions örneği başlatır.

Kod örneği için, belgeleri inceleyin.

```python
def __init__(self, file_type):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_type | `FileType` | Açılacak dosyanın türü. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `file_type` None ise. |

### Örnek

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Ayrıca Bakınız
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
