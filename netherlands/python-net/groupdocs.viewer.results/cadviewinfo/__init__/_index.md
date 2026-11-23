---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een nieuw CadViewInfo-exemplaar."
type: docs
url: /nl/python-net/groupdocs.viewer.results/cadviewinfo/__init__/
is_root: false
weight: 10
---


## __init__ {#file_type-pages-layers-layouts}

Initialiseert een nieuw CadViewInfo-exemplaar.

```python
def __init__(self, file_type, pages, layers, layouts):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_type | `FileType` | Het type van het bestand. |
| pages | `List[Page]` | De lijst met pagina's om te bekijken. |
| layers | `List[Layer]` | De lijst met lagen die de CAD-tekening bevat. |
| layouts | `List[Layout]` | De lijst met lagen die de CAD-tekening bevat. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wordt opgegooid wanneer `layouts` None is. |

### Zie ook
* class [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)
