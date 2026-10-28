---
title: "Método warning"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Escribe un mensaje de advertencia."
type: docs
url: /es/python-net/groupdocs.viewer.logging/ilogger/warning/
is_root: false
weight: 1070
---


## warning {#message}

Escribe un mensaje de advertencia.

Los mensajes de registro de advertencia proporcionan información sobre eventos inesperados y recuperables en el flujo de la aplicación.

```python
def warning(self, message):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| message | `str` | El mensaje de advertencia. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `message` es None. |

### Ver también
* class [`ILogger`](/viewer/python-net/groupdocs.viewer.logging/ilogger/)
