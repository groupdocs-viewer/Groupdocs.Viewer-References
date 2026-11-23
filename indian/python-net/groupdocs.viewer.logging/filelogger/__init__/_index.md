---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक लॉगर को आरंभ करता है जो फ़ाइल में संदेश लिखता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.logging/filelogger/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

एक लॉगर को आरंभ करता है जो फ़ाइल में संदेश लिखता है।

```python
def __init__(self, file_name):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_name | `str` | पथ सहित पूर्ण फ़ाइल नाम। |

### उदाहरण

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

### साथ में देखें
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
