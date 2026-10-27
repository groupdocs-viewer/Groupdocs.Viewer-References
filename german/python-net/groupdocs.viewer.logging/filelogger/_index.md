---
title: "FileLogger Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Schreibt Protokollnachrichten in die Datei."
type: docs
url: /de/python-net/groupdocs.viewer.logging/filelogger/
is_root: false
weight: 20
---


## FileLogger class

Schreibt Protokollnachrichten in die Datei.

Der FileLogger-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.logging/filelogger/__init__/#file_name) | Initialisiert einen Logger, der Nachrichten in eine Datei schreibt. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [error](/viewer/python-net/groupdocs.viewer.logging/filelogger/error/#message-exception) | Schreibt eine Fehlermeldung in die Konsole. Fehlermeldungen im Protokoll liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf. |
| [error_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_file/) |  |
| [error_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_string/) |  |
| [trace](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace/#message) | Schreibt eine Trace-Nachricht in das Protokoll. Trace-Protokollnachrichten liefern allgemein nützliche Informationen über den Anwendungsablauf. |
| [trace_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_file/) |  |
| [trace_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_string/) |  |
| [warning](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning/#message) | Schreibt eine Warnmeldung in die Konsole. |
| [warning_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_file/) |  |
| [warning_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_string/) |  |

### Beispiel

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

### Siehe auch
* module [`groupdocs.viewer.logging`](/viewer/python-net/groupdocs.viewer.logging/)
