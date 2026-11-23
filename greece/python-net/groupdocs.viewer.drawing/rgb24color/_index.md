---
title: "Rgb24Color κλάση"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά χρώμα 24-bit RGB με 8 bits ανά κανάλι (Red, Green, Blue) και χωρίς διαφάνεια."
type: docs
url: /el/python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 80
---


## Rgb24Color class

Αναπαριστά χρώμα 24-bit RGB με 8 bits ανά κανάλι (Red, Green, Blue) και χωρίς διαφάνεια.

Αυτός ο τύπος έχει σχεδιαστεί ώστε να είναι χρήσιμος για (αλλά όχι περιορισμένο σε) λειτουργίες CSS. Δείτε περισσότερα: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Ο τύπος Rgb24Color εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/) |  |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Καθορίζει εάν αυτό το χρώμα είναι ίσο με το καθορισμένο [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Ελέγχει αυτό το χρώμα με το καθορισμένο χρώμα [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) για ισότητα. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#obj) | Ελέγχει αυτό το χρώμα σε σχέση με το καθορισμένο μη μετατρεπόμενο χρώμα. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#red-green-blue) | Δημιουργεί μια τιμή [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) από τις καθορισμένες τιμές των καναλιών κόκκινου, πράσινου και μπλε. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/) | Επιστρέφει τη φωτεινότητα (Lightness) του μοντέλου Hue‑Saturation‑Lightness (HSL) για αυτήν την παρουσίαση [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hash_code/) | Επιστρέφει έναν κωδικό κατακερματισμού που ορίζει το τρέχον χρώμα. Δεν είναι συμβατό με `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/) | Επιστρέφει το συστατικό απόχρωσης (hue) του χρώματος στο χρωματικό χώρο HSL, εκφρασμένο σε μοίρες. Εάν το χρώμα είναι σε κλίμακα του γκρι (R == G == B), η απόχρωση είναι ακαθόριστη και η μέθοδος επιστρέφει 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/) | Ο κορεσμός Hue‑Saturation‑Lightness (HSL) για αυτήν την παρουσίαση [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/) | Επιστρέφει την τιμή ARGB αυτής της παρουσίασης [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/), συμβατή με `System.Drawing.Color`. |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/) | Επιστρέφει αυτό το χρώμα σε δεκαεξαδική αναπαράσταση συμβολοσειράς. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/) | Σειριοποιεί αυτήν την παρουσίαση [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) σε σημειογραφία της συνάρτησης CSS 'rgb'. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_string/) | Σειριοποιεί αυτήν την παρουσίαση [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) σε μορφή 'rgb(r, g, b)'. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b/) | Το μπλε συστατικό του χρώματος ως 8-bit ακέραιος χωρίς πρόσημο [0..255]. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g/) | Το πράσινο στοιχείο του χρώματος ως 8-bit ακέραιος χωρίς πρόσημο στο εύρος 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default/) | Η ιδιότητα υποδεικνύει εάν αυτή η παρουσίαση [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) είναι η προεπιλογή (Μαύρο) – όλα τα τρία κανάλια είναι ορισμένα στο 0. |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r/) | Το κόκκινο στοιχείο του χρώματος ως 8-bit ακέραιος χωρίς πρόσημο (0..255). |

### Δείτε επίσης
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
