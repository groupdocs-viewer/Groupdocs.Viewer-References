---
title: "Classe ConsoleLogger"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Écrit les messages de journal dans la console."
type: docs
url: /fr/python-net/groupdocs.viewer.logging/consolelogger/
is_root: false
weight: 10
---


## ConsoleLogger class

Écrit les messages de journal dans la console.

Le type ConsoleLogger expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.logging/consolelogger/__init__/) |  |

### Méthodes
| Méthode | Description |
| :- | :- |
| [error](/viewer/python-net/groupdocs.viewer.logging/consolelogger/error/#message-exception) | Écrit un message d’erreur dans la console. |
| [error_file](/viewer/python-net/groupdocs.viewer.logging/consolelogger/error_file/) |  |
| [error_string](/viewer/python-net/groupdocs.viewer.logging/consolelogger/error_string/) |  |
| [trace](/viewer/python-net/groupdocs.viewer.logging/consolelogger/trace/#message) | Écrit un message de trace dans la console. |
| [trace_file](/viewer/python-net/groupdocs.viewer.logging/consolelogger/trace_file/) |  |
| [trace_string](/viewer/python-net/groupdocs.viewer.logging/consolelogger/trace_string/) |  |
| [warning](/viewer/python-net/groupdocs.viewer.logging/consolelogger/warning/#message) | Écrit un message d’avertissement dans la console. |
| [warning_file](/viewer/python-net/groupdocs.viewer.logging/consolelogger/warning_file/) |  |
| [warning_string](/viewer/python-net/groupdocs.viewer.logging/consolelogger/warning_string/) |  |

### Exemple

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### Voir aussi
* module [`groupdocs.viewer.logging`](/viewer/python-net/groupdocs.viewer.logging/)
