---
title: "Clase PdfViewInfo"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa información de vista para un documento PDF."
type: docs
url: /es/python-net/groupdocs.viewer.results/pdfviewinfo/
is_root: false
weight: 140
---


## PdfViewInfo class

Representa información de vista para un documento PDF.

El tipo PdfViewInfo expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/) | Inicializa una nueva instancia de PdfViewInfo. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/#file_type-pages-printing_allowed) | Inicializa una nueva instancia de PdfViewInfo. |

### Métodos
| Método | Descripción |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Devuelve una cadena que representa el objeto actual. (heredado de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [printing_allowed](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/printing_allowed/) | La propiedad printing_allowed indica si se permite imprimir el documento. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | El tipo del archivo. (heredado de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | La lista de páginas a visualizar. (heredado de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Ejemplo

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import PdfViewInfo

def get_pdf_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        pdf_info = cast(PdfViewInfo, info)

        print("File type:", pdf_info.file_type)
        print("Pages count:", len(pdf_info.pages))
        print("Printing allowed:", pdf_info.printing_allowed)

if __name__ == "__main__":
    get_pdf_info()
```

### Guides
Guías de tareas que usan `PdfViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Ver también
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
