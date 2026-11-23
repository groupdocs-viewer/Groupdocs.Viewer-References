---
title: "PdfViewInfo-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar vyinformation för ett PDF-dokument."
type: docs
url: /sv/python-net/groupdocs.viewer.results/pdfviewinfo/
is_root: false
weight: 140
---


## PdfViewInfo class

Representerar vyinformation för ett PDF-dokument.

PdfViewInfo-typen visar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/) | Initierar en ny PdfViewInfo-instans. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/#file_type-pages-printing_allowed) | Initierar en ny PdfViewInfo-instans. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Returnerar en sträng som representerar det aktuella objektet. (ärvd från [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [printing_allowed](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/printing_allowed/) | Egenskapen printing_allowed indikerar om utskrift av dokumentet är tillåten. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Filens typ. (ärvd från [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Listan över sidor att visa. (ärvd från [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Exempel

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
Uppgiftsguider som använder `PdfViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Se även
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
