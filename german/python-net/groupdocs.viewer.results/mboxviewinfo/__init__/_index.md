---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz von MboxViewInfo."
type: docs
url: /de/python-net/groupdocs.viewer.results/mboxviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz von [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

Initialisiert eine neue [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/) Instanz.

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_type | `FileType` | Der Typ der Datei. |
| pages | `List[Page]` | Die Liste der anzuzeigenden Seiten. |
| notes_count | `int` | Die Anzahl der Notizen, die in der Lotus-Datenbankdatei enthalten ist. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `notes_count` None ist. |

### Siehe auch
* class [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/)
