---
title: "PdfViewInfo Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt Ansichtsinformationen für ein PDF-Dokument dar."
type: docs
url: /de/python-net/groupdocs.viewer.results/pdfviewinfo/
is_root: false
weight: 140
---


## PdfViewInfo class

Stellt Ansichtsinformationen für ein PDF-Dokument dar.

Der PdfViewInfo-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/) | Initialisiert eine neue PdfViewInfo-Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/#file_type-pages-printing_allowed) | Initialisiert eine neue PdfViewInfo-Instanz. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. (geerbt von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [printing_allowed](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/printing_allowed/) | Die Eigenschaft printing_allowed gibt an, ob das Drucken des Dokuments erlaubt ist. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Der Typ der Datei. (geerbt von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Die Liste der anzuzeigenden Seiten. (geerbt von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Beispiel

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
Aufgabenleitfäden, die `PdfViewInfo` verwenden:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Siehe auch
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
