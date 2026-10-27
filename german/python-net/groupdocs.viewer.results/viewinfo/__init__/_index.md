---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz von ViewInfo."
type: docs
url: /de/python-net/groupdocs.viewer.results/viewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages}

Initialisiert eine neue ViewInfo-Instanz.

```python
def __init__(self, file_type, pages):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_type | `FileType` | Der Typ der Datei. |
| pages | `List[Page]` | Die Liste der anzuzeigenden Seiten. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `pages` None ist. |

### Siehe auch
* class [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)
