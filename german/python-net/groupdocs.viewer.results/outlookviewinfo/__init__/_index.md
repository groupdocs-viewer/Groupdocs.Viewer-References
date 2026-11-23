---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz von OutlookViewInfo."
type: docs
url: /de/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz von [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Initialisiert eine neue OutlookViewInfo-Instanz.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_type | `FileType` | Der Typ der Datei. |
| pages | `List[Page]` | Die Liste der anzuzeigenden Seiten. |
| folders | `List[str]` | Die Liste der Ordner, die in der Outlook-Datendatei enthalten sind. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `folders` None ist. |

### Siehe auch
* class [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/)
