---
title: "Κλάση CadOptions"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Οι επιλογές για απόδοση σχεδίων CAD."
type: docs
url: /el/python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

Οι επιλογές για απόδοση σχεδίων CAD.

Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε την τεκμηρίωση Render CAD drawings and models as HTML, PDF, and image files και Specify rendering options for CAD files.

Ο τύπος CadOptions εκθέτει τα ακόλουθα μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | Αρχικοποιεί ένα αντικείμενο CadOptions για απόδοση με βάση το ύψος. |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | Αρχικοποιεί ένα αντικείμενο CadOptions για απόδοση με βάση τον συντελεστή κλίμακας. |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | Αρχικοποιεί ένα αντικείμενο της κλάσης [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) για απόδοση με βάση το πλάτος. |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | Αρχικοποιεί ένα αντικείμενο της κλάσης CadOptions για απόδοση με βάση το πλάτος και το ύψος. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | Το χρώμα φόντου της εικόνας. |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | Η σημαία που ενεργοποιεί μια λειτουργία μετατροπής προσανατολισμένη στην απόδοση για όλες τις μορφές CAD, όπου ο ορισμός της σε True επιταχύνει τη μετατροπή με κόστος μειωμένης ποιότητας εξόδου· η προεπιλογή είναι False για μέγιστη ποιότητα. |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | Το ύψος του αποτελέσματος εξόδου (σε εικονοστοιχεία). |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | Τα στρώματα σχεδίου CAD που θα αποδοθούν. |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | Το όνομα της συγκεκριμένης διάταξης για απόδοση. Το όνομα διάταξης είναι ευαίσθητο σε πεζά/κεφαλαία. |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | Το αρχείο ρυθμίσεων του εκτυπωτή PC3. |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | Η σημαία που υποδεικνύει εάν οι διατάξεις από το έγγραφο CAD πρέπει να αποδοθούν. |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | Ο συντελεστής κλίμακας. Τιμή μεγαλύτερη από 1 μεγεθύνει το αποτέλεσμα εξόδου· τιμή μεταξύ 0 και 1 μειώνει το αποτέλεσμα εξόδου. |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | Οι περιοχές σχεδίου που θα αποδοθούν. |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | Το πλάτος του αποτελέσματος εξόδου (σε εικονοστοιχεία). |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # Φόρτωση αρχείου CAD
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        # Απόδοση με πλάτος και ενεργοποίηση λειτουργίας απόδοσης
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### Δείτε επίσης
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
