---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "FileName sınıfının bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/filename/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

[`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) sınıfının bir örneğini başlatır.

```python
def __init__(self, file_name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_name | `str` | Dosyanın adı. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `file_name` None ise. |

### Örnek

```python
from groupdocs.viewer.options import FileName

# Özel bir arşiv adıyla bir FileName örneği oluşturun
custom_name = FileName("Sample Files")
```

### Ayrıca Bakınız
* class [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/)
