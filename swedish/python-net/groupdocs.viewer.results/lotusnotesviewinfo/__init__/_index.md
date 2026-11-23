---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny instans av LotusNotesViewInfo."
type: docs
url: /sv/python-net/groupdocs.viewer.results/lotusnotesviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

Initierar en ny instans av [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/) klassen.

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_type | `FileType` | Filens typ. |
| pages | `List[Page]` | Listan över sidor att visa. |
| notes_count | `int` | Antalet anteckningar som finns i Lotus-databasens lagringsfil. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Utlöst när `notes_count` är None. |

### Se även
* class [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/)
