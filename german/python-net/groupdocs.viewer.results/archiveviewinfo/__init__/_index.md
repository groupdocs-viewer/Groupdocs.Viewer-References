---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz von ArchiveViewInfo."
type: docs
url: /de/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz von [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Initialisiert eine neue ArchiveViewInfo‑Instanz.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_type | `FileType` | Der Typ der Datei. |
| pages | `List[Page]` | Die Liste der anzuzeigenden Seiten. |
| folders | `List[str]` | Die Liste der im Archivdatei enthaltenen Ordner. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `folders` None ist. |

### Siehe auch
* class [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)
