---
title: "classe FileLogger"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Scrive i messaggi di log sul file."
type: docs
url: /it/python-net/groupdocs.viewer.logging/filelogger/
is_root: false
weight: 20
---


## FileLogger class

Scrive i messaggi di log sul file.

Il tipo FileLogger espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.logging/filelogger/__init__/#file_name) | Inizializza un logger che scrive i messaggi su un file. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [error](/viewer/python-net/groupdocs.viewer.logging/filelogger/error/#message-exception) | Scrive un messaggio di errore sulla console. I messaggi di log di errore forniscono informazioni sugli eventi irrecuperabili nel flusso dell'applicazione. |
| [error_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_file/) |  |
| [error_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_string/) |  |
| [trace](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace/#message) | Scrive un messaggio di traccia nel log. I messaggi di log di traccia forniscono informazioni generalmente utili sul flusso dell'applicazione. |
| [trace_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_file/) |  |
| [trace_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_string/) |  |
| [warning](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning/#message) | Scrive un messaggio di avviso sulla console. |
| [warning_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_file/) |  |
| [warning_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_string/) |  |

### Esempio

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

### Vedi anche
* module [`groupdocs.viewer.logging`](/viewer/python-net/groupdocs.viewer.logging/)
