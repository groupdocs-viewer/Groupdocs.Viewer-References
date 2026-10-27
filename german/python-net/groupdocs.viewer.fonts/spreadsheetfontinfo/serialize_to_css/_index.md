---
title: "serialize_to_css Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Serialisiert die Schriftinformationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Textwriter."
type: docs
url: /de/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/
is_root: false
weight: 1010
---


## serialize_to_css {#output}

Serialisiert die Schriftinformationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Textwriter.

```python
def serialize_to_css(self, output):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| output | `System.IO.TextWriter` | Ein dateiähnliches Objekt (z. B. ein `io.TextIOBase`), in das die serialisierten Textdaten geschrieben werden sollen. |

**Returns:** None.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `output` None ist. |

### Siehe auch
* class [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/)
