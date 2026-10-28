---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny Resource-instans."
type: docs
url: /sv/python-net/groupdocs.viewer.results/resource/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny Resource-instans.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-nested}

Initierar en ny Resource-instans.

```python
def __init__(self, file_name, nested):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_name | `str` | Resursfilnamn. |
| nested | `bool` | Anger om resursen finns inuti en annan resurs, t.ex. teckensnittresurs som finns i CSS- eller SVG-resurs. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Utlöst när `file_name` är None eller tom. |

### Se även
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)
