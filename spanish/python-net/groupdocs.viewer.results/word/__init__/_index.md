---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de Word."
type: docs
url: /es/python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

Inicializa una nueva instancia de [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| word | `str` | La palabra. |
| x | `float` | La coordenada X del punto superior izquierdo en el diseño de página donde comienza el rectángulo que contiene la palabra. |
| y | `float` | La coordenada Y del punto superior izquierdo en el diseño de página donde comienza el rectángulo que contiene la palabra. |
| width | `float` | El ancho del rectángulo que contiene la palabra. |
| height | `float` | La altura del rectángulo que contiene la palabra. |
| characters | `List[Character]` | Los caracteres contenidos por la palabra. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `characters` es null. |

### Ver también
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
