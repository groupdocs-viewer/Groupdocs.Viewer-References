---
title: "error-Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Schreibt eine Fehlermeldung."
type: docs
url: /de/python-net/groupdocs.viewer.logging/ilogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Schreibt eine Fehlermeldung.

Fehlerprotokollnachrichten liefern Informationen über nicht wiederherstellbare Ereignisse im Anwendungsablauf.

```python
def error(self, message, exception):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| message | `str` | Die Fehlermeldung. |
| exception | `Exception` | Die Ausnahme. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `exception` None ist. |

### Siehe auch
* class [`ILogger`](/viewer/python-net/groupdocs.viewer.logging/ilogger/)
