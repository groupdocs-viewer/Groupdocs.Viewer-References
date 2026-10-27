---
title: "Κλάση PdfViewInfo"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά πληροφορίες προβολής για ένα έγγραφο PDF."
type: docs
url: /el/python-net/groupdocs.viewer.results/pdfviewinfo/
is_root: false
weight: 140
---


## PdfViewInfo class

Αναπαριστά πληροφορίες προβολής για ένα έγγραφο PDF.

Ο τύπος PdfViewInfo εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/) | Αρχικοποιεί ένα νέο στιγμιότυπο του PdfViewInfo. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/#file_type-pages-printing_allowed) | Αρχικοποιεί ένα νέο στιγμιότυπο του PdfViewInfo. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. (κληρονομείται από [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [printing_allowed](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/printing_allowed/) | Η ιδιότητα printing_allowed υποδεικνύει εάν επιτρέπεται η εκτύπωση του εγγράφου. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Ο τύπος του αρχείου. (κληρονομείται από [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Η λίστα των σελίδων προς προβολή. (κληρονομείται από [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Παράδειγμα

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
Οδηγοί εργασιών που χρησιμοποιούν `PdfViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Δείτε επίσης
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
