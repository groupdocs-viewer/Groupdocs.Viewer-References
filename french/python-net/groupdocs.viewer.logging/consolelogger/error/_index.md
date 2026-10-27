---
title: "méthode error"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Écrit un message d’erreur dans la console."
type: docs
url: /fr/python-net/groupdocs.viewer.logging/consolelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Écrit un message d’erreur dans la console.

Les messages de journalisation d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application.

```python
def error(self, message, exception):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| message | `str` | Le message d'erreur. |
| exception | `Exception` | L'exception. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lancée lorsque `exception` est None. |

### Voir aussi
* class [`ConsoleLogger`](/viewer/python-net/groupdocs.viewer.logging/consolelogger/)
