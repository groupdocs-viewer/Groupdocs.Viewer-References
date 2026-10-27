---
title: "Classe FileLogger"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Écrit les messages de journal dans le fichier."
type: docs
url: /fr/python-net/groupdocs.viewer.logging/filelogger/
is_root: false
weight: 20
---


## FileLogger class

Écrit les messages de journal dans le fichier.

Le type FileLogger expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.logging/filelogger/__init__/#file_name) | Initialise un journal qui écrit les messages dans un fichier. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [error](/viewer/python-net/groupdocs.viewer.logging/filelogger/error/#message-exception) | Écrit un message d’erreur dans la console. Les messages du journal d’erreurs fournissent des informations sur les événements irrécupérables dans le flux de l’application. |
| [error_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_file/) |  |
| [error_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_string/) |  |
| [trace](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace/#message) | Écrit un message de trace dans le journal. Les messages du journal de trace fournissent des informations généralement utiles sur le flux de l’application. |
| [trace_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_file/) |  |
| [trace_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_string/) |  |
| [warning](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning/#message) | Écrit un message d’avertissement dans la console. |
| [warning_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_file/) |  |
| [warning_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_string/) |  |

### Exemple

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

### Voir aussi
* module [`groupdocs.viewer.logging`](/viewer/python-net/groupdocs.viewer.logging/)
