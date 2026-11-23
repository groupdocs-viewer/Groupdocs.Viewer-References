---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een nieuw Resource‑exemplaar."
type: docs
url: /nl/python-net/groupdocs.viewer.results/resource/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw Resource‑exemplaar.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-nested}

Initialiseert een nieuw Resource‑exemplaar.

```python
def __init__(self, file_name, nested):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_name | `str` | Naam van resourcebestand. |
| nested | `bool` | Geeft aan of de resource zich binnen een andere resource bevindt, bijv. fontresource die zich in een CSS- of SVG-resource bevindt. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wordt opgegooid wanneer `file_name` None of leeg is. |

### Zie ook
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)
