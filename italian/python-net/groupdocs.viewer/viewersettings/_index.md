---
title: "Classe ViewerSettings"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Definisce le impostazioni per personalizzare il comportamento di Viewer."
type: docs
url: /it/python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

Definisce le impostazioni per personalizzare il comportamento di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Il tipo ViewerSettings espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | Inizializza una nuova istanza di ViewerSettings. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | Inizializza una nuova istanza di ViewerSettings. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | Inizializza una nuova istanza di ViewerSettings. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | L'implementazione della cache utilizzata per memorizzare i risultati del rendering. |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | L'implementazione del logger utilizzata per la registrazione (Errori, Avvisi, Tracce). |

### Esempio

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

### Vedi anche
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
