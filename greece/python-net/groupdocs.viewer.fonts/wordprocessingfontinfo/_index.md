---
title: "Κλάση WordProcessingFontInfo"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από ένα έγγραφο WordProcessing που φορτώθηκε σε μια παρουσία Viewer."
type: docs
url: /el/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από ένα έγγραφο WordProcessing που φορτώθηκε σε ένα [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) αντικείμενο.

Αμετάβλητη δομή.

Οι παρουσίες του παράγονται και επιστρέφονται από το δημόσιο API του [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) και κανονικά δεν πρέπει να δημιουργούνται από τον χρήστη.

Για λεπτομέρειες, δείτε την τεκμηρίωση: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

Ο τύπος WordProcessingFontInfo εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | Σειριοποιεί τις πληροφορίες γραμματοσειράς ως @font-face at-rule και τις γράφει στον καθορισμένο συγγραφέα κειμένου. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | Επιστρέφει πληροφορίες αποσφαλμάτωσης για αυτά τα δεδομένα γραμματοσειράς με το εξής πρότυπο: "name style, embedded/system, format". |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | Το εναλλακτικό όνομα οικογένειας της γραμματοσειράς. Εάν λείπει, τότε μια κενή συμβολοσειρά. |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | Το σύνολο χαρακτήρων αυτής της γραμματοσειράς. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | Το περιεχόμενο αυτής της γραμματοσειράς ως πίνακας byte. Εάν είναι διαθέσιμες μόνο οι μεταπληροφορίες για αυτή τη γραμματοσειρά και το δυαδικό περιεχόμενο δεν είναι διαθέσιμο, η ιδιότητα επιστρέφει None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | Το όνομα οικογένειας της γραμματοσειράς, χωρίς στυλ· ποτέ None ή κενή συμβολοσειρά. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | Η μορφή αυτής της γραμματοσειράς. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | Η ιδιότητα υποδεικνύει εάν αυτή η γραμματοσειρά είναι ενσωματωμένη μέσα στο έγγραφο, φορτωμένη στην παρουσία του [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`), ή είναι μια γραμματοσειρά συστήματος (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | Το στυλ της γραμματοσειράς — μπορεί να είναι Regular, Bold, Italic ή Bold Italic. |

### Δείτε επίσης
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
