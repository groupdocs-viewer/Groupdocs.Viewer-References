---
title: "error methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Schrijft een foutmelding naar de console."
type: docs
url: /nl/python-net/groupdocs.viewer.logging/consolelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Schrijft een foutmelding naar de console.

Error-logberichten bieden informatie over onherstelbare gebeurtenissen in de applicatiestroom.

```python
def error(self, message, exception):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| message | `str` | Het foutbericht. |
| exception | `Exception` | De uitzondering. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wordt opgegooid wanneer `exception` None is. |

### Zie ook
* class [`ConsoleLogger`](/viewer/python-net/groupdocs.viewer.logging/consolelogger/)
