---
title: "Metodo error"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Scrive un messaggio di errore sulla console."
type: docs
url: /it/python-net/groupdocs.viewer.logging/consolelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Scrive un messaggio di errore sulla console.

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
| `ValueError` | Generato quando `exception` è None. |

### Vedi anche
* class [`ConsoleLogger`](/viewer/python-net/groupdocs.viewer.logging/consolelogger/)
