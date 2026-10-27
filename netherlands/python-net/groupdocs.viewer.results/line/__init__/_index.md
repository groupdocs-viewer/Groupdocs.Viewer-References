---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van Line."
type: docs
url: /nl/python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

Initialiseert een nieuw exemplaar van de [`Line`](/viewer/python-net/groupdocs.viewer.results/line/) klasse.

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| line | `str` | De lijn. |
| x | `float` | De X-coördinaat van het hoogste linkerpunt op de paginalay-out waar de rechthoek die de lijn bevat begint. |
| y | `float` | De Y-coördinaat van het hoogste linkerpunt op de paginalay-out waar de rechthoek die de lijn bevat begint. |
| width | `float` | De breedte van de rechthoek die de lijn bevat (in pixels). |
| height | `float` | De hoogte van de rechthoek die de lijn bevat (in pixels). |
| words | `List[Word]` | De woorden die in de lijn voorkomen. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wordt opgegooid wanneer `line` null of leeg is, of wanneer `words` null is. |

### Zie ook
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
