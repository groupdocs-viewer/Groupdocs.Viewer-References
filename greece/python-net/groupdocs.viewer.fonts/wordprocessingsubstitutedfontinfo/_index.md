---
title: "WordProcessingSubstitutedFontInfo κλάση"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από ένα έγγραφο WordProcessing, η οποία αρχικά δεν χρησιμοποιείται στο φορτωμένο έγγραφο παρουσία Viewer, αλλά λειτουργεί ως γραμματοσειρά αντικατάστασης για εκείνες που…"
type: docs
url: /el/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από ένα έγγραφο WordProcessing, η οποία αρχικά δεν χρησιμοποιείται στο φορτωμένο έγγραφο του [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), αλλά λειτουργεί ως γραμματοσειρά αντικατάστασης για εκείνες που δεν μπορούν να βρεθούν στο στόχο μηχάνημα. Οι αντικατεστημένες γραμματοσειρές υπάρχουν μόνο για την οικογένεια μορφών WordProcessing.

Αμετάβλητη δομή. Οι στιγμές της παράγονται και επιστρέφονται από το δημόσιο API του [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) και κανονικά δεν πρέπει να δημιουργούνται από τον χρήστη. Για λεπτομέρειες, δείτε την τεκμηρίωση: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

Ο τύπος WordProcessingSubstitutedFontInfo εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | Σειριοποιεί τις πληροφορίες γραμματοσειράς ως @font-face at-rule και τις γράφει στον καθορισμένο συγγραφέα κειμένου. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | Επιστρέφει μια συμβολοσειρά εντοπισμού σφαλμάτων που περιέχει πληροφορίες γραμματοσειράς στη μορφή "original-name -> substituted-name style, format". |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | Το περιεχόμενο της αντικατεστημένης γραμματοσειράς ως πίνακας byte. Ποτέ δεν είναι None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | Το όνομα οικογένειας της αντικατεστημένης γραμματοσειράς, χωρίς στυλ. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | Η μορφή αυτής της αντικατεστημένης (μη αρχικής) γραμματοσειράς. |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | Το όνομα οικογένειας της αρχικής γραμματοσειράς, η οποία δεν μπορεί να βρεθεί σε μηχανή-στόχο, χωρίς στυλ. Ποτέ δεν είναι null ή κενή συμβολοσειρά. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | Το στυλ της αρχικής γραμματοσειράς — μπορεί να είναι Regular, Bold, Italic ή Bold Italic. |

### Δείτε επίσης
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
