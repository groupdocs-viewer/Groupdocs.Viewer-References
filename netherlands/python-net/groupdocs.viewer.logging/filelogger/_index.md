---
title: "FileLogger klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Schrijft logberichten naar het bestand."
type: docs
url: /nl/python-net/groupdocs.viewer.logging/filelogger/
is_root: false
weight: 20
---


## FileLogger class

Schrijft logberichten naar het bestand.

Het FileLogger-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.logging/filelogger/__init__/#file_name) | Initialiseert een logger die berichten naar een bestand schrijft. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [error](/viewer/python-net/groupdocs.viewer.logging/filelogger/error/#message-exception) | Schrijft een foutmelding naar de console. Foutlogberichten geven informatie over onherstelbare gebeurtenissen in de applicatiestroom. |
| [error_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_file/) |  |
| [error_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_string/) |  |
| [trace](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace/#message) | Schrijft een trace-bericht naar het logboek. Trace-logberichten bieden over het algemeen nuttige informatie over de applicatiestroom. |
| [trace_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_file/) |  |
| [trace_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_string/) |  |
| [warning](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning/#message) | Schrijft een waarschuwingsbericht naar de console. |
| [warning_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_file/) |  |
| [warning_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_string/) |  |

### Voorbeeld

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

### Zie ook
* module [`groupdocs.viewer.logging`](/viewer/python-net/groupdocs.viewer.logging/)
