---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Resource-Instanz."
type: docs
url: /de/python-net/groupdocs.viewer.results/resource/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Resource-Instanz.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-nested}

Initialisiert eine neue Resource-Instanz.

```python
def __init__(self, file_name, nested):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_name | `str` | Ressourcendateiname. |
| nested | `bool` | Gibt an, ob die Ressource innerhalb einer anderen Ressource liegt, z. B. Schriftressource, die in einer CSS- oder SVG-Ressource enthalten ist. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `file_name` None oder leer ist. |

### Siehe auch
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)
