---
title: ViewerSettings class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Defines settings for customizing Viewer behaviour."
type: docs
url: /python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

Defines settings for customizing [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) behaviour.

The ViewerSettings type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | Initializes a new ViewerSettings instance. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | Initializes a new ViewerSettings instance. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | Initializes a new ViewerSettings instance. |

### Properties
| Property | Description |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | The cache implementation used for storing rendering results. |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | The logger implementation used for logging (Errors, Warnings, Traces). |

### Example

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "example/page_{0}.html"
    )
    viewer.view(html_options)
```

### See Also
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
