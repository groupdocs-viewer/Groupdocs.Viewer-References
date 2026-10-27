---
title: "PdfFontInfo κλάση"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Περιλαμβάνει μεταδεδομένα και δυαδικά δεδομένα μιας γραμματοσειράς PDF που φορτώνεται σε μια παρουσία Viewer, η οποία μπορεί να είναι ενσωματωμένη στο έγγραφο ή εγκατεστημένη στο λειτουργικό σύστημα όπου εκτελείται το GroupDocs.Viewer."
type: docs
url: /el/python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

Περιλαμβάνει μεταδεδομένα και δυαδικά δεδομένα μιας γραμματοσειράς PDF που φορτώθηκε σε ένα αντικείμενο του [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), η οποία μπορεί να ενσωματωθεί στο έγγραφο ή να εγκατασταθεί στο λειτουργικό σύστημα όπου εκτελείται το GroupDocs.Viewer.

Ο τύπος PdfFontInfo εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | Σειριοποιεί αυτές τις πληροφορίες γραμματοσειράς ως @font-face at-rule και τις γράφει στον καθορισμένο συγγραφέα κειμένου. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | Το περιεχόμενο αυτής της γραμματοσειράς ως πίνακας byte, ή None εάν είναι διαθέσιμα μόνο τα μεταδεδομένα και το δυαδικό περιεχόμενο δεν είναι διαθέσιμο. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | Το όνομα οικογένειας της γραμματοσειράς, χωρίς στυλ· ποτέ None ή κενή συμβολοσειρά. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | Η μορφή αυτής της γραμματοσειράς. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | Η ιδιότητα υποδεικνύει εάν η γραμματοσειρά είναι ενσωματωμένη μέσα στο έγγραφο PDF και φορτώνεται στην παρουσία Viewer (`True`), ή όχι. |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | Η ιδιότητα υποδεικνύει εάν αυτή η γραμματοσειρά είναι παρούσα (εγκατεστημένη) στο λειτουργικό σύστημα όπου εκτελείται το GroupDocs.Viewer. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | Το στυλ της γραμματοσειράς· μπορεί να είναι Regular, Bold, Italic ή Bold Italic. |

### Δείτε επίσης
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
