---
title: "ViewerSettings Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Definiert Einstellungen zum Anpassen des Viewer-Verhaltens."
type: docs
url: /de/python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

Definiert Einstellungen zur Anpassung des Verhaltens von [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Der ViewerSettings Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | Initialisiert eine neue ViewerSettings-Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | Initialisiert eine neue ViewerSettings-Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | Initialisiert eine neue ViewerSettings-Instanz. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | Die Cache-Implementierung, die zum Speichern von Rendering-Ergebnissen verwendet wird. |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | Die Logger-Implementierung, die zum Protokollieren (Fehler, Warnungen, Traces) verwendet wird. |

### Beispiel

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

### Siehe auch
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
