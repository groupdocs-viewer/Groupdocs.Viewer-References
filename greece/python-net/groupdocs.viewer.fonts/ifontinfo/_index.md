---
title: "IFontInfo κλάση"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει μια κοινή διεπαφή για όλες τις γραμματοσειρές που μπορούν να εξαχθούν από όλες τις υποστηριζόμενες οικογένειες μορφών εγγράφων: PDF, WordProcessing, Spreadsheet και Presentation."
type: docs
url: /el/python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

Αντιπροσωπεύει μια κοινή διεπαφή για όλες τις γραμματοσειρές που μπορούν να εξαχθούν από όλες τις υποστηριζόμενες οικογένειες μορφών εγγράφων: PDF, WordProcessing, Spreadsheet και Presentation.

Ο τύπος IFontInfo εκθέτει τα ακόλουθα μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | Σειριοποιεί αυτές τις πληροφορίες γραμματοσειράς ως @font-face at-rule και τις γράφει στον καθορισμένο συγγραφέα κειμένου. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | Το δυαδικό περιεχόμενο της γραμματοσειράς ως πίνακας byte, εάν είναι διαθέσιμο, ή None εάν δεν είναι. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | Το όνομα οικογένειας της γραμματοσειράς ως συμβολοσειρά. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | Η μορφή αυτής της γραμματοσειράς ως enum — TrueType, TrueType Collection, OpenType, Embedded OpenType ή `FontFormat.unknown`. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | Το στυλ της γραμματοσειράς ως enum (Regular, Bold, Italic ή Bold Italic); ορισμένες μορφές εγγράφων μπορεί να υποστηρίζουν μόνο [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/). |

### Δείτε επίσης
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
