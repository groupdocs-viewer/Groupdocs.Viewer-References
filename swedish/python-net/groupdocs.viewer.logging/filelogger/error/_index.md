---
title: "error-metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Skriver ett felmeddelande till konsolen."
type: docs
url: /sv/python-net/groupdocs.viewer.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Skriver ett felmeddelande till konsolen. Felloggmeddelanden ger information om oåterställbara händelser i applikationsflödet.

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
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
