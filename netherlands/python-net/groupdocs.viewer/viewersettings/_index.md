---
title: "ViewerSettings klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Definieert instellingen voor het aanpassen van Viewer-gedrag."
type: docs
url: /nl/python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

Definieert instellingen voor het aanpassen van het gedrag van [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Het ViewerSettings-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | Initialiseert een nieuwe ViewerSettings-instantie. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | Initialiseert een nieuwe ViewerSettings-instantie. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | Initialiseert een nieuwe ViewerSettings-instantie. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | De cache-implementatie die wordt gebruikt voor het opslaan van renderresultaten. |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | De logger-implementatie die wordt gebruikt voor het loggen (Fouten, Waarschuwingen, Traces). |

### Voorbeeld

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

### Zie ook
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
