---
title: "Κλάση SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από ένα έγγραφο υπολογιστικού φύλλου που φορτώθηκε σε μια παρουσία Viewer."
type: docs
url: /el/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

Περιλαμβάνει μεταπληροφορίες και δυαδικά δεδομένα μιας γραμματοσειράς από ένα έγγραφο λογιστικού φύλλου που φορτώθηκε σε ένα [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) αντικείμενο. Τα έγγραφα λογιστικού φύλλου δεν μπορούν να έχουν ενσωματωμένες γραμματοσειρές, έτσι μια γραμματοσειρά που επιστρέφεται από το [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) εγκαθίσταται στο λειτουργικό σύστημα όπου εκτελείται ο viewer.

Ο τύπος SpreadsheetFontInfo εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | Σειριοποιεί τις πληροφορίες γραμματοσειράς ως @font-face at-rule και τις γράφει στον καθορισμένο συγγραφέα κειμένου. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | Το σύνολο χαρακτήρων αυτής της γραμματοσειράς. |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | Το χρώμα αυτής της γραμματοσειράς. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | Το περιεχόμενο αυτής της γραμματοσειράς ως πίνακας byte. Εάν είναι διαθέσιμες μόνο μεταπληροφορίες για αυτή τη γραμματοσειρά και το δυαδικό της περιεχόμενο δεν είναι διαθέσιμο, η ιδιότητα επιστρέφει None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | Το όνομα οικογένειας της γραμματοσειράς, χωρίς στυλ, ποτέ δεν είναι null ή κενό string. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | Η μορφή αυτής της γραμματοσειράς. |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | Η γραμματοσειρά έχει μια μοναδική διαγράμμιση. |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | Η γραμματοσειρά έχει υπογράμμιση. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | Το στυλ αυτής της γραμματοσειράς — μπορεί να είναι Regular, Bold, Italic ή Bold Italic. |

### Δείτε επίσης
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
