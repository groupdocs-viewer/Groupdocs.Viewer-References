---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een instantie van de FileName‑klasse."
type: docs
url: /nl/python-net/groupdocs.viewer.options/filename/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

Initialiseert een instantie van de [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/) klasse.

```python
def __init__(self, file_name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_name | `str` | De naam van het bestand. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `file_name` None is. |

### Voorbeeld

```python
from groupdocs.viewer.options import FileName

# Maak een FileName‑instantie met een aangepaste archiefnaam
custom_name = FileName("Sample Files")
```

### Zie ook
* class [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/)
