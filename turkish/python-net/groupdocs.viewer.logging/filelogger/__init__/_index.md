---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bir dosyaya mesaj yazan bir logger başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.logging/filelogger/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

Bir dosyaya mesaj yazan bir logger başlatır.

```python
def __init__(self, file_name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_name | `str` | Tam dosya adı ve yol. |

### Örnek

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import FileLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=FileLogger("./log.txt"))
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "write_logs_to_file/page_{0}.html"
    )
    viewer.view(html_options)
```

### Ayrıca Bakınız
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
