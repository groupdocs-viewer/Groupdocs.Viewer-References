---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van MboxViewInfo."
type: docs
url: /nl/python-net/groupdocs.viewer.results/mboxviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

Initialiseert een nieuw [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/) exemplaar.

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_type | `FileType` | Het type van het bestand. |
| pages | `List[Page]` | De lijst met pagina's om te bekijken. |
| notes_count | `int` | Het aantal notities dat in het Lotus-databaseopslagbestand zit. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `notes_count` None is. |

### Zie ook
* class [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/)
