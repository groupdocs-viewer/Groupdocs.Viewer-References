---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de Line."
type: docs
url: /es/python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

Inicializa una nueva instancia de la clase [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| line | `str` | La línea. |
| x | `float` | La coordenada X del punto superior izquierdo en el diseño de página donde comienza el rectángulo que contiene la línea. |
| y | `float` | La coordenada Y del punto superior izquierdo en el diseño de página donde comienza el rectángulo que contiene la línea. |
| width | `float` | El ancho del rectángulo que contiene la línea (en píxeles). |
| height | `float` | La altura del rectángulo que contiene la línea (en píxeles). |
| words | `List[Word]` | Las palabras contenidas por la línea. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Se genera cuando `line` es null o está vacío, o cuando `words` es null. |

### Ver también
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
