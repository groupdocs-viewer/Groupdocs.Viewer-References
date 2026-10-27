---
title: "error methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Schrijft een foutmelding."
type: docs
url: /nl/python-net/groupdocs.viewer.logging/ilogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Schrijft een foutmelding.

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
| `ValueError` | Wanneer `exception` None is. |

### Zie ook
* class [`ILogger`](/viewer/python-net/groupdocs.viewer.logging/ilogger/)
