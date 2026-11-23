---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en instans av FileName-klassen."
type: docs
url: /sv/python-net/groupdocs.viewer.options/filename/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

Initierar en instans av [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) klass.

```python
def __init__(self, file_name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_name | `str` | Filens namn. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `file_name` är None. |

### Exempel

```python
from groupdocs.viewer.options import FileName

# Skapa en FileName-instans med ett anpassat arkivnamn
custom_name = FileName("Sample Files")
```

### Se även
* class [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/)
