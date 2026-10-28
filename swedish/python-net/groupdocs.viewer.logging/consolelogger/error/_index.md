---
title: "error-metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Skriver ett felmeddelande till konsolen."
type: docs
url: /sv/python-net/groupdocs.viewer.logging/consolelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Skriver ett felmeddelande till konsolen.

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
| `ValueError` | Kastas när `exception` är None. |

### Se även
* class [`ConsoleLogger`](/viewer/python-net/groupdocs.viewer.logging/consolelogger/)
