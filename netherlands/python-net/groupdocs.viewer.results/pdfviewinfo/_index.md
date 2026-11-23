---
title: "PdfViewInfo klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt weergave-informatie voor een PDF-document voor."
type: docs
url: /nl/python-net/groupdocs.viewer.results/pdfviewinfo/
is_root: false
weight: 140
---


## PdfViewInfo class

Stelt weergave-informatie voor een PDF-document voor.

Het PdfViewInfo-type exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/) | Initialiseert een nieuw PdfViewInfo-exemplaar. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/#file_type-pages-printing_allowed) | Initialiseert een nieuw PdfViewInfo-exemplaar. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Retourneert een string die het huidige object vertegenwoordigt. (geërfd van [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [printing_allowed](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/printing_allowed/) | De property printing_allowed geeft aan of afdrukken van het document is toegestaan. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Het type van het bestand. (geërfd van [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | De lijst met pagina's om te bekijken. (geërfd van [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Voorbeeld

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
Taakgidsen die `PdfViewInfo` gebruiken:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Zie ook
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
