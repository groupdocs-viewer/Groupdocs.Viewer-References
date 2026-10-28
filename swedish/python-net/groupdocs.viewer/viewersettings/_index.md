---
title: "ViewerSettings-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Definierar inställningar för att anpassa Viewer-beteende."
type: docs
url: /sv/python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

Definierar inställningar för att anpassa beteendet hos [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

ViewerSettings-typen exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | Initierar en ny ViewerSettings-instans. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | Initierar en ny ViewerSettings-instans. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | Initierar en ny ViewerSettings-instans. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | Cache-implementationen som används för att lagra renderingsresultat. |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | Logger-implementationen som används för loggning (fel, varningar, spårning). |

### Exempel

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

### Se även
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
