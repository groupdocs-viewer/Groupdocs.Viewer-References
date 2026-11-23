---
title: "Κλάση VisioRenderingOptions"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει επιλογές για την απόδοση εγγράφων Visio."
type: docs
url: /el/python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

Αντιπροσωπεύει επιλογές για την απόδοση εγγράφων Visio.

Για λεπτομέρειες, δείτε την τεκμηρίωση.

Ο τύπος VisioRenderingOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | Αρχικοποιεί μια παρουσία της κλάσης [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/). |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | Το πλάτος του σχήματος· το ύψος υπολογίζεται αυτόματα. Η προεπιλεγμένη τιμή είναι 100. |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | Η ιδιότητα αποδίδει μόνο σχήματα Visio, όχι ένα διάγραμμα. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # Φόρτωση εγγράφου Visio
    with Viewer("map.vsdx") as viewer:
        # Μετατροπή του αρχείου Visio σε PDF.
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # Απόδοση μόνο των κύριων σχημάτων.
        view_options.visio_rendering_options.render_figures_only = True
        # Καθορίστε το πλάτος του σχήματος σε εικονοστοιχεία.
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### Δείτε επίσης
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
