---
title: "κλάση Argb32Color"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά χρώμα 32-bit σε μορφή ARGB, με 8 bit σε κάθε κανάλι (Alpha, Red, Green, Blue)."
type: docs
url: /el/python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

Αναπαριστά χρώμα 32-bit σε μορφή ARGB, με 8 bits ανά κανάλι (Alpha, Red, Green, Blue). Υποστηρίζει διαφάνεια.

Αυτός ο τύπος έχει σχεδιαστεί ώστε να είναι χρήσιμος για (αλλά όχι περιορισμένο σε) λειτουργίες CSS. Δείτε περισσότερα: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Ο τύπος Argb32Color εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Ελέγχει αν αυτό το χρώμα είναι ίσο με το καθορισμένο [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Καθορίζει αν αυτό το χρώμα είναι ίσο με το καθορισμένο [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | Ελέγχει αν αυτό το χρώμα ισούται με το καθορισμένο μη μετατρεπόμενο χρώμα. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_rgb_24_color/) |  |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | Δημιουργεί μια παρουσία Argb32Color από μια τιμή ARGB 32-bit, συμβατή με τιμές που παράγονται από `System.Drawing.Color.ToArgb()`. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Δημιουργεί μια νέα παρουσία [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) από την καθορισμένη παρουσία, αλλά με επαναπροσδιορισμένη τιμή άλφα (διαφάνειας). |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Δημιουργεί μια νέα παρουσία Argb32Color από ένα καθορισμένο Rgb24Color, αλλά με μια καθορισμένη τιμή άλφα (διαφάνειας). |
| [from_other_with_alpha_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_argb_32_color/) |  |
| [from_other_with_alpha_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | Δημιουργεί μια τιμή Argb32Color από καθορισμένα κανάλια Κόκκινο, Πράσινο, Μπλε, με το κανάλι Alpha ορισμένο σε πλήρη αδιαφάνεια. |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | Δημιουργεί μια τιμή [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) από καθορισμένες τιμές καναλιών κόκκινου, πράσινου, μπλε και άλφα. |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | Δημιουργεί ένα πλήρως αδιαφανές (A=255) χρώμα από μια μοναδική τιμή byte που εφαρμόζεται σε όλα τα κανάλια. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | Επιστρέφει τη φωτεινότητα/λαμπρότητα Hue‑Saturation‑Lightness (HSL) για αυτήν την παρουσία [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | Επιστρέφει έναν κωδικό κατακερματισμού που ορίζει το τρέχον χρώμα· δεν είναι συμβατός με `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | Επιστρέφει την τιμή απόχρωσης Hue‑Saturation‑Lightness (HSL), σε μοίρες, για αυτήν την παρουσία [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/); εάν R == G == B, η απόχρωση δεν έχει νόημα και η μέθοδος επιστρέφει 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | Επιστρέφει τον κορεσμό Hue‑Saturation‑Lightness (HSL) αυτής της παρουσίας [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | Επιστρέφει την τιμή ARGB αυτής της παρουσίας [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/), συμβατή με τη μέθοδο `System.Drawing.Color.ToArgb()`. |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | Σειριοποιεί αυτό το αντίγραφο [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) σε σημειογραφία δεκαεξαδικού `##RRGGBB` ως συμβολοσειρά χωρίς το κανάλι άλφα. |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | Σειριοποιεί αυτό το αντίγραφο [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) σε σημειογραφία δεκαεξαδικού `##RRGGBBAA` ως συμβολοσειρά με το κανάλι άλφα. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | Σειριοποιεί αυτό το αντίγραφο [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) στη σημειογραφία συνάρτησης CSS `rgb`, παραλείποντας το κανάλι άλφα. |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | Σειριοποιεί αυτό το αντίγραφο [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) στη σημειογραφία συνάρτησης CSS 'rgba'. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | Σειριοποιεί το αντίγραφο Argb32Color στη πιο κατάλληλη σημειογραφία συνάρτησης CSS ανάλογα με τη διαφάνεια. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | Το στοιχείο άλφα του χρώματος ως 8-bit ακέραιος χωρίς πρόσημο στο εύρος 0..255. |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | Το στοιχείο άλφα του χρώματος ως δεκαδικός αριθμός στο εύρος 0..1. |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | Το μπλε στοιχείο του χρώματος ως 8-bit ακέραιος χωρίς πρόσημο στο εύρος 0..255. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | Το πράσινο στοιχείο του χρώματος ως 8-bit ακέραιος χωρίς πρόσημο στο εύρος 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | Η ιδιότητα υποδεικνύει εάν αυτό το αντίγραφο [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) είναι προεπιλεγμένο (διαφανές), σημαίνοντας ότι όλα τα τέσσερα κανάλια έχουν τιμή 0· είναι ισοδύναμη με [`Argb32Color.is_empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/). |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | Η ιδιότητα υποδεικνύει εάν αυτό το αντίγραφο [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) δεν έχει αρχικοποιηθεί (όλα τα τέσσερα κανάλια έχουν τιμή 0). Είναι ισοδύναμη με το προεπιλεγμένο ή διαφανές χρώμα και ταιριάζει με [`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/). |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | Η ιδιότητα υποδεικνύει εάν αυτό το αντίγραφο [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) είναι πλήρως αδιαφανές, χωρίς διαφάνεια (το κανάλι Alpha έχει τη μέγιστη τιμή). |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | Η ιδιότητα υποδεικνύει εάν αυτό το αντίγραφο [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) είναι πλήρως διαφανές—το κανάλι Alpha έχει την ελάχιστη (0) τιμή, έτσι τα κανάλια R, G και B δεν έχουν ορατό αποτέλεσμα. |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | Η ιδιότητα υποδεικνύει εάν αυτό το αντίγραφο [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) είναι ημιδιαφανές (δεν είναι πλήρως διαφανές, αλλά ούτε και πλήρως αδιαφανές). |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | Το κόκκινο στοιχείο του χρώματος ως 8-bit ακέραιος χωρίς πρόσημο (0..255). |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | Η 32-bit υπογεγραμμένη ακέραια αναπαράσταση του χρώματος. |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | Επιστρέφει ένα κενό χρώμα, το οποίο δεν έχει πληροφορίες καναλιών και είναι πλήρως διαφανές. Το ίδιο με ''. Προεπιλεγμένη τιμή. |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | Πλήρως διαφανές κενό χρώμα. Το ίδιο με την προεπιλεγμένη τιμή χρώματος ''. |

### Παράδειγμα

```python
from groupdocs.viewer.drawing import Argb32Color

# Δημιουργήστε ένα πλήρως αδιαφανές κίτρινο χρώμα (RGB 255, 255, 0)
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### Δείτε επίσης
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
