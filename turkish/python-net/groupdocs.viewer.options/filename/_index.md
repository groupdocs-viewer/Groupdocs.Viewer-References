---
title: "FileName sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Dosya adı."
type: docs
url: /tr/python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

Dosya adı.

FileName türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) sınıfının bir örneğini başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | Mevcut nesneyi temsil eden bir dize döndürür. |

### Alanlar
| Alan | Açıklama |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | Boş dosya adı. |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | Kaynak dosyanın adı. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, FileName

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "output/archive_{0}.html"
    )
    view_options.archive_options.file_name = FileName("Sample Files")
    viewer.view(view_options)
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
