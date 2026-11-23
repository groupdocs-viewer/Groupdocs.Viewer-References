---
title: "Κλάση PdfOptions"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά επιλογές για απόδοση σε έγγραφα PDF."
type: docs
url: /el/python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

Αναπαριστά επιλογές για απόδοση σε έγγραφα PDF.

Για λεπτομέρειες, δείτε την τεκμηρίωση.

Ο τύπος PdfOptions εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | Αρχικοποιεί μια νέα παρουσία της κλάσης PdfOptions. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | Η ιδιότητα απενεργοποιεί την ομαδοποίηση συμβόλων για ακριβή τοποθέτηση συμβόλων κατά την απόδοση της σελίδας. |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | Η ιδιότητα απενεργοποιεί την προστασία αντιγραφής περιεχομένου κατά την απόδοση σε HTML. |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | Η ιδιότητα απενεργοποιεί τυχόν περιορισμούς άδειας για όλες τις γραμματοσειρές στο τρέχον έγγραφο XPS/OXPS. |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | Η ιδιότητα ενεργοποιεί την υποδείξη γραμματοσειράς. |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | Η ιδιότητα ενεργοποιεί την απόδοση κειμένου και γραφικών με τη σειρά z‑order του αρχικού εγγράφου PDF κατά την απόδοση σε HTML. |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | Η επιλογή σταθερής διάταξης ενεργοποιεί την απόδοση εγγράφων PDF και EPUB σε HTML με σταθερή διάταξη. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | Η ποιότητα εικόνας εξόδου για πόρους εικόνας κατά την απόδοση σε HTML. Η προεπιλεγμένη ποιότητα είναι `ImageQuality.LOW`. |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | Το μέγεθος σελίδας εξόδου ορίζεται ώστε να ταιριάζει με το μέγεθος σελίδας του αρχικού εγγράφου PDF. |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | Η επιλογή ενεργοποιεί την απόδοση κειμένων σε αρχεία PDF ως εικόνα στην έξοδο HTML. |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | Η ιδιότητα που ενεργοποιεί την περιτύλιξη κάθε εικόνας στο έγγραφο HTML εξόδου με ετικέτα SVG για βελτίωση της ποιότητας εξόδου. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # Ενεργοποιήστε την υποδείξη γραμματοσειράς κατά την απόδοση σελίδων PDF σε εικόνες.
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### Δείτε επίσης
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
