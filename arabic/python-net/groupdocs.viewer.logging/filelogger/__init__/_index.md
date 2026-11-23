---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُهيئ مسجلاً يكتب الرسائل إلى ملف."
type: docs
url: /ar/python-net/groupdocs.viewer.logging/filelogger/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

يُهيئ مسجلاً يكتب الرسائل إلى ملف.

```python
def __init__(self, file_name):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_name | `str` | اسم الملف الكامل مع المسار. |

### مثال

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

### انظر أيضًا
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
