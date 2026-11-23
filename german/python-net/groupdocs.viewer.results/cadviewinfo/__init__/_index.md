---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue CadViewInfo-Instanz."
type: docs
url: /de/python-net/groupdocs.viewer.results/cadviewinfo/__init__/
is_root: false
weight: 10
---


## __init__ {#file_type-pages-layers-layouts}

Initialisiert eine neue CadViewInfo-Instanz.

```python
def __init__(self, file_type, pages, layers, layouts):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_type | `FileType` | Der Typ der Datei. |
| pages | `List[Page]` | Die Liste der anzuzeigenden Seiten. |
| layers | `List[Layer]` | Die Liste der im CAD-Zeichnung enthaltenen Ebenen. |
| layouts | `List[Layout]` | Die Liste der im CAD-Zeichnung enthaltenen Ebenen. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `layouts` None ist. |

### Siehe auch
* class [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)
