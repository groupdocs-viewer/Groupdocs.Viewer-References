---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine Instanz der FileName‑Klasse."
type: docs
url: /de/python-net/groupdocs.viewer.options/filename/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

Initialisiert eine Instanz der Klasse [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/).

```python
def __init__(self, file_name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_name | `str` | Der Name der Datei. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `file_name` None ist. |

### Beispiel

```python
from groupdocs.viewer.options import FileName

# Erstelle eine FileName‑Instanz mit einem benutzerdefinierten Archivnamen
custom_name = FileName("Sample Files")
```

### Siehe auch
* class [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/)
