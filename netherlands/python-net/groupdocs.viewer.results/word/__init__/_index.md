---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van Word."
type: docs
url: /nl/python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

Initialiseert een nieuw exemplaar van [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| word | `str` | Het woord. |
| x | `float` | De X-coördinaat van het hoogste linkerpunt op de paginalay-out waar de rechthoek die het woord bevat begint. |
| y | `float` | De Y-coördinaat van het hoogste linkerpunt op de paginalay-out waar de rechthoek die het woord bevat begint. |
| width | `float` | De breedte van de rechthoek die het woord bevat. |
| height | `float` | De hoogte van de rechthoek die het woord bevat. |
| characters | `List[Character]` | De tekens die in het woord voorkomen. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `characters` null is. |

### Zie ook
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
