---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny CadViewInfo-instans."
type: docs
url: /sv/python-net/groupdocs.viewer.results/cadviewinfo/__init__/
is_root: false
weight: 10
---


## __init__ {#file_type-pages-layers-layouts}

Initierar en ny CadViewInfo-instans.

```python
def __init__(self, file_type, pages, layers, layouts):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_type | `FileType` | Filens typ. |
| pages | `List[Page]` | Listan över sidor att visa. |
| layers | `List[Layer]` | Listan över lager som ingår i CAD-ritningen. |
| layouts | `List[Layout]` | Listan över lager som ingår i CAD-ritningen. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Kastas när `layouts` är None. |

### Se även
* class [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)
