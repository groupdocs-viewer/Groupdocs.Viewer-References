---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van ArchiveViewInfo."
type: docs
url: /nl/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Initialiseert een nieuw ArchiveViewInfo-exemplaar.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_type | `FileType` | Het type van het bestand. |
| pages | `List[Page]` | De lijst met pagina's om te bekijken. |
| folders | `List[str]` | De lijst met mappen die in het archiefbestand zijn opgenomen. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `folders` None is. |

### Zie ook
* class [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)
