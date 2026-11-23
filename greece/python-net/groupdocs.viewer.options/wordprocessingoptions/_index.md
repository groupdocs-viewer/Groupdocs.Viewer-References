---
title: "WordProcessingOptions κλάση"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Περιέχει επιλογές για την απόδοση εγγράφων Word."
type: docs
url: /el/python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

Περιέχει επιλογές για την απόδοση εγγράφων Word.

Για λεπτομέρειες, δείτε την τεκμηρίωση στο https://docs.groupdocs.com/viewer/net/render-word-documents/.

Ο τύπος WordProcessingOptions εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | Αρχικοποιεί τις επιλογές για την απόδοση εγγράφων επεξεργασίας κειμένου. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | Δημιουργεί και επιστρέφει ένα πλήρες βαθύ αντίγραφο αυτών των επιλογών. |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | Καθορίζει εάν το συγκεκριμένο [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/) αντικείμενο είναι ίσο με αυτό το αντικείμενο. |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | Το κάτω περιθώριο μιας σελίδας. |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | Η επιλογή ενεργοποιεί το kerning και άλλες λειτουργίες OpenType κατά την απόδοση αραβικών, εβραϊκών, Ινδικών βασισμένων σε λατινικό αλφάβητο ή κυριλλικών γραφών. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | Η οριζόντια ανάλυση για τις παραγόμενες εικόνες σε κουκκίδες ανά ίντσα. Αυτή η επιλογή χρησιμοποιείται μόνο κατά την απόδοση εγγράφων WordProcessing σε μορφές PNG ή JPEG. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | Το αριστερό περιθώριο μιας σελίδας. |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | Η θέση αρίθμησης σελίδων για το φορτωμένο έγγραφο WordProcessing, η οποία μπορεί να εφαρμόσει την αρίθμηση σελίδων με εξαναγκασμό· από προεπιλογή είναι `WordsPageNumberLocation.not_apply`, διατηρώντας το έγγραφο αμετάβλητο. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | Το μέγεθος της εξαγόμενης σελίδας. |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | Η ιδιότητα ενεργοποιεί την απόδοση των παρακολουθούμενων αλλαγών (αναθεωρήσεων). |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | Το δεξί περιθώριο μιας σελίδας. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | Το πάνω περιθώριο μιας σελίδας σε σημεία. |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | Η επιλογή απενεργοποιεί την πλοήγηση από τον πίνακα περιεχομένων όταν οριστεί σε True για απόδοση HTML ή PDF. |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | Η ιδιότητα καθορίζει εάν πεδία ορισμένων τύπων ενημερώνονται πριν από την αποθήκευση του εγγράφου WordProcessing σε μορφές HTML, PDF, PNG ή JPEG. Η προεπιλογή είναι True, που σημαίνει ότι τα πεδία ενημερώνονται. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | Η κάθετη ανάλυση για τις παραγόμενες εικόνες σε κουκκίδες ανά ίντσα, χρησιμοποιείται μόνο κατά την απόδοση εγγράφων WordProcessing σε μορφές PNG ή JPEG. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Δείτε επίσης
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
