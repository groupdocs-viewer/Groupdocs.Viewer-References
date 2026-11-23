---
title: "Classe PdfViewInfo"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta le informazioni di visualizzazione per un documento PDF."
type: docs
url: /it/python-net/groupdocs.viewer.results/pdfviewinfo/
is_root: false
weight: 140
---


## PdfViewInfo class

Rappresenta le informazioni di visualizzazione per un documento PDF.

Il tipo PdfViewInfo espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/) | Inizializza una nuova istanza di PdfViewInfo. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/#file_type-pages-printing_allowed) | Inizializza una nuova istanza di PdfViewInfo. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Restituisce una stringa che rappresenta l'oggetto corrente. (eredita da [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [printing_allowed](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/printing_allowed/) | La proprietà printing_allowed indica se la stampa del documento è consentita. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Il tipo del file. (eredita da [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | L'elenco delle pagine da visualizzare. (eredita da [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Esempio

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
Guide operative che utilizzano `PdfViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Vedi anche
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
