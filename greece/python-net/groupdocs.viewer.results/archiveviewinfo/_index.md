---
title: "κλάση ArchiveViewInfo"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει πληροφορίες προβολής για ένα αρχείο αρχειοθήκης."
type: docs
url: /el/python-net/groupdocs.viewer.results/archiveviewinfo/
is_root: false
weight: 10
---


## ArchiveViewInfo class

Αντιπροσωπεύει πληροφορίες προβολής για ένα αρχείο αρχειοθήκης.

Ο τύπος ArchiveViewInfo εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/) | Αρχικοποιεί ένα νέο αντικείμενο του [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/#file_type-pages-folders) | Αρχικοποιεί ένα νέο αντικείμενο ArchiveViewInfo. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. (κληρονομείται από [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/folders/) | Οι φάκελοι που περιέχονται στο αρχείο αρχειοθήκης. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Ο τύπος του αρχείου. (κληρονομείται από [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Η λίστα των σελίδων προς προβολή. (κληρονομείται από [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Παράδειγμα

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ArchiveViewInfo

def get_archive_info():
    with Viewer("documents.zip") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        archive_info = cast(ArchiveViewInfo, info)

        print("File type:", archive_info.file_type)
        print("Pages count:", len(archive_info.pages))
        print("Folders:")
        for folder in archive_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_archive_info()
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `ArchiveViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Δείτε επίσης
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
