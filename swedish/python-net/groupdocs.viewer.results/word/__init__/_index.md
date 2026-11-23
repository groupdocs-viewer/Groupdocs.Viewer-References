---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny instans av Word."
type: docs
url: /sv/python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

Initierar en ny instans av [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| word | `str` | Ordet. |
| x | `float` | X‑koordinaten för den högsta vänstra punkten i sidlayouten där rektangeln som innehåller ordet börjar. |
| y | `float` | Y‑koordinaten för den högsta vänstra punkten i sidlayouten där rektangeln som innehåller ordet börjar. |
| width | `float` | Bredden på rektangeln som innehåller ordet. |
| height | `float` | Höjden på rektangeln som innehåller ordet. |
| characters | `List[Character]` | Tecknen som ordet innehåller. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `characters` är null. |

### Se även
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
