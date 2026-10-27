---
title: "Κλάση CadViewInfo"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει πληροφορίες προβολής για σχέδιο CAD."
type: docs
url: /el/python-net/groupdocs.viewer.results/cadviewinfo/
is_root: false
weight: 30
---


## CadViewInfo class

Αντιπροσωπεύει πληροφορίες προβολής για σχέδιο CAD.

Ο τύπος CadViewInfo εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/__init__/#file_type-pages-layers-layouts) | Αρχικοποιεί ένα νέο στιγμιότυπο του CadViewInfo. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. (κληρονομείται από [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [layers](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layers/) | Η λίστα των στρώσεων που περιέχονται στο σχέδιο CAD. |
| [layouts](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layouts/) | Η λίστα των διατάξεων που περιέχονται στο σχέδιο CAD. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Ο τύπος του αρχείου. (κληρονομείται από [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Η λίστα των σελίδων προς προβολή. (κληρονομείται από [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Παράδειγμα

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import CadViewInfo

def get_cad_info():
    with Viewer("sample.dwg") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        cad_info = cast(CadViewInfo, info)

        print("File type:", cad_info.file_type)
        print("Pages count:", len(cad_info.pages))
        print("Layers:")
        for layer in cad_info.layers:
            print(f"  {layer.name} (visible={layer.visible})")
        print("Layouts:")
        for layout in cad_info.layouts:
            print(f"  {layout.name} ({layout.width}x{layout.height})")

if __name__ == "__main__":
    get_cad_info()
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `CadViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Δείτε επίσης
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
