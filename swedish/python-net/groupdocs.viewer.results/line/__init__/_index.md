---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny instans av Line."
type: docs
url: /sv/python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

Initierar en ny instans av klassen [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| line | `str` | Raden. |
| x | `float` | X-koordinaten för den högsta vänstra punkten i sidlayouten där rektangeln som innehåller raden börjar. |
| y | `float` | Y-koordinaten för den högsta vänstra punkten i sidlayouten där rektangeln som innehåller raden börjar. |
| width | `float` | Bredden på rektangeln som innehåller raden (i pixlar). |
| height | `float` | Höjden på rektangeln som innehåller raden (i pixlar). |
| words | `List[Word]` | Orden som finns i raden. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Kastas när `line` är null eller tom, eller när `words` är null. |

### Se även
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
