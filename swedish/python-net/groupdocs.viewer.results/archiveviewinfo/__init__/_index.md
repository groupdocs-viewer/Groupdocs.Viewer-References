---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny instans av ArchiveViewInfo."
type: docs
url: /sv/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Initierar en ny ArchiveViewInfo-instans.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_type | `FileType` | Filens typ. |
| pages | `List[Page]` | Listan över sidor att visa. |
| folders | `List[str]` | Listan över mappar som finns i arkivfilen. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `folders` är None. |

### Se även
* class [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)
