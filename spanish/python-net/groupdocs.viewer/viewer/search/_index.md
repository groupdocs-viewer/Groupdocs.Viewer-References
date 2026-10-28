---
title: "método de búsqueda"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Realiza una búsqueda de texto y resalta el texto encontrado en el documento cargado según las opciones proporcionadas."
type: docs
url: /es/python-net/groupdocs.viewer/viewer/search/
is_root: false
weight: 1110
---


## search {#options}

Realiza una búsqueda de texto y resalta el texto encontrado en el documento cargado según las opciones proporcionadas.

```python
def search(self, options):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | `SearchHighlightOptions` | Opciones de búsqueda y resaltado, incluida la frase de texto a buscar. No debe ser None. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `options` es None. |

### Ver también
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
