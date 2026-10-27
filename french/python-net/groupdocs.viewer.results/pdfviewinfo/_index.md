---
title: "Classe PdfViewInfo"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente les informations de vue pour un document PDF."
type: docs
url: /fr/python-net/groupdocs.viewer.results/pdfviewinfo/
is_root: false
weight: 140
---


## PdfViewInfo class

Représente les informations de vue pour un document PDF.

Le type PdfViewInfo expose les membres suivants:

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/) | Initialise une nouvelle instance de PdfViewInfo. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/#file_type-pages-printing_allowed) | Initialise une nouvelle instance de PdfViewInfo. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Renvoie une chaîne qui représente l'objet actuel. (hérité de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Propriétés
| Propriété | Description |
| :- | :- |
| [printing_allowed](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/printing_allowed/) | La propriété printing_allowed indique si l'impression du document est autorisée. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Le type du fichier. (hérité de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | La liste des pages à afficher. (hérité de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Exemple

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
Guides de tâches qui utilisent `PdfViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Voir aussi
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
