---
title: "Método error"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Escribe un mensaje de error en la consola."
type: docs
url: /es/python-net/groupdocs.viewer.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Escribe un mensaje de error en la consola. Los mensajes de registro de error proporcionan información sobre eventos irrecuperables en el flujo de la aplicación.

```python
def error(self, message, exception):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| message | `str` | El mensaje de error. |
| exception | `Exception` | La excepción. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `exception` es None. |

### Ver también
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
