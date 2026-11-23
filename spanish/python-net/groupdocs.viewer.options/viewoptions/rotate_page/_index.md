---
title: "método rotate_page"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Aplica la rotación en sentido horario a una página."
type: docs
url: /es/python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

Aplica la rotación en sentido horario a una página.

Para obtener más detalles, consulte la documentación en https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/.

```python
def rotate_page(self, page_number, rotation):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_number | `int` | El número de página debe ser estrictamente mayor que 0. |
| rotation | `Rotation` | El valor de rotación. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si la rotación para la página con número `page_number` ya fue añadida. |

### Ver también
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
