---
title: "error-metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Skriver ett felmeddelande."
type: docs
url: /sv/python-net/groupdocs.viewer.logging/ilogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Skriver ett felmeddelande.

Error-loggmeddelanden ger information om oåterkalleliga händelser i applikationsflödet.

```python
def error(self, message, exception):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| message | `str` | Error-meddelandet. |
| exception | `Exception` | Undantaget. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `exception` är None. |

### Se även
* class [`ILogger`](/viewer/python-net/groupdocs.viewer.logging/ilogger/)
