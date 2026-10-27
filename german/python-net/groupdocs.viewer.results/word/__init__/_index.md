---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz von Word."
type: docs
url: /de/python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz von [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

Initialisiert eine neue Instanz von [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| word | `str` | Das Wort. |
| x | `float` | Die X‑Koordinate des höchsten linken Punkts im Seitenlayout, an dem das Rechteck, das das Wort enthält, beginnt. |
| y | `float` | Die Y‑Koordinate des höchsten linken Punkts im Seitenlayout, an dem das Rechteck, das das Wort enthält, beginnt. |
| width | `float` | Die Breite des Rechtecks, das das Wort enthält. |
| height | `float` | Die Höhe des Rechtecks, das das Wort enthält. |
| characters | `List[Character]` | Die vom Wort enthaltenen Zeichen. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `characters` null ist. |

### Siehe auch
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
