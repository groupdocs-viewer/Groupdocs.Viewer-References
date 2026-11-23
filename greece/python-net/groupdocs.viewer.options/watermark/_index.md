---
title: "Κλάση Watermark"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει ένα υδατογράφημα κειμένου."
type: docs
url: /el/python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

Αντιπροσωπεύει ένα υδατογράφημα κειμένου.

Δείτε την online τεκμηρίωση για περισσότερες πληροφορίες.

Ο τύπος Watermark εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | Αρχικοποιεί ένα στιγμιότυπο της κλάσης [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/). |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | Το χρώμα του υδατογραφήματος. Η προεπιλεγμένη τιμή είναι `Rgb24Color.known_colors.css_level1.red`. |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | Το όνομα γραμματοσειράς που χρησιμοποιείται για το υδατογράφημα. |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | Η θέση του υδατογραφήματος. Η προεπιλεγμένη τιμή είναι `Position.diagonal`. |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | Το μέγεθος του υδατογραφήματος. Η προεπιλεγμένη τιμή είναι [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/). |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | Το κείμενο του υδατογραφήματος. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # Φόρτωση εγγράφου
    with Viewer("sample.docx") as viewer:
        # Δημιουργία αρχείου HTML.
        viewOptions = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark.html"
        )
        # Προσθήκη υδατογραφήματος.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `Watermark`:

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### Δείτε επίσης
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
