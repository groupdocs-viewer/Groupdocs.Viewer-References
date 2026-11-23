---
title: "Argb32Color"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αναπαριστά χρώμα 32bit σε μορφή ARGB με 8 bits για κάθε κανάλι Alpha, Red, Green, Blue. Υποστηρίζει διαφάνεια."
type: docs
weight: 950
url: /el/net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color structure

Αναπαριστά χρώμα 32-bit σε μορφή ARGB, με 8 bits για κάθε κανάλι (Alpha, Red, Green, Blue). Υποστηρίζει διαφάνεια.

```csharp
public struct Argb32Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | Επιστρέφει το μέρος alpha του χρώματος ως 8-bit μη υπογεγραμμένο ακέραιο [0..255] |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | Επιστρέφει το μέρος alpha του χρώματος σε ποσοστό στο εύρος (0..1). |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | Επιστρέφει το μέρος blue του χρώματος ως 8-bit μη υπογεγραμμένο ακέραιο [0..255] |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | Επιστρέφει το μέρος green του χρώματος ως 8-bit μη υπογεγραμμένο ακέραιο [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/argb32color/isdefault) { get; } | Δείχνει αν αυτή η [`Argb32Color`](../argb32color) αντικείμενο είναι προεπιλεγμένη (Διαφανής) - όλα τα 4 κανάλια έχουν τιμή 0. Ίδιο με [`IsEmpty`](./isempty) |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | Δείχνει αν αυτή η [`Argb32Color`](../argb32color) αντικείμενο χρώματος δεν έχει αρχικοποιηθεί - όλα τα 4 κανάλια έχουν τιμή 0. Ίδιο με Προεπιλογή και Διαφανές. Ίδιο με [`IsDefault`](./isdefault) |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | Δείχνει αν αυτή η [`Argb32Color`](../argb32color) αντικείμενο είναι πλήρως αδιαφανές, χωρίς διαφάνεια (το κανάλι Alpha έχει μέγιστη τιμή) |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | Δείχνει αν αυτή η [`Argb32Color`](../argb32color) αντικείμενο είναι πλήρως διαφανές - το κανάλι Alpha έχει την ελάχιστη (0) τιμή, έτσι τα άλλα κανάλια R, G και B δεν έχουν ορατό αποτέλεσμα. |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | Δείχνει εάν αυτό το [`Argb32Color`](../argb32color) αντικείμενο είναι διαφανές (όχι πλήρως διαφανές, αλλά επίσης όχι πλήρως αδιαφανές) |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | Επιστρέφει το κόκκινο μέρος του χρώματος ως 8-bit ακέραιο χωρίς πρόσημο [0..255] |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | Επιστρέφει την τιμή Int32 του χρώματος ως 32-bit ακέραιο με πρόσημο |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | Δημιουργεί ένα [`Argb32Color`](../argb32color) αντικείμενο από τις 32-bit συνιστώσες του (άλφα, κόκκινο, πράσινο και μπλε), συμβατό με την τιμή που παράγεται από τη μέθοδο `System.Drawing.Color.ToArgb()` |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | Δημιουργεί ένα νέο [`Argb32Color`](../argb32color) αντικείμενο από τις καθορισμένες τιμές, αλλά με επανακαθορισμένη τιμή άλφα (αδιαφάνειας) |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | Δημιουργεί ένα νέο [`Argb32Color`](../argb32color) αντικείμενο από το καθορισμένο [`Rgb24Color`](../rgb24color), αλλά με την καθορισμένη τιμή άλφα (αδιαφάνειας) |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | Δημιουργεί μία τιμή [`Argb32Color`](../argb32color) από τα καθορισμένα κανάλια Κόκκινο, Πράσινο, Μπλε, ενώ το κανάλι Άλφα είναι πλήρως αδιαφανές |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | Δημιουργεί μία τιμή [`Argb32Color`](../argb32color) από τα καθορισμένα κανάλια Κόκκινο, Πράσινο, Μπλε και Άλφα |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | Δημιουργεί ένα πλήρως αδιαφανές (A=255) χρώμα από μία μοναδική τιμή, η οποία θα εφαρμοστεί σε όλα τα κανάλια |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | Ελέγχει αυτό το χρώμα με το καθορισμένο χρώμα [`Argb32Color`](../argb32color) για ισότητα |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | Ελέγχει αυτό το χρώμα με το καθορισμένο μη μετατρεπόμενο |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | Ελέγχει αυτό το χρώμα με το καθορισμένο χρώμα [`Rgb24Color`](../rgb24color) για ισότητα |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | Επιστρέφει τη φωτεινότητα (Lightness) του Hue-Saturation-Lightness (HSL) για αυτή τη [`Argb32Color`](../argb32color) παρουσία. |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού που ορίζει το τρέχον χρώμα. Δεν είναι συμβατό με το GetHashCode |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | Επιστρέφει την τιμή απόχρωσης Hue-Saturation-Lightness (HSL), σε μοίρες, για αυτή τη [`Argb32Color`](../argb32color) παρουσία. Εάν R == G == B, η απόχρωση δεν έχει νόημα και η επιστρεφόμενη τιμή είναι 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | Ο κορεσμός Hue-Saturation-Lightness (HSL) για αυτή τη [`Argb32Color`](../argb32color) παρουσία |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | Επιστρέφει την τιμή ARGB αυτής της [`Argb32Color`](../argb32color) παρουσία, συμβατή με τη μέθοδο `System.Drawing.Color.ToArgb()` |
| [ToHexRGB](../../groupdocs.viewer.drawing/argb32color/tohexrgb)() | Σειριοποιεί αυτή τη [`Argb32Color`](../argb32color) παρουσία στη δεκαεξαδική σημειογραφία `##RRGGBB` ως συμβολοσειρά χωρίς κανάλι άλφα |
| [ToHexRGBA](../../groupdocs.viewer.drawing/argb32color/tohexrgba)() | Σειριοποιεί αυτή τη [`Argb32Color`](../argb32color) παρουσία στη δεκαεξαδική σημειογραφία `##RRGGBBAA` ως συμβολοσειρά με κανάλι άλφα |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | Σειριοποιεί αυτή τη [`Argb32Color`](../argb32color) παρουσία στη σημειογραφία συνάρτησης CSS 'rgb'. Το κανάλι άλφα αυτού του χρώματος θα παραλειφθεί κατά τη σειριοποίηση. |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | Σειριοποιεί αυτή τη [`Argb32Color`](../argb32color) παρουσία στη σημειογραφία συνάρτησης CSS 'rgba' |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | Σειριοποιεί αυτή τη [`Argb32Color`](../argb32color) παρουσία στη πιο κατάλληλη σημειογραφία συνάρτησης CSS ανάλογα με τη διαφάνεια |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | Συγκρίνει δύο χρώματα [`Argb32Color`](../argb32color) και επιστρέφει μια boolean τιμή που υποδεικνύει αν τα δύο ταιριάζουν. (2 τελεστές) |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | Μετατρέπει ρητά το 32-bit [`Argb32Color`](../argb32color) σε 24-bit [`Rgb24Color`](../rgb24color). Το κανάλι άλφα του πηγαίου [`Argb32Color`](../argb32color) θα χαθεί μετά τη μετατροπή, επειδή το [`Rgb24Color`](../rgb24color) δεν υποστηρίζει διαφάνεια. |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | Μετατρέπει έμμεσα το 24-bit [`Rgb24Color`](../rgb24color) σε 32-bit [`Argb32Color`](../argb32color). Το κανάλι άλφα της εξόδου [`Argb32Color`](../argb32color) θα οριστεί σε `255` - πλήρως αδιαφανές. |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | Συγκρίνει δύο χρώματα [`Argb32Color`](../argb32color) και επιστρέφει μια Boolean τιμή που υποδεικνύει αν τα δύο δεν ταιριάζουν. (2 τελεστές) |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | Επιστρέφει ένα κενό χρώμα, το οποίο δεν έχει πληροφορίες καναλιών και είναι πλήρως διαφανές. Το ίδιο με το '[`Transparent`](./transparent)'. Προεπιλεγμένη τιμή. |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | Πλήρως διαφανές κενό χρώμα. Το ίδιο με την προεπιλεγμένη τιμή χρώματος '[`Empty`](./empty)'. |

### Παρατηρήσεις

Αυτός ο τύπος έχει σχεδιαστεί ώστε να είναι χρήσιμος για (αλλά όχι περιορισμένο σε) λειτουργίες CSS. Δείτε περισσότερα: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Δείτε επίσης

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
