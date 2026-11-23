---
title: "Clase ConsoleLogger"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Escribe mensajes de registro en la consola."
type: docs
url: /es/python-net/groupdocs.viewer.logging/consolelogger/
is_root: false
weight: 10
---


## ConsoleLogger class

Escribe mensajes de registro en la consola.

El tipo ConsoleLogger expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.logging/consolelogger/__init__/) |  |

### Métodos
| Método | Descripción |
| :- | :- |
| [error](/viewer/python-net/groupdocs.viewer.logging/consolelogger/error/#message-exception) | Escribe un mensaje de error en la consola. |
| [error_file](/viewer/python-net/groupdocs.viewer.logging/consolelogger/error_file/) |  |
| [error_string](/viewer/python-net/groupdocs.viewer.logging/consolelogger/error_string/) |  |
| [trace](/viewer/python-net/groupdocs.viewer.logging/consolelogger/trace/#message) | Escribe un mensaje de rastreo en la consola. |
| [trace_file](/viewer/python-net/groupdocs.viewer.logging/consolelogger/trace_file/) |  |
| [trace_string](/viewer/python-net/groupdocs.viewer.logging/consolelogger/trace_string/) |  |
| [warning](/viewer/python-net/groupdocs.viewer.logging/consolelogger/warning/#message) | Escribe un mensaje de advertencia en la consola. |
| [warning_file](/viewer/python-net/groupdocs.viewer.logging/consolelogger/warning_file/) |  |
| [warning_string](/viewer/python-net/groupdocs.viewer.logging/consolelogger/warning_string/) |  |

### Ejemplo

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### Ver también
* module [`groupdocs.viewer.logging`](/viewer/python-net/groupdocs.viewer.logging/)
