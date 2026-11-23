---
title: "metodo rotate_page"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Applica la rotazione in senso orario a una pagina."
type: docs
url: /it/python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

Applica la rotazione in senso orario a una pagina.

Per ulteriori dettagli, vedere la documentazione su https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/.

```python
def rotate_page(self, page_number, rotation):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_number | `int` | Il numero di pagina deve essere strettamente maggiore di 0. |
| rotation | `Rotation` | Il valore di rotazione. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se la rotazione per la pagina con numero `page_number` è già stata aggiunta. |

### Vedi anche
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
