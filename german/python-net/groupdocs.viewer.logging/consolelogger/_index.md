---
title: "ConsoleLogger Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Schreibt Protokollnachrichten in die Konsole."
type: docs
url: /de/python-net/groupdocs.viewer.logging/consolelogger/
is_root: false
weight: 10
---


## ConsoleLogger class

Schreibt Protokollnachrichten in die Konsole.

Der ConsoleLogger-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.logging/consolelogger/__init__/) |  |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [error](/viewer/python-net/groupdocs.viewer.logging/consolelogger/error/#message-exception) | Schreibt eine Fehlermeldung in die Konsole. |
| [error_file](/viewer/python-net/groupdocs.viewer.logging/consolelogger/error_file/) |  |
| [error_string](/viewer/python-net/groupdocs.viewer.logging/consolelogger/error_string/) |  |
| [trace](/viewer/python-net/groupdocs.viewer.logging/consolelogger/trace/#message) | Schreibt eine Trace-Nachricht in die Konsole. |
| [trace_file](/viewer/python-net/groupdocs.viewer.logging/consolelogger/trace_file/) |  |
| [trace_string](/viewer/python-net/groupdocs.viewer.logging/consolelogger/trace_string/) |  |
| [warning](/viewer/python-net/groupdocs.viewer.logging/consolelogger/warning/#message) | Schreibt eine Warnmeldung in die Konsole. |
| [warning_file](/viewer/python-net/groupdocs.viewer.logging/consolelogger/warning_file/) |  |
| [warning_string](/viewer/python-net/groupdocs.viewer.logging/consolelogger/warning_string/) |  |

### Beispiel

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### Siehe auch
* module [`groupdocs.viewer.logging`](/viewer/python-net/groupdocs.viewer.logging/)
