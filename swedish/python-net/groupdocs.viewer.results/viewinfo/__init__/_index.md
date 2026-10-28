---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny instans av ViewInfo."
type: docs
url: /sv/python-net/groupdocs.viewer.results/viewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages}

Initierar en ny ViewInfo-instans.

```python
def __init__(self, file_type, pages):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_type | `FileType` | Filens typ. |
| pages | `List[Page]` | Listan över sidor att visa. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `pages` är None. |

### Se även
* class [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)
