---
title: "Κλάση PdfOptimizationOptions"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά τις επιλογές βελτιστοποίησης PDF που θα εφαρμοστούν στο αρχείο PDF εξόδου."
type: docs
url: /el/python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

Αναπαριστά τις επιλογές βελτιστοποίησης PDF που θα εφαρμοστούν στο αρχείο PDF εξόδου.

Για λεπτομέρειες και παραδείγματα κώδικα, δείτε τη σελίδα τεκμηρίωσης.

Ο τύπος PdfOptimizationOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | Αρχικοποιεί τις προεπιλεγμένες τιμές της επιλογής MaxResolution σε 300 και της επιλογής ImageQuality σε 100. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | Η ιδιότητα ενεργοποιεί τη συμπίεση εικόνων στο αρχείο PDF εξόδου. |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | Η ιδιότητα ενεργοποιεί τη μετατροπή του αρχείου PDF εξόδου σε αποχρώσεις του γκρι. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | Η ποιότητα εικόνας στο αρχείο PDF εξόδου, εκφρασμένη ως ποσοστό. |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | Η ιδιότητα ενεργοποιεί τη βελτιστοποίηση του αρχείου PDF εξόδου για προβολή στο διαδίκτυο με έναν web browser. |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | Η μέγιστη ανάλυση στο αρχείο PDF εξόδου. |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | Η ιδιότητα που ενεργοποιεί τη βελτιστοποίηση λογιστικών φύλλων σε αρχεία PDF. |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | Η ιδιότητα ενεργοποιεί την αφαίρεση σχολίων από το αρχείο PDF εξόδου. |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | Η ιδιότητα ενεργοποιεί την αφαίρεση πεδίων φόρμας από ένα αρχείο PDF. |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | Η ιδιότητα αφαιρεί αχρησιμοποίητα (ορφανά) αντικείμενα από ένα αρχείο PDF. |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | Η ιδιότητα αφαιρεί αχρησιμοποίητες (ορφανές) ροές από ένα αρχείο PDF που αναφέρονται στο λεξικό πόρων της σελίδας αλλά δεν χρησιμοποιούνται ποτέ στα περιεχόμενα της σελίδας. Απενεργοποιημένη εξ ορισμού (`False`); ορίζοντάς την σε `True` μειώνει το μέγεθος του PDF εξόδου. |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | Η ιδιότητα ενεργοποιεί τον ορισμό της μέγιστης ανάλυσης στο αρχείο PDF εξόδου. |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | Η ιδιότητα δημιουργεί υποσύνολα γραμματοσειρών στο αρχείο PDF εξόδου. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # Ενεργοποίηση γραμμικοποίησης για ταχύτερη προεπισκόπηση στο web
        view_options.pdf_optimization_options.lineriaze = True
        # Αφαιρέστε τις σημειώσεις και τα πεδία φόρμας για να μειώσετε το μέγεθος
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### Δείτε επίσης
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
