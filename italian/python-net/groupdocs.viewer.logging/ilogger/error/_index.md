---
title: "Metodo error"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Scrive un messaggio di errore."
type: docs
url: /it/python-net/groupdocs.viewer.logging/ilogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Scrive un messaggio di errore.

I messaggi di log di errore forniscono informazioni sugli eventi irrecuperabili nel flusso dell'applicazione.

```python
def error(self, message, exception):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| message | `str` | Il messaggio di errore. |
| exception | `Exception` | L'eccezione. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `exception` è None. |

### Vedi anche
* class [`ILogger`](/viewer/python-net/groupdocs.viewer.logging/ilogger/)
