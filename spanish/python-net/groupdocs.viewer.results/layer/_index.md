---
title: "Clase Layer"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa una capa contenida en el dibujo CAD."
type: docs
url: /es/python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

Representa una capa contenida en el dibujo CAD.

El tipo Layer expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | Inicializa una nueva instancia de la clase [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | Inicializa una nueva instancia de Layer. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | Inicializa una nueva instancia de Layer. |

### Métodos
| Método | Descripción |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | Determina si el Layer actual es el mismo que el objeto Layer especificado. |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | Comprueba si el [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) actual es igual al objeto especificado. |
| [equals_layer](/viewer/python-net/groupdocs.viewer.results/layer/equals_layer/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.results/layer/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | Devuelve el código hash del objeto Layer actual. |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | Devuelve una cadena que representa el objeto actual. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | El nombre de la capa. |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | El indicador de visibilidad de la capa. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("output.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Ver también
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
