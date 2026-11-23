---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz von Line."
type: docs
url: /de/python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz von [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

Initialisiert eine neue Instanz der [`Line`](/viewer/python-net/groupdocs.viewer.results/line/) Klasse.

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| line | `str` | Die Zeile. |
| x | `float` | Die X‑Koordinate des höchsten linken Punktes im Seitenlayout, an dem das Rechteck, das die line enthält, beginnt. |
| y | `float` | Die Y‑Koordinate des höchsten linken Punktes im Seitenlayout, an dem das Rechteck, das die line enthält, beginnt. |
| width | `float` | Die Breite des Rechtecks, das die line enthält (in Pixeln). |
| height | `float` | Die Höhe des Rechtecks, das die line enthält (in Pixeln). |
| words | `List[Word]` | Die von der Zeile enthaltenen Wörter. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `line` null oder leer ist, oder wenn `words` null ist. |

### Siehe auch
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
