---
title: "try_parse-Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Versucht, die angegebene Rohzeichenkette als Schriftstilnamen zu parsen."
type: docs
url: /de/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/
is_root: false
weight: 1060
---


## try_parse {#style-parsed}

Versucht, die angegebene Rohzeichenkette als Schriftstilnamen zu parsen.

```python
def try_parse(cls, style, parsed):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| style | `str` | Zeichenkette, die als Schriftstil geparst werden soll. |
| parsed | `FontStyles` | Geparster Schriftstil bei Erfolg oder `FontStyles.Regular` bei Fehlschlag. |

**Returns:** bool: True if string was successfully parsed as a correct font style; False otherwise.

### Siehe auch
* class [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/)
